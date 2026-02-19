# Tugas 2 Pengembangan Aplikasi Mobile

* **Nama : Muhammad Bimastiar**
* **NIM : 123140211**

## Deskripsi Tugas
Buat aplikasi "News Feed Simulator" menggunakan Kotlin dengan fitur:
1. Flow yang mensimulasikan data berita baru setiap 2 detik
2. Filter berita berdasarkan kategori tertentu
3. Transform data menjadi format yang ditampilkan
4. StateFlow untuk menyimpan jumlah berita yang sudah dibaca
5. Coroutines untuk mengambil detail berita secara async

##  Cara Menjalankan Aplikasi (Langkah-langkah)

Karena proyek ini menggunakan basis **Compose Multiplatform**, aplikasi akan berjalan sebagai aplikasi Desktop. Berikut adalah panduan langkah demi langkah untuk menjalankannya:

1. **Persiapan IDE:** Pastikan Anda menggunakan **Android Studio** atau **IntelliJ IDEA** versi terbaru.
2. **Buka Proyek:** Pilih menu `File > Open...` dan arahkan ke folder proyek `NewsFeedSimulator` ini.
3. **Tunggu Gradle Sync:** Perhatikan bagian pojok kanan bawah IDE. Tunggu hingga proses sinkronisasi Gradle selesai sepenuhnya (mengunduh *dependencies* Kotlin, Coroutines, dan Compose).
4. **Jalankan Aplikasi:** Klik tombol **Run** (segitiga hijau) atau tekan `Shift + F10`.
5. **Simulasi Berjalan:** Jendela aplikasi Desktop akan terbuka. Anda akan melihat berita baru masuk secara otomatis setiap 2 detik. Cobalah klik filter kategori di bagian atas, dan klik salah satu *card* berita untuk melihat *counter* "Dibaca" bertambah.

## Hasil

### tampilan mobile
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d5414a94-e5b2-4a1d-8e59-fb146299594a" />

### tampilan dekstop
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/75aca5fe-7828-4872-ab5c-66335b1da77f" />
