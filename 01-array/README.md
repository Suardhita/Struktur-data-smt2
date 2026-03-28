# 1. Menjelaskan konsep struktur data dan peran array

Array adalah struktur data yang digunakan untuk menyimpan banyak nilai dalam satu variabel. Biasanya, array direpresentasikan menggunakan list karena lebih fleksibel dan mudah digunakan. Data dalam array dapat diakses menggunakan indeks, sehingga mempermudah pengolahan seperti pencarian dan perhitungan. Selain itu, Python juga menyediakan modul array untuk penyimpanan data dengan tipe yang sama. Secara umum, array membantu membuat program lebih rapi dan efisien dalam mengelola data.

Fungsi array di program ini:
1. Menyimpan data nilai mahasiswa
2. Mempermudah proses perulangan (looping)
3. Menghitung nilai statistik
4. Menentukan jumlah lulus dan tidak lulus
5. Menampilkan data ke output dan grafik

# 2. Hasil dari tugas ini
- Input Nilai
- <img width="294" height="194" alt="Screenshot 2026-03-25 235402" src="https://github.com/user-attachments/assets/6833de31-b0cf-4b61-855a-a0488e9d733d" />

- Output Nilai

   <img width="648" height="116" alt="image" src="https://github.com/user-attachments/assets/45a48341-ef4c-4d1f-8cc5-b52d0d7e36ad" />

- Grafik Kelulusan

<img width="638" height="555" alt="Screenshot 2026-03-25 235253" src="https://github.com/user-attachments/assets/16aab9cc-42ec-4d91-849b-0f8ea6c2b580" />

- Grafik Nilai

<img width="640" height="554" alt="Screenshot 2026-03-25 235236" src="https://github.com/user-attachments/assets/cebde2b5-da05-406a-8313-5409efe32ef7" />


# 3. Analisis Kompleksitas

| No | Bagian Program        | Kode Terkait            | Penjelasan                                                                 | Kompleksitas |
|----|----------------------|------------------------|-----------------------------------------------------------------------------|--------------|
| 1  | Input nilai          | for i in range(jumlah) | Menginput nilai sebanyak n kali (sesuai jumlah mahasiswa)                  | O(n)         |
| 2  | Validasi input       | while True             | Validasi dilakukan sampai input benar (diasumsikan konstan)                | O(1)         |
| 3  | Proses data          | for n in data          | Loop untuk mencari nilai tertinggi, terendah, total, dan jumlah lulus      | O(n)         |
| 4  | Hitung rata-rata     | total / len(data)      | Operasi matematika sederhana                                               | O(1)         |
| 5  | Hitung tidak lulus   | len(data) - lulus      | Operasi sederhana                                                          | O(1)         |
| 6  | Menampilkan hasil    | print()                | Menampilkan output ke layar                                                | O(1)         |
| 7  | Menampilkan grafik   | plt.bar()              | Menampilkan grafik dengan data tetap (tidak tergantung n besar)            | O(1)         |


**Kesimpulan :**
Program memiliki kompleksitas waktu O(n) karena bergantung pada jumlah data yang diinput dan diproses. Sementara itu, operasi lainnya bersifat konstan (O(1)). Secara keseluruhan, program sudah efisien karena hanya menggunakan satu perulangan utama.

# 4. Refleksi Pembelajaran

Dari pembuatan program ini, saya belajar bahwa penggunaan list sangat membantu dalam menyimpan dan mengelola banyak data secara efisien. Selain itu, perulangan mempermudah proses pengolahan data tanpa harus menulis kode berulang secara manual.

Saya juga memahami pentingnya percabangan dalam menentukan kondisi tertentu, seperti mencari nilai tertinggi, terendah, dan menentukan kelulusan. Penggunaan fungsi membuat program lebih terstruktur dan mudah dibaca, sehingga memudahkan dalam pengembangan.

Di sisi lain, validasi input menjadi hal penting untuk memastikan data yang dimasukkan sesuai dengan ketentuan. Visualisasi data dalam bentuk grafik juga membantu dalam memahami hasil dengan lebih jelas.

Kesimpulan:  
Program ini memberikan pemahaman tentang dasar-dasar pemrograman seperti pengolahan data, logika program, dan penyusunan kode yang terstruktur. Dengan demikian, program menjadi lebih efisien, rapi, dan mudah untuk dikembangkan.
 # Dibuat Oleh: I Made Suardhita Kusuma (2501010075) 
   

  
  
