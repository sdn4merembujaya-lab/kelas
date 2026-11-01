# Perangkat Ajar Kurikulum Merdeka SD

Aplikasi web statis untuk guru SD: CP/TP/ATP, program tahunan dan semester, jurnal, modul ajar, LKPD, soal (ulangan harian, mid semester, semester), analisis soal, daftar nilai, dan administrasi kelas.

## Isi repositori
| File | Fungsi |
|---|---|
| `index.html` | Halaman login (tab Pengguna dan Admin), dashboard, dan Data Guru |
| `perangkat-ajar.html` | Seluruh dokumen perangkat ajar (dimuat di dalam index.html) |
| `guru.json` | Daftar akun guru dan admin (hasil unduhan dari menu Data Guru) |

## Cara pakai
1. Buka alamat situs, lalu masuk lewat tab **Pengguna** (guru) atau **Admin**.
2. Pilih Kelas, Semester, dan Mata pelajaran di bilah atas, lalu pilih dokumen di menu kiri.
3. Isi data sekolah dan siswa di **Pengaturan data**. Data tersimpan di browser masing-masing akun.
4. Menu **Soal** membuat draf soal dari TP; sunting isinya, lalu isi skor di **Analisis Soal**.

## Mengelola akun (admin)
Menu **Data Guru**: daftar, edit, blokir, dan hapus akun. Akun baru hanya tersimpan di browser admin. Agar berlaku di semua perangkat, klik **Unduh guru.json** lalu ganti file `guru.json` di repositori.

## Tips memperbarui situs
- Unggah semua file yang berubah **sekaligus** dalam satu commit, supaya hanya ada satu proses deploy.
- Jangan menghapus lalu mengunggah ulang file; cukup unggah dengan nama yang sama.
- Setelah deploy hijau di tab Actions, buka situs dan tekan Ctrl+Shift+R.
