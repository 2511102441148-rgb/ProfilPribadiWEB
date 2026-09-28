Nama: Muhammad Aidil Fachriyansyah
NIM: 2511102441148

Tiga perubahan dari contoh modul:
1. Menambahkan atribut `data-bs-theme="dark"` pada tag  untuk menerapkan mode gelap bawaan Bootstrap agar sesuai dengan tema website sebelumnya.
2. Memodifikasi Navigasi menggunakan class `.sticky-top` dan menambahkan efek blur kustom (backdrop-filter) agar menu tetap terlihat di atas saat di-scroll namun tetap elegan.
3. Mengganti tata letak list keahlian biasa menjadi sistem Grid Bootstrap (`.row.g-4` dan `.col-md-4`) dengan komponen 3 Card yang dilengkapi gambar ilustrasi.

Satu kendala dan cara mengatasinya:
- Kendala: Gambar profil berubah menjadi tidak proporsional (gepeng) saat dimasukkan ke dalam class Bootstrap.
- Cara mengatasi: Saya menambahkan properti CSS kustom `object-fit: cover;` dikombinasikan dengan menetapkan ukuran `width` dan `height` yang sama agar gambar tetap bulat sempurna menggunakan class `.rounded-circle`.
