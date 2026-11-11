# HAENOFFICE

Aplikasi desktop Windows untuk membuka, membuat, dan mengedit **Word (.docx), Excel (.xlsx), PowerPoint (.pptx), PDF, dan Markdown**, dibantu asisten AI yang berjalan di komputer sendiri. Dibuat untuk admin HAEN GROUP.

Repositori ini **hanya berisi installer**. Kode sumber tidak dipublikasikan.

## Unduh

➡️ **[Unduh versi terbaru](https://github.com/sa4nha-beep/HAENOFFICE-Releases/releases/latest)**: pilih file `HAENOFFICE-Setup-x.y.z.exe`.

## Cara memasang

1. Jalankan `HAENOFFICE-Setup-x.y.z.exe`.
2. Jika muncul layar biru "Windows protected your PC", klik **More info → Run anyway**. Peringatan ini muncul karena installer belum ditandatangani (*code signing*), bukan karena ada virus.
3. Ikuti langkah pemasangan, lalu buka **HAENOFFICE** dari Start Menu.

Syarat: Windows 10/11 64-bit, RAM minimal 8 GB, ruang kosong ±5 GB (termasuk model AI).

## Menyalakan asisten AI (gratis, offline)

1. Pasang **Ollama** dari [ollama.com](https://ollama.com).
2. Buka Command Prompt, lalu unduh modelnya (±3,4 GB, cukup sekali):
   ```
   ollama pull gemma3:4b
   ```
3. Buka HAENOFFICE. Badge di panel AI harus hijau bertuliskan **"Lokal · gemma3:4b"**.

Kalau muncul pesan tentang **driver NVIDIA**, perbarui driver kartu grafis dari [nvidia.com/drivers](https://www.nvidia.com/drivers), lalu restart PC.

## Pembaruan

HAENOFFICE memeriksa dan mengunduh versi baru secara otomatis saat dibuka (bisa dimatikan di **⚙ Pengaturan → Pembaruan aplikasi**). Setelah unduhan selesai, klik **Mulai ulang & pasang**, atau pembaruan akan dipasang saat aplikasi ditutup. Keutuhan file pembaruan diperiksa dengan hash SHA-512 sebelum dipasang.

## Privasi

Semua file dibuka, diedit, dan disimpan di komputer Anda. Dengan AI lokal (Ollama), isi dokumen tidak keluar dari PC. Aplikasi tidak mengirim data pemakaian ke mana pun. Satu-satunya koneksi otomatis adalah pemeriksaan pembaruan ke halaman rilis ini.

## Lisensi

© HAEN GROUP. HAENOFFICE memakai pustaka sumber terbuka berlisensi MIT, Apache-2.0, ISC, dan BSD. Teks lisensinya terlampir di setiap rilis (`THIRD_PARTY_LICENSES.txt`).
