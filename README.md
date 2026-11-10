# Kalkulator IKM / SKM (aplikasi desktop)

Tauri 2 + HTML (tanpa server, tanpa internet). Tampilan liquid-glass, tema gelap/terang, 6 warna aksen.
Logika hitung IKM sama dengan Kalkulator-IKM-SKM.html.

## Cara mendapat file .exe (tanpa install apa pun di PC)
1. Buat repo baru di GitHub, unggah seluruh isi folder ini (termasuk folder .github).
2. Tab **Actions** > workflow **build** > **Run workflow**.
3. Setelah selesai (sekitar 10-15 menit), unduh artifact `IKM-windows-latest` berisi `*-setup.exe` dan `.msi`.
   (macOS dan Linux juga dibangun otomatis.)

## Build sendiri di PC (butuh Node.js 20 + Rust)
    npm install
    npx tauri icon app-icon.png
    npx tauri build

Installer tidak ditandatangani; Windows: More info > Run anyway.
