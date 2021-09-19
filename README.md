# PresOn

[![Netlify Status](https://api.netlify.com/api/v1/badges/0c404268-689f-4f13-b3c1-1710c51a6ef5/deploy-status)](https://preson.netlify.com)

## Tentang PresOn

**PresOn** merupakan kepanjangan dari Presensi Online. WebApps ini muncul saat pandemi melanda. Terinspirasi dari GoogleForm, ingin membuat tampilan antar muka formulir secara custom. Fitur dari PresOn ini adalah perekapan secara otomatis presensi ke dalam Google Spreadsheet secara realtime. Inspirasi dan ide didapatkan dari:

- [Ngobar #29 WPU](https://youtu.be/2XosKncBoQ4)

## Cara Kerja dan Bahan

### Pengajar / Guru / Dosen

- Selayaknya seorang Guru, setiap pembelajaran diawali dengan presensi. Maka dari itu, silahkan buka File Google Spreadsheet berikut. [File Rekap Presensi](https://docs.google.com/spreadsheets/d/1kiJXMnO5KWO1ZWDOdRbcW5sbO8yqYg4Ab3icBg5463I/edit?usp=sharing), _untuk pak Dika sudah saya jadikan editor. Jadi, bisa melakukan langkah selanjutnya._
- Pada kolom berwarna kuning, klik dua kali untuk membuka tanggal pertemuan pembelajaran.
- Persilahkan siswa untuk presensi sesuai tanggal yang sudah ditentukan.

### Pelajar / Siswa / Mahasiswa

- Akses laman presensi online pada link berikut. [Link Presensi](https://preson.netlify.com)
- Lakukan presensi sesuai dengan NIM yang sudah disediakan

#### Daftar NIM yang tersedia / Testing saja

- 21100001
- 21100002
- 21100003
- 21100004
- 21100005
- 21100006
- 21100007
- 21100008
- 21100009
- 21100010

**NIM yang tidak tersedia dan mengisikan tanggal tidak sesuai dengan tanggal yang ditentukan oleh pengajar maka tidak akan terekap. Rekap hanya terjadi sekali saja meskipun mengisikan berkali-kai**

## Konsep

Konsep dari web ini sederhana. Siswa / Mahasiswa presensi, seperti menggunakan google form. Kemudian masuk ke google spreadsheet diolah dengan rumus-rumus administrasi. Dilemparkan ke dalam view yang dimana siswa / mahasiswa bisa langsung cek dan mengingatkan pengajar kalau belum merekap presensi.

## Teknologi

Website ini menggunakan sistem yang sederhana, yaitu sebagai berikut.

- Bootstrap Veersi 5
- Bootstrap Data Picker
- Java Script
- [jamiewilson/form-to-google-sheets](https://github.com/jamiewilson/form-to-google-sheets)
- Google Spreadsheet
- Google AppsScript
- Netlify untuk deploy

## Kekurangan

- Website ini sebatas uji coba dan latihan dari video tutorial Ngobar #29 WPU. Sembari mengasah kemampuan dalam dunia web development. Berniat web ini bisa menjadi website yang dinamis untuk menambahkan kelas, membuat daftar presensi sampai dengan produksi presensi.
- Masih belum bisa membatasi dengan waktu. Jika tidak berkenan untuk presensi rumus yang ada pada google spreadsheet harus di hapus untuk setiap pertemuan.
- Belum bisa validasi nim yang terdaftar seperti pada google form validation.
