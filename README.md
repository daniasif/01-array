# Sistem Pengelolaan Nilai Mahasiswa Menggunakan Array

## Deskripsi Program

Program ini dibuat menggunakan bahasa Python untuk mengelola nilai mahasiswa menggunakan struktur data array (list).

Fitur program:
- Input 10 nilai mahasiswa
- Menampilkan nilai tertinggi
- Menampilkan nilai terendah
- Menghitung rata-rata nilai
- Menghitung jumlah mahasiswa lulus (>=60)
- Menampilkan grafik nilai tertinggi & terendah
- Menampilkan grafik kelulusan mahasiswa

Program terdiri dari 2 file:

Soal_01.py  
Program utama untuk mengolah data nilai mahasiswa.

Soal_02.py  
Program untuk menampilkan visualisasi grafik menggunakan matplotlib.

## Konsep Array

Array adalah struktur data yang digunakan untuk menyimpan beberapa data dalam satu variabel dengan tipe data yang sama.

Pada program ini array digunakan untuk menyimpan nilai mahasiswa. Dengan array, kita bisa melakukan berbagai operasi seperti:

- Menyimpan banyak nilai
- Mencari nilai tertinggi
- Mencari nilai terendah
- Menghitung rata-rata
- Menghitung jumlah mahasiswa yang lulus

Contoh array pada Python:

nilai = [80, 75, 90, 60]

## Screenshot Hasil Eksekusi

<img width="614" height="337" alt="Screenshot 2026-03-10 at 13 15 07" src="https://github.com/user-attachments/assets/3d7f3d5b-bb39-4f34-a3c0-537b1e44c981" />

<img width="325" height="342" alt="Screenshot 2026-03-10 at 13 16 00" src="https://github.com/user-attachments/assets/896b443f-5fcf-4721-beea-647358fbccf5" />

<img width="300" height="216" alt="Screenshot 2026-03-10 at 13 16 18" src="https://github.com/user-attachments/assets/9971e410-a3d9-4a6b-8854-adebf078f348" />

## Analisis Kompleksitas

Input Nilai Mahasiswa  
Kompleksitas: O(n)  
Karena program melakukan perulangan untuk memasukkan nilai sebanyak n mahasiswa.

Mencari Nilai Tertinggi  
Kompleksitas: O(n)  
Karena program harus membandingkan seluruh nilai dalam array.

Mencari Nilai Terendah  
Kompleksitas: O(n)  
Karena setiap elemen dalam array harus diperiksa.

Menghitung Rata-rata  
Kompleksitas: O(n)  
Karena semua nilai dijumlahkan terlebih dahulu.

Menghitung Jumlah Kelulusan  
Kompleksitas: O(n)  
Karena program mengecek setiap nilai apakah >= 60.

## Refleksi Pembelajaran

Dari tugas ini saya jadi lebih paham bagaimana menggunakan array (list) di Python untuk menyimpan banyak data dalam satu variabel. Dengan array, data nilai mahasiswa bisa dikelola dengan lebih mudah.
Saya juga belajar membuat perulangan untuk mencari nilai tertinggi, nilai terendah, menghitung rata-rata, serta menentukan berapa mahasiswa yang lulus berdasarkan nilai minimal.
Selain itu, saya mencoba menggunakan library matplotlib untuk membuat grafik sederhana. Dengan grafik, data nilai dan kelulusan mahasiswa bisa dilihat dengan lebih jelas dibandingkan hanya dalam bentuk angka.
