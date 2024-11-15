# Tugas 5: Aplikasi Penghitung Kata

**Nabila Parastiwi - 2210010420 - Kelas 5A Reg Pagi Banjarmasin**  
Mata Kuliah: Pemrograman Berbasis Objek

## Deskripsi

Aplikasi ini digunakan untuk menghitung jumlah kata, karakter, dan kalimat dalam teks yang dimasukkan oleh pengguna. Aplikasi ini juga dilengkapi dengan fitur tambahan seperti pencarian kata dan penyimpanan hasil ke file.

## Fitur

- **Penghitungan Kata dan Karakter**: Menghitung jumlah kata dan karakter dalam teks.
- **Penghitungan Kalimat dan Paragraf**: Menampilkan jumlah kalimat dan paragraf dalam teks.
- **Pencarian Kata**: Memungkinkan pengguna mencari kata tertentu dalam teks.
- **Penyimpanan Hasil**: Menyimpan teks dan hasil perhitungan ke file.
- **Real-Time Update**: Menggunakan DocumentListener untuk menghitung secara otomatis saat teks dimasukkan.

## Komponen

- GUI menggunakan JFrame, JPanel, JLabel, JTextArea, JScrollPane, JButton.
- Logika program mencakup:
  - Manipulasi string.
  - Penggunaan ekspresi reguler untuk menghitung kalimat dan kata.
- Event Handling:
  - **ActionListener** untuk tombol "Hitung".
  - **DocumentListener** untuk pembaruan real-time.

## Cara Menjalankan

1. Clone repositori ini ke perangkat Anda.
2. Jalankan aplikasi dengan memastikan Java Runtime Environment (JRE) telah terinstal.
3. Masukkan teks ke dalam JTextArea.
4. Tekan tombol "Hitung" untuk melihat jumlah kata, karakter, dan kalimat.
5. Gunakan fitur pencarian untuk menemukan kata tertentu.
6. Simpan teks dan hasil ke file jika diperlukan.
