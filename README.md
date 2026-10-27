# Absensi Siswa Mapel Bahasa Inggris

Halaman web satu file untuk prank "absensi" kelas X TKJ. Teman mengisi Nama, Kelas, dan Kehadiran, menekan **Kirim**, lalu muncul halaman prank.

## Isi folder

| File | Fungsi |
| --- | --- |
| `index.html` | Seluruh halaman (HTML, CSS, dan JavaScript dalam satu file) |
| `vercel.json` | Pengaturan sederhana untuk Vercel |
| `README.md` | Petunjuk ini |

## Cara kerja

1. Halaman 1: formulir berisi Nama, Kelas (X TKJ 1, 2, 3), dan Kehadiran (Hadir, Sakit, Izin).
2. Setelah **Kirim** ditekan, muncul animasi "Mengirim jawaban..." sekitar 3,5 detik.
3. Halaman 2: stempel **PRANK!** dengan tulisan "Selamat, Anda kena prank!".

Tidak ada data yang dikirim atau disimpan. Semua berjalan di browser pengguna.

## Cara membagikan lewat Vercel

1. Buat akun di [vercel.com](https://vercel.com) (bisa masuk dengan GitHub).
2. Buat repository baru di GitHub, lalu unggah semua file di folder ini.
3. Di Vercel pilih **Add New**, lalu **Project**, pilih repository tadi, lalu **Deploy**.
4. Salin link `namaproject.vercel.app` dan bagikan ke teman.

## Cara membagikan lewat GitHub Pages

1. Unggah file ke repository GitHub yang bersifat **Public**.
2. Buka **Settings**, lalu **Pages**.
3. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Link muncul dalam 1 sampai 2 menit, berbentuk `https://namakamu.github.io/namarepo/`.

## Mengubah isi

Buka `index.html` dengan editor teks dan cari bagian berikut:

- **Judul dan deskripsi**: di dalam `<header class="card title-card">`.
- **Pilihan kelas atau kehadiran**: baris `<label class="opt">` di bagian masing-masing.
- **Tulisan prank**: teks di dalam `<section class="card center" id="prank">`.
- **Warna**: variabel di bagian atas `<style>` (`--accent` untuk ungu, `--bg` untuk latar).

## Catatan

- Halaman ini hanya candaan. Jangan menambahkan kolom untuk kata sandi, nomor identitas, atau data pribadi lain.
- Beri tahu teman bahwa ini prank setelah berhasil, supaya tidak ada yang salah paham.
- Halaman ini bukan produk Google dan tidak meniru logo atau merek Google.
