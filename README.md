1. DESKRIPSI PROGRAM
    Program ini dibuat untuk mengelola nilai mahasiswa menggunakan struktur data array (list pada Python). Program ini dapat melakukan input data, mencari nilai tertinggi dan terendah, menghitung rata-rata, serta menentukan jumlah mahasiswa yang lulus. Selain itu, program juga menampilkan grafik untuk visualisasi data.
2. PENJELASAN KONSEP ARRAY
   Array adalah struktur data yang digunakan untuk menyimpan banyak nilai dalam satu variabel dengan tipe data yang sama. Dalam Python, array direpresentasikan menggunakan list.

Pada program ini, array digunakan untuk menyimpan nilai mahasiswa yang diinput oleh user. Data nilai disimpan dalam variabel nilai yang berbentuk list.

Contoh implementasi dalam kode:
```python
nilai = []
for i in range(10):
    n = float(input("Masukkan nilai: "))
    nilai.append(n)
