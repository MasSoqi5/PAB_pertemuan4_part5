# PAB_Pertemuan-4_part-5
# Mini E-Commerce Shopping Cart (Flutter + Provider)
## Deskripsi Project

Project ini merupakan implementasi sederhana aplikasi Mini E-Commerce Shopping Cart menggunakan framework Flutter dengan state management Provider. Aplikasi ini dibuat untuk memahami konsep manajemen state global menggunakan ChangeNotifier, serta implementasi interaksi dasar keranjang belanja pada aplikasi mobile.

Pada versi ini, project juga menambahkan materi lanjutan Part 6 (Advanced Provider Topics): MultiProvider, perbedaan Consumer vs context.watch vs context.read, serta optimasi performa menggunakan Selector.

Pengguna dapat melihat daftar produk, menambahkan produk ke keranjang, mencari dan memfilter produk, mengatur jumlah item, menghapus item, serta melihat total harga sebelum melakukan checkout melalui halaman checkout terpisah.untuk memuat banyak barang tanpa harus terlihat bug ataupun hal yang menggangu


## Fitur Aplikasi

**Model produk**

**Model cart item**

**Cart model dengan ChangeNotifier**

**Halaman daftar produk**

**Tombol tambah ke cart**

**Badge jumlah item pada icon cart**

**Halaman cart berisi semua item**

**Penambahan dan pengurangan jumlah item**

**Hapus item dari cart**

**Perhitungan total harga otomatis**

**Pesan ketika cart kosong**

Checklist Penilaian:
Wajib (70 Points)

### Kita Mulaikan dengan menambahkan Cart ke Shopping List

<img width="948" height="633" alt="image" src="https://github.com/user-attachments/assets/8f9d8c28-0d3e-45c6-b621-25241fa8097d" />

### Habis itu kita lihat hasil belanjaan kita

<img width="952" height="1027" alt="image" src="https://github.com/user-attachments/assets/fee0c444-b94f-4b8c-bbdb-f634ed9851bb" />

### Lalu kita bisa menimbang antara menambah maupun mengurangi barang

<img width="944" height="1019" alt="image" src="https://github.com/user-attachments/assets/387d9762-3c0b-47fb-8626-81e4bbdbd981" />

### Ataupun menghapus barang yang tidak ingin dibeli

<img width="949" height="1023" alt="image" src="https://github.com/user-attachments/assets/be277a8c-db60-41ca-8e34-cd2bc0797a18" />

### Kalau nggak ada yang dibeli yah kosong begini saja

<img width="944" height="1022" alt="image" src="https://github.com/user-attachments/assets/6134cf3e-0379-46ac-8c75-0376db1e08c4" />

### Pada akhirnya jika kita sudah menyelesaikan progress maka tekan icon troli untuk menyudahi pembelian

<img width="947" height="574" alt="image" src="https://github.com/user-attachments/assets/bd68166c-dcb2-4e11-b417-9388365d3724" />

ini Hasilnya kalau kita berhasil memasukkan Barang 

<img width="965" height="63" alt="image" src="https://github.com/user-attachments/assets/af0d891e-7711-4448-b7d8-ed40c0bd5534" />



# 📁 Struktur Folder

Struktur folder pada project ini disusun untuk memisahkan setiap bagian aplikasi agar lebih rapi, mudah dipahami, dan mudah dikembangkan kembali di masa depan.

project-name/
│── public/
│   └── index.html
│
│── src/
│   ├── assets/
│   │   └── images/
│   │
│   ├── components/
│   │   └── ExampleComponent.vue
│   │
│   ├── views/
│   │   └── Home.vue
│   │
│   ├── App.vue
│   └── main.js
│
│── package.json
│── README.md

Penjelasan:

public/
Folder ini berisi file statis yang tidak diproses oleh Vue, seperti index.html.

src/
Folder utama tempat seluruh kode aplikasi ditulis.

assets/
Digunakan untuk menyimpan file statis seperti gambar, icon, atau stylesheet.

components/
Berisi komponen Vue yang dapat digunakan kembali di berbagai bagian aplikasi.

views/
Berisi halaman utama aplikasi (biasanya digunakan jika memakai routing).

App.vue
Komponen utama (root component) yang menjadi wadah seluruh tampilan aplikasi.

main.js
File entry point yang menjalankan aplikasi Vue dan menghubungkannya ke HTML.

package.json
File konfigurasi project yang berisi dependency dan script perintah.

README.md
Dokumentasi project.

# 🚀 Cara Menjalankan Project

Ikuti langkah berikut untuk menjalankan aplikasi secara lokal:

1. Clone Repository
git clone https://github.com/username/nama-repository.git

Masuk ke folder project:

cd nama-repository
2. Install Dependencies

Pastikan Node.js sudah terinstall, lalu jalankan:

npm install

Perintah ini akan menginstall semua library yang dibutuhkan sesuai package.json.

3. Menjalankan Server Development
npm run dev

Setelah itu aplikasi dapat diakses melalui browser pada alamat:

http://localhost:5173

(Port bisa berbeda tergantung konfigurasi.)

4. Build untuk Production

Jika ingin membuat versi siap deploy:

npm run build

Hasil build akan tersimpan di folder dist/.

🧑‍💻 Cara Penggunaan Aplikasi

Langkah penggunaan aplikasi:

Jalankan aplikasi menggunakan perintah npm run dev.

Buka aplikasi melalui browser.

Pengguna dapat berinteraksi dengan tampilan yang tersedia, seperti:

Melihat data yang ditampilkan

Menginput informasi (jika ada form)

Menekan tombol aksi yang tersedia

Setiap komponen pada aplikasi dibuat menggunakan Vue Component sehingga tampilan bersifat modular dan mudah dikembangkan.

## ✨ Teknologi yang Digunakan

Vue.js

JavaScript

HTML

CSS

Node.js

NPM

# Kesimpulan

Project ini menunjukkan bahwa penggunaan Provider mempermudah pengelolaan state global pada aplikasi Flutter. Implementasi ChangeNotifier memungkinkan UI diperbarui secara otomatis tanpa perlu mengirim data antar widget secara manual.

Penambahan MultiProvider, penggunaan Consumer/context.watch/context.read yang tepat, serta Selector untuk rebuild terfokus membantu meningkatkan skalabilitas dan performa aplikasi.

Struktur pemisahan model dan halaman membantu meningkatkan keterbacaan kode serta memudahkan pengembangan lanjutan seperti integrasi database atau API.

