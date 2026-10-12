# 🛡️ UjianKu Pro

Aplikasi ujian online & offline dengan sistem anti-curang, audio listening, dan dukungan gambar soal.

## ✨ Fitur

- 🔐 **Token Ujian** - Verifikasi sebelum masuk
- 🛡️ **Anti-Curang** - Deteksi pindah tab, keluar fullscreen, split screen, DevTools
- ⚠️ **2x Pelanggaran = Diskualifikasi** - Peringatan dulu di pelanggaran pertama
- 🎧 **Audio Listening** - Upload MP3 untuk soal listening
- 🖼️ **Gambar Soal** - Upload gambar dengan zoom
- 📝 **Import Soal** - Dukung .docx, .pdf, .txt, .md
- 📄 **Jawaban Terpisah** - File soal & kunci terpisah
- 👥 **Multi-Kelas** - VII-XII dengan roster siswa otomatis
- 🔑 **Password Toggle** - Lihat/sembunyikan password
- 💾 **Offline First** - Semua data tersimpan lokal
- 📱 **PWA Ready** - Bisa diinstall seperti app

## 🚀 Cara Pakai

### Offline (Lokal)
1. Download repo ini
2. Buka `index.html` di browser
3. Login guru: password `guru2024`
4. Buat soal, siswa ujian

### Online (GitHub Pages)
1. Fork repo ini
2. Settings → Pages → Deploy from main
3. Akses: `https://username.github.io/ujianku-pro`

## 🔑 Default Login

| Peran | Password |
|-------|----------|
| Guru | `guru2024` |
| Token Ujian | `654321` |

## 📖 Panduan

### Untuk Guru
1. Klik **"Portal Guru / Admin"**
2. Login dengan password `guru2024`
3. Tab **Bank Soal** - tambah/import soal
4. Tab **Pengaturan** - atur durasi & token
5. Tab **Siswa** - lihat hasil ujian

### Untuk Siswa
1. Buka aplikasi
2. Masukkan token dari guru
3. Pilih mapel, kelas, nama
4. Ikuti ujian (fullscreen wajib)

## 🛠️ Format Import Soal

### File Soal (.docx/.pdf/.txt/.md)