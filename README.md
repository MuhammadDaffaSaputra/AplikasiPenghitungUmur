# AplikasiPenghitungUmur
 Latihan 2 Muhammad Daffa Saputra 2210010440

## README

### Aplikasi Penghitung Umur

Aplikasi ini adalah sebuah program berbasis GUI (Graphical User Interface) yang dikembangkan menggunakan **Java Swing**. Program ini dirancang untuk menghitung umur seseorang berdasarkan tanggal lahir yang diinputkan.

---

### Fitur Utama
1. **Input Tanggal Lahir**: Menggunakan komponen `JDateChooser` untuk mempermudah pemilihan tanggal.
2. **Penghitungan Umur**: Menghitung umur hingga ke detail tahun, bulan, dan hari.
3. **Tampilan Hasil**: Menampilkan umur dalam format yang mudah dibaca.

---

### Prasyarat
- **JDK** versi 8 atau lebih baru.
- Library tambahan:
  - **JCalendar**: Library pihak ketiga untuk komponen tanggal (`JDateChooser`).
  
  Pastikan library ini sudah diimport ke dalam project Anda.

---

### Cara Menjalankan
1. **Import Project**:
   - Buka project ini di IDE Java seperti NetBeans atau IntelliJ IDEA.
   - Tambahkan library **JCalendar** jika belum ada.
2. **Kompilasi dan Jalankan**:
   - Kompilasi kode menggunakan IDE.
   - Jalankan program untuk membuka GUI aplikasi.
3. **Penggunaan**:
   - Pilih tanggal lahir menggunakan komponen **Tanggal Lahir**.
   - Klik tombol **Hitung**.
   - Umur akan ditampilkan dalam format: `XX Tahun YY Bulan ZZ Hari`.

---

### Struktur GUI
1. **Label**:
   - `Tanggal Lahir`: Menunjukkan input untuk tanggal lahir.
   - `Umur`: Menunjukkan hasil umur.
   - `Hasil`: Menunjukkan detail umur.
2. **Komponen**:
   - **JDateChooser**: Untuk memilih tanggal lahir.
   - **JTextField**: Menampilkan hasil hitungan umur.
   - **JButton**: Tombol untuk memproses penghitungan umur.

---

### Teknologi yang Digunakan
- **Java Swing**: Untuk membangun antarmuka pengguna.
- **JCalendar**: Untuk komponen pemilihan tanggal.
- **Java Time API**: Untuk menghitung selisih waktu (umur).

---

### Contoh Output
Jika tanggal lahir yang dipilih adalah `1 Januari 2000` dan tanggal saat ini adalah `16 November 2024`, maka hasil yang ditampilkan:
```
24 Tahun 10 Bulan 15 Hari
```

---

### Kontributor
- **Nama**: [Pengembang]
- **Perangkat**: ACER

---

### Lisensi
Proyek ini dilisensikan di bawah [MIT License](https://opensource.org/licenses/MIT). Anda bebas untuk menggunakan, memodifikasi, dan mendistribusikan ulang kode sumber ini sesuai dengan ketentuan lisensi.
