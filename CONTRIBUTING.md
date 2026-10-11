# Panduan Kontribusi (CONTRIBUTING)

## Pendahuluan

Repository ini dibuat sebagai tempat penyimpanan tugas dan dokumentasi pembelajaran mata kuliah Rekayasa Perangkat Lunak (RPL).

Meskipun repository ini digunakan untuk tugas individu, panduan kontribusi tetap dibuat sebagai latihan memahami alur kerja kolaborasi dalam pengembangan perangkat lunak.

## 1. Aturan Kontribusi

Setiap kontribusi harus berkaitan dengan tujuan repository, seperti perbaikan dokumentasi, pembaruan materi, atau penyempurnaan tugas.

Sebelum melakukan perubahan, kontributor perlu memahami isi repository dan memastikan perubahan yang dibuat tidak menghilangkan informasi penting.

## 2. Penggunaan Branch

Branch `main` digunakan untuk menyimpan hasil pekerjaan yang sudah diperiksa dan siap digunakan.

Untuk mengerjakan perubahan, gunakan branch terpisah dengan format berikut:

- `feature/nama-perubahan` untuk penambahan fitur atau konten baru.
- `fix/nama-perbaikan` untuk memperbaiki kesalahan.
- `docs/nama-dokumentasi` untuk memperbarui dokumentasi.

Contoh nama branch:

- `docs/update-readme`
- `fix/typo-laporan`
- `feature/tambah-dokumentasi`

## 3. Aturan Commit

Setiap perubahan perlu dicatat melalui commit dengan pesan yang jelas dan menggambarkan pekerjaan yang dilakukan.

Format pesan commit:

`tipe: deskripsi singkat`

Contoh:

- `docs: update README`
- `docs: add AI policy`
- `fix: correct documentation typo`
- `feat: add new project documentation`

Usahakan setiap commit berisi perubahan yang saling berkaitan agar riwayat pekerjaan mudah dipahami.

## 4. Pull Request dan Review

Jika bekerja bersama kontributor lain, perubahan dilakukan melalui branch terpisah dan diajukan menggunakan Pull Request (PR).

Langkah-langkahnya:

1. Membuat branch baru sesuai jenis pekerjaan.
2. Melakukan perubahan pada file yang diperlukan.
3. Memeriksa kembali isi file sebelum melakukan commit.
4. Melakukan commit dengan pesan yang sesuai.
5. Mengirimkan Pull Request ke branch `main`.
6. Meminta minimal satu anggota tim untuk melakukan review sebelum perubahan digabungkan.

Untuk tugas individu, pemeriksaan dilakukan secara mandiri sebelum perubahan dimasukkan ke branch utama.

## 5. Penanganan Kesalahan dan Perubahan

Jika ditemukan kesalahan, kontributor perlu menjelaskan masalah dan melakukan perbaikan tanpa menghapus riwayat perubahan sebelumnya.

Apabila terdapat perubahan kebutuhan, alasan dan hasil perubahan perlu didokumentasikan agar dapat dipahami kembali.

## 6. Etika Kontribusi

Setiap kontributor diharapkan untuk:

- Menghargai pendapat dan hasil pekerjaan orang lain.
- Berkomunikasi dengan sopan dan terbuka.
- Tidak mengakui pekerjaan orang lain sebagai hasil pribadi.
- Menjaga kerahasiaan data pribadi dan informasi sensitif.
- Menerima kritik dan saran yang membangun.
- Menyelesaikan perbedaan pendapat melalui diskusi bersama.

## Penutup

Panduan ini dibuat untuk membiasakan proses pengembangan perangkat lunak yang terstruktur, transparan, dan bertanggung jawab. Dengan mengikuti aturan kontribusi, perubahan dalam repository dapat dikelola dan ditinjau dengan lebih baik.