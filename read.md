<div id="p14">

# <span style="color: blue">Praktikum 14 | Pagination dan Pencarian</span>

## 1. Membuat Pagination

- Terletak di folder `app/Controllers`, buka file `Artikel.php`. Ubah menjadi berikut :
  ![img76](/image/14.1.PNG)
  <br>

- Terletak di folder `app/Views/artikel`, buka file `admin_index.php`, tambah kode berikut : `<?= $pager->links(); ?>`
  ![img77](/image/14.2.PNG)
  <br>

- Buka kembali teks editor (VScode), ubah isi file `.env` menjadi berikut :
  ![img79](image/14.3.PNG)
  <br>

- Akses kembali `http://localhost:8080/admin/artikel`. Menampilkan artikel maksimal 4 per halaman.

- Halaman 1
  ![img80](image/14.4.PNG)
  <br>

- Halaman 2
  ![img81](/imgage/14.5.PNG)
  <br>

## 2. Membuat Pencarian

- Terletak di folder `app/Controllers`, buka file `Artikel.php`. Ubah menjadi berikut :
  ![img82](/image/14.6.PNG)
  <br>

- Terletak di folder `app/Views/artikel`, buka file `admin_index.php`. Ubah menjadi berikut :
  ![img83](/image/14.7.PNG)
  <br>

- Juga berikut :
  ![img84](/image/14.8.PNG)
  <br>

- Akses kembali `http://localhost:8080/admin/artikel`. Kemudian ketik artikel yang akan di cari, selanjutnya tekan `cari`.

- Proses mencari artikel `Tambah Artikel 3`
- Artikel ditemukan.
  ![img86](/image/14.9.PNG)
  <br>

## 3. Upload Gambar

- Terletak di folder `app/Controllers`, buka file `Artikel.php`. Ubah menjadi berikut :
  ![img87](/image/14.10.PNG)
  <br>

- Terletak di folder `app/Views/artikel`, buka file `form_add.php`. Ubah menjadi berikut :
  ![img88](/image/14.11.PNG)
  <br>

- Akses kembali `http://localhost:8080/admin/artikel`. Kemudian pilih menu `Tambah Artikel`
- Lalu isi Artikel dan pilih Gambar
  ![img89](/image/14.12.PNG)
  ![img92](/image/14.13.PNG)
  <br>

- Otomatis diarahkan kembali ke menu admin. Pilih halaman ke-3 (terakhir ditambah). Untuk melihat tampilannya, tekan menu `artikel`.
- Berikut tampilannya.
  ![img93](/image/14.14.PNG)
  ![img93](/image/14.15.PNG)
  <br>

</div>
