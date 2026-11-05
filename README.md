# Flutter CRUD API – REST API

## 📝 Deskripsi Singkat

Flutter CRUD API merupakan aplikasi berbasis Flutter yang menerapkan operasi **CRUD (Create, Read, Update, Delete)** menggunakan REST API. Aplikasi ini menggunakan JSONPlaceholder sebagai API untuk mengelola data post berupa nama dan pekerjaan.

Aplikasi memungkinkan pengguna menambahkan data baru, melihat data yang ditampilkan, memperbarui data, dan menghapus data. Komunikasi dengan REST API dilakukan menggunakan package `http`, sedangkan perubahan tampilan dikelola menggunakan `StatefulWidget` dan `setState()`.

## ✨ Fitur Utama

- **Create Data:** Menambahkan data baru melalui dialog input.
- **Read Data:** Menampilkan data post dalam bentuk Card.
- **Update Data:** Memperbarui nama dan pekerjaan melalui dialog edit.
- **Delete Data:** Menghapus data melalui menu Delete dengan konfirmasi terlebih dahulu.
- **REST API:** Menghubungkan aplikasi dengan JSONPlaceholder menggunakan HTTP POST, PUT, dan DELETE.
- **JSON Parsing:** Mengubah respons JSON menjadi objek Dart menggunakan Model Class `Post`.
- **State Management:** Menggunakan `setState()` untuk memperbarui tampilan setelah perubahan data.
- **AlertDialog:** Menampilkan dialog untuk menambah, mengubah, dan mengonfirmasi penghapusan data.
- **SnackBar:** Menampilkan notifikasi ketika operasi berhasil atau gagal.

## 🛠️ Teknologi dan Package

- **Flutter & Dart:** Framework dan bahasa pemrograman untuk membangun aplikasi.
- **http:** Mengirim permintaan dan menerima respons dari REST API.
- **intl:** Mengatur format tanggal dan waktu.
- **google_fonts:** Menggunakan font dari Google Fonts.
- **JSONPlaceholder:** REST API publik yang digunakan untuk pengujian operasi CRUD.

## 📂 Struktur Proyek

```text
flutter_crud_api/
├── android/
├── ios/
├── lib/
│   └── main.dart
└── pubspec.yaml
```

## 🚀 Cara Menjalankan Aplikasi

1. Clone repository ini:

   ```bash
   git clone https://github.com/username/flutter_crud_api.git
   ```

2. Masuk ke direktori proyek:

   ```bash
   cd flutter_crud_api
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Jalankan aplikasi:

   ```bash
   flutter run
   ```

## 📌 Kesimpulan

Praktikum ini menerapkan operasi CRUD (Create, Read, Update, Delete) pada aplikasi Flutter menggunakan REST API JSONPlaceholder. Package `http` digunakan untuk melakukan komunikasi dengan server melalui metode HTTP, sedangkan data JSON diubah menjadi objek Dart menggunakan Model Class `Post`.

Penggunaan `async`, `await`, dan `setState()` membantu proses pengelolaan data serta memperbarui tampilan aplikasi setelah data ditambahkan, diubah, atau dihapus. Melalui praktikum ini, dapat dipahami cara membangun aplikasi Flutter yang dapat mengelola data dengan REST API.
