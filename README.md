# Klustering C-MET Menggunakan Algoritma K-Prototype

## Kelompok 9 RA
### Muhammad Fathir Fadillah, Raditia Riandi, Salwa Amelia Salsabila, Frisca Sihotang, Lulu Christin Sihombing

---

## Pendahuluan

Klustering merupakan metode dalam analisis data yang bertujuan untuk mengelompokkan objek-objek ke dalam kelompok (cluster) berdasarkan karakteristik yang dimilikinya. Dalam hal ini, **C-MET** adalah salah satu pendekatan yang digunakan untuk mengelompokkan data yang memiliki atribut campuran, yaitu data numerik dan kategorikal. Algoritma yang digunakan adalah **K-Prototype**, yang merupakan pengembangan dari algoritma K-Means untuk menangani data campuran tersebut.

---

## Apa itu C-MET?
C-MET adalah singkatan dari **Clustering Mixed-Etype Data**. Metode ini dirancang untuk:
- Mengelompokkan data yang memiliki kombinasi atribut numerik dan kategorikal.
- Mempermudah analisis data yang kompleks, seperti data demografi, survei, atau data pasar.

Dalam penerapannya, algoritma K-Prototype sangat relevan untuk C-MET karena memiliki kemampuan untuk menangani dua jenis atribut tersebut dengan bobot yang fleksibel.

---

## Algoritma K-Prototype
**K-Prototype** adalah algoritma klustering yang menggabungkan konsep K-Means untuk data numerik dan K-Modes untuk data kategorikal. Keunggulan algoritma ini meliputi:

1. **Fleksibilitas Bobot:**
   - Memberikan bobot yang fleksibel untuk atribut kategorikal, sehingga memengaruhi hasil klustering secara signifikan.

2. **Efisiensi:**
   - Dapat bekerja dengan data berskala besar dengan atribut campuran.

3. **Aplikasi Luas:**
   - Cocok untuk berbagai kasus analisis data seperti segmentasi pasar, data kesehatan, dan lain-lain.

### Tahapan Algoritma K-Prototype:
1. Inisialisasi centroid awal untuk cluster.
2. Perhitungan jarak:
   - **Numerik:** Menggunakan jarak Euclidean.
   - **Kategorikal:** Menggunakan perhitungan mismatch (perbedaan kategori).
3. Penyesuaian centroid hingga mencapai konvergensi.

---

## Alur Penelitian
![Alur Penelitian Menggunakan K-Prototype Clustering](https://github.com/fadillah180403/Bioinformatika9RA/blob/main/Flowchart.png)

---

## Kesimpulan
Metode klustering dengan algoritma K-Prototype sangat berguna untuk menangani data campuran, seperti yang terdapat dalam metode C-MET. Dengan kemampuan untuk menyesuaikan bobot atribut, algoritma ini memberikan hasil yang lebih akurat dan relevan dalam pengelompokan data.
---
