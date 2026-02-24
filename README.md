# Tugas Pemrograman Aplikasi Bergerak

**PART 5: Shopping Cart Hands-On**

Nama : Nabila Imtiyaz Agustin

NIM : 2409116011

Kelas : A

Sistem Informasi 2024

# <sub>Deskripsi</sub>

<img width="1910" height="860" alt="image" src="https://github.com/user-attachments/assets/c07cb17b-9d41-4b32-9912-32364c8f65b4" />

Shopping Cart sederhana berbasis Flutter memungkinkan pengguna untuk melihat produk dan menambahkan produk ke dalam keranjang belanja.
Aplikasi menerapkan konsep state management menggunakan Provider dengan ChangeNotifier untuk mengelola data keranjang secara real-time. Setiap perubahan data seperti menambah, mengurangi, atau menghapus item akan langaung memperbarui tampilan tanpa perlu refresh manual.

# <sub>Fitur-Fitur</sub>

**1. Menampilkan Daftar Produk**

- Menampilkan list produk (nama, harga, emoji).
- Menggunakan ListView.builder.
- Data produk berasal dari model Product.

**2. Menambahkan Produk ke Keranjang**

- Tombol Add untuk memasukkan produk ke cart.
- Jika produk sudah ada, quantity otomatis bertambah.
- State langsung diperbarui menggunakan notifyListeners().

**3. Badge Jumlah Item di Icon Cart**

- Icon keranjang menampilkan jumlah total item.
- Badge muncul hanya jika ada item dalam cart.
- Menggunakan Stack dan Positioned.

**4. Halaman Keranjang**

- Menampilkan daftar produk yang sudah ditambahkan.

**5. Menambah & Mengurangi Quantity**

- Tombol + untuk menambah jumlah produk.
- Tombol - untuk mengurangi jumlah produk.
- Jika quantity menjadi 0, produk otomatis dihapus dari cart.

**6. Menghapus Semua Item**

- Tombol delete di AppBar untuk mengosongkan keranjang.

**7. Total Harga Otomatis**

- Total belanja dihitung otomatis dari seluruh item dalam cart.
- Menggunakan getter totalPrice pada cartModel.


# <sub>Widget yang Digunakan</sub>

Berikut ini adalah widget utama yang digunakan:
1. MaterialApp
2. Scaffold
3. AppBar
4. ListView
5. ListView.builder
6. ListTile
7. Column
8. Row
9. Expanded
10. Padding
11. Center
12. Stack
13. ElevetedButton
14. ChangeNotifier
15. ChangeNotifierProvider
