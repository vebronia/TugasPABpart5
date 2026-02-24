# TugasPABpart5
## 👩‍💻 Author

| Nama                      | NIM           | Kelas             |
|---------------------------|---------------|-------------------|
|  Vebronia vitania Lusi    | 2409116112    | Sistem Informasi C|


# 🛒 Aplikasi Shopping Cart (Flutter)

Aplikasi ini merupakan implementasi sistem keranjang belanja sederhana menggunakan Flutter. Fitur utama meliputi penambahan produk, pengelolaan quantity, perhitungan total harga otomatis, serta manajemen state saat navigasi antar halaman.


## 1️⃣ Tambah Produk 3x

📷 **Screenshot: Tambah produk yang sama sebanyak 3 kali**

<img width="1559" height="920" alt="Screenshot 2026-02-24 204631" src="https://github.com/user-attachments/assets/e742d030-16e4-4e84-9e41-bdc1f879634c" />

### Penjelasan:
Ketika produk yang sama ditambahkan sebanyak 3 kali, sistem tidak membuat item baru, melainkan menambah nilai quantity menjadi 3.  
Total harga otomatis dihitung berdasarkan:

total = harga × quantity

## 2️⃣ Tambah Produk Berbeda

📷 **Screenshot: Tambah produk berbeda ke keranjang**

<img width="1541" height="969" alt="Screenshot 2026-02-24 210524" src="https://github.com/user-attachments/assets/7afeb56b-8bf4-4e9d-b08e-de4b1ae1836e" />

### Penjelasan:
Saat menambahkan produk yang berbeda, item baru ditambahkan ke dalam list cart.  
Badge pada ikon keranjang akan menampilkan jumlah total item yang ada di keranjang.

---

## 3️⃣ Increase Quantity (+)

📷 **Screenshot: Tekan tombol + untuk menambah jumlah**

<img width="1555" height="966" alt="Screenshot 2026-02-24 210814" src="https://github.com/user-attachments/assets/07cd8c21-dc5e-456d-bb5e-3e711a97a549" />


### Penjelasan:
Saat tombol "+" ditekan:
- Quantity bertambah
- Total harga per item berubah
- Total keseluruhan keranjang ikut terupdate secara otomatis

---

## 4️⃣ Decrease Quantity ke 1

📷 **Screenshot: Quantity dikurangi menjadi 1**

<img width="1552" height="964" alt="Screenshot 2026-02-24 210745" src="https://github.com/user-attachments/assets/81f50ae5-d225-4486-8ecc-e8231f43a737" />

### Penjelasan:
Jika quantity dikurangi hingga 1, produk tetap berada di dalam keranjang.  
Sistem hanya mengurangi jumlah tanpa menghapus item.


## 5️⃣ Decrease Quantity ke 0 (Auto Remove)

📷 **Screenshot: Quantity menjadi 0 dan item terhapus**

<img width="1555" height="967" alt="Screenshot 2026-02-24 211854" src="https://github.com/user-attachments/assets/687d996f-0c2c-4bde-adf0-86aa79647b18" />

### Penjelasan:
Jika quantity dikurangi dari 1 ke 0, sistem secara otomatis menghapus produk dari keranjang.  
Hal ini mencegah adanya item dengan quantity 0.

---

## 6️⃣ Clear All Cart

📷 **Screenshot: Tombol clear untuk mengosongkan keranjang**

<img width="1549" height="975" alt="image" src="https://github.com/user-attachments/assets/cdcd1fec-b5b8-48f4-998a-37f9e75a0ca5" />


### Penjelasan:
Tombol clear digunakan untuk menghapus seluruh item dalam keranjang sekaligus.  
Setelah ditekan, sistem akan menampilkan tampilan keranjang kosong.

---

## 7️⃣ Tampilan Keranjang Kosong

📷 **Screenshot: Empty Cart View**

<img width="1555" height="967" alt="Screenshot 2026-02-24 211854" src="https://github.com/user-attachments/assets/396c0e0a-3cd9-4c2e-b57b-b5f9db352254" />


### Penjelasan:
Ketika tidak ada item dalam keranjang, aplikasi menampilkan:
- Icon keranjang
- Pesan "Your cart is empty"
- Tombol "Continue Shopping"

Ini meningkatkan user experience agar pengguna tidak bingung.

---

## 8️⃣ Navigasi Kembali (State Tetap)

📷 **Screenshot: Kembali ke halaman produk dan badge tetap benar**

<img width="1556" height="978" alt="image" src="https://github.com/user-attachments/assets/9c6a1390-8f63-49bf-a156-1b2dd9788e15" />

<img width="1559" height="950" alt="image" src="https://github.com/user-attachments/assets/e5fc68ba-feea-4a4a-ba59-ea07fcf16b34" />

### Penjelasan:
Saat pengguna kembali ke halaman produk, badge pada ikon keranjang tetap menunjukkan jumlah item yang benar.  
Ini menunjukkan bahwa state management berjalan dengan baik dan data tidak hilang saat navigasi.





