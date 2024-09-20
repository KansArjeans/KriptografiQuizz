# KriptografiQuizz
Pemenuhan Tugas Quizz Kriptografi

# Cipher Program

Program ini adalah aplikasi GUI untuk enkripsi dan dekripsi menggunakan tiga algoritma kriptografi: Vigenère Cipher, Hill Cipher, dan Playfair Cipher. 

## Fitur
- Enkripsi dan dekripsi teks menggunakan tiga metode cipher.
- Memungkinkan pengguna untuk memuat teks dari file.
- Menyediakan antarmuka pengguna yang sederhana dan intuitif.

## Cara Penggunaan

1. **Jalankan Program**
   - Untuk menjalankan program, pastikan Anda memiliki Python dan pustaka Tkinter serta NumPy terinstal.
   - Jalankan file Python menggunakan perintah:
     python nama_file.py

2. **Masukkan Teks**
   - Di bagian "Input Text", masukkan teks yang ingin dienkripsi atau didekripsi.
   - Anda juga dapat mengklik tombol "Open File" untuk memuat teks dari file `.txt`.

3. **Masukkan Kunci**
   - Di bagian "Key (min. 12 characters)", masukkan kunci untuk enkripsi atau dekripsi. Kunci minimal harus terdiri dari 12 karakter untuk Vigenère dan 4 karakter untuk Hill Cipher.

4. **Pilih Metode Cipher**
   - Pilih metode cipher yang diinginkan dari menu dropdown "Cipher Method".

5. **Enkripsi/Dekripsi**
   - Klik tombol "Encrypt" untuk mengenkripsi teks, atau klik tombol "Decrypt" untuk mendekripsi teks.
   - Hasil akan ditampilkan di bagian "Output Text".

## Algoritma
1. **Vigenère Cipher**:
   - Metode enkripsi yang menggunakan kunci untuk mengenkripsi teks. Kunci diulang sesuai panjang plaintext.

2. **Hill Cipher**:
   - Menggunakan matriks kunci 2x2 untuk enkripsi. Teks dibagi menjadi pasangan karakter.

3. **Playfair Cipher**:
   - Menggunakan matriks 5x5 untuk enkripsi. Karakter 'J' diganti dengan 'I'.

## Persyaratan
- Python 3.x
- NumPy
- Tkinter

## Lisensi
Program ini dirilis di bawah lisensi MIT. Silakan lihat file LICENSE untuk informasi lebih lanjut.

## Penulis
Zerin Angellyca Philia
4611422107


