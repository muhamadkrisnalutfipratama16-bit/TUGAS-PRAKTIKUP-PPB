# CHRIS STORE - Flutter Mobile Application

CHRIS STORE merupakan aplikasi katalog produk berbasis mobile yang dikembangkan menggunakan framework Flutter dan bahasa pemrograman Dart. Aplikasi ini mengambil data produk secara dinamis melalui REST API dari DummyJSON. Aplikasi menyediakan katalog gadget dan teknologi, fitur pencarian produk, serta halaman detail untuk melihat informasi produk secara lengkap.

---

## Fitur Utama

- **Integrasi REST API:** Mengambil data produk secara online menggunakan DummyJSON API dengan package `http`.
- **Filter Kategori Produk:** Menampilkan produk khusus kategori laptop, smartphone, tablet, dan aksesori mobile.
- **Tampilan Grid Katalog:** Menampilkan produk dalam bentuk grid dua kolom dengan desain modern.
- **Pencarian Real-time:** Mencari produk berdasarkan nama produk maupun brand.
- **Halaman Detail Produk:** Menampilkan informasi produk berupa gambar, nama, harga, brand, rating, stok, dan deskripsi.
- **Navigasi Produk:** Pengguna dapat memilih produk untuk melihat halaman detail.
- **Responsive UI:** Tampilan menyesuaikan ukuran layar perangkat.
- **Loading dan Error Handling:** Menampilkan indikator loading dan pesan ketika terjadi masalah koneksi.

---

## Video Demonstrasi

Tonton video demonstrasi aplikasi CHRIS STORE melalui link berikut:

- **YouTube:** [KLIK DI SINI](MASUKKAN_LINK_YOUTUBE_KAMU)

---

## Tech Stack

- **Framework:** Flutter
- **Bahasa Pemrograman:** Dart
- **UI Design:** Material Design 3
- **State Management:** StatefulWidget (Native)
- **Networking:** HTTP Package
- **Data Source:** DummyJSON API
- **Platform:** Android

---

## Persyaratan Sistem & Dependensi

Sebelum menjalankan proyek ini, pastikan perangkat telah memiliki:

- Flutter SDK (versi 3.x atau terbaru yang kompatibel).
- Dart SDK.
- Android Studio atau Visual Studio Code.
- Android SDK dan Emulator (jika menggunakan emulator).
- Koneksi internet untuk mengambil data produk dari API.

### Package yang Digunakan

Tambahkan package berikut pada file `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter
  http: ^1.2.0
```

---

## Cara Menjalankan Proyek

**1. Clone Repository**

```bash
git clone MASUKKAN_LINK_REPOSITORY_KAMU
cd NAMA_FOLDER_PROJECT
```

**2. Install Dependensi**

```bash
flutter pub get
```

**3. Periksa Perangkat Terhubung**

```bash
flutter devices
```

**4. Jalankan Aplikasi**

```bash
flutter run
```

---

## Struktur Folder

```text
CHRIS_STORE/
│
├── lib/
│   └── main.dart
│       # Entry point aplikasi, tampilan katalog,
│       # pencarian, dan halaman detail produk
│
├── android/
├── ios/
├── web/
├── test/
│
├── pubspec.yaml
│   # Konfigurasi project dan dependensi
│
├── pubspec.lock
└── README.md
    # Dokumentasi proyek
```

---

## Identitas Pengembang

- **Nama:** Muhamad Krisna Lutfi Pratama
- **NIM:** 240102063
- **Program Studi:** Teknik Informatika
- **Fakultas:** Sains dan Teknologi
- **Perguruan Tinggi:** Universitas Muhammadiyah Bandung

---

**CHRIS STORE - Modern Gadget & Technology Catalog Application**
