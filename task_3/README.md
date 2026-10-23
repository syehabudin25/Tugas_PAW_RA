# Pendaftaran Pasien Rumah Sakit

- Nama: Syehabudin
- NIM: 124140102
- Kelas: RA
- Mata kuliah: Pengembangan Aplikasi Web
- Tugas Individu 3

## Tentang tugas

Pada tugas ini, saya membuat website sederhana untuk pendaftaran pasien rumah sakit menggunakan HTML dan CSS. Website ini terdiri dari dua halaman, yaitu formulir pendaftaran dan detail pasien.

Formulir berisi nama lengkap, email, nomor telepon, tanggal lahir, jenis kelamin, alamat, dan pilihan dokter. Tampilannya menggunakan warna putih dengan isian dua kolom. Saat dibuka di layar kecil, susunannya menjadi satu kolom.

## Alur pendaftaran

Setelah formulir diisi dan tombol **Daftar** ditekan, pengguna diarahkan ke `detail.html`. Formulir menggunakan method GET, sehingga data yang diisi dikirim melalui query string pada URL.

Contoh singkat:

```text
detail.html?nama=Syehab&dokter=Dokter+Umum
```

Sesuai ketentuan tugas, halaman detail menggunakan data dummy yang ditulis langsung di HTML. Jadi, data pada tabel tetap sama meskipun formulir diisi dengan data lain.

## Penggunaan CSS

File `style.css` digunakan untuk mengatur layout, box, formulir, dan tabel pada kedua halaman. Beberapa selector yang digunakan adalah:

- `body` sebagai selector elemen.
- `.container` sebagai selector class.
- `#pendaftaran` sebagai selector ID.

## Cara menjalankan

1. Buka folder `task_3` di VS Code.
2. Buka `index.html`, lalu jalankan melalui Live Server atau buka langsung di browser.
3. Isi formulir dan klik **Daftar** untuk membuka halaman detail.