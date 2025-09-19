# 🚗 Sistem Pemesanan Layanan Cuci Mobil - Desain Database

Repositori ini menyediakan *Diagram Entitas dan Relasi (ERD)* serta *file migrasi Laravel 12* yang digunakan untuk membangun sistem pemesanan layanan cuci mobil.

## 🗂 Diagram Entitas dan Relasi (ERD)

Desain basis data yang digunakan dalam aplikasi ini:

![ERD](https://i.imgur.com/6SKsoEN.png)

## 📦 Struktur Repositori

* database/migrations/ → berisi file migrasi untuk tabel-tabel berikut:

  * **users**: Menyimpan informasi pengguna aplikasi.
  * **cars**: Menyimpan data kendaraan yang dimiliki oleh pengguna.
  * **services**: Menyimpan data layanan cuci mobil yang tersedia.
  * **bookings**: Menyimpan data pemesanan layanan oleh pengguna.
  * **payments**: Menyimpan data pembayaran terkait pemesanan layanan.
* erd.png → Gambar yang menggambarkan Diagram Entitas dan Relasi (ERD) dalam aplikasi ini.

---