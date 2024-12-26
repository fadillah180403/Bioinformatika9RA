# Klustering C-MET Menggunakan Algoritma K-Prototype

## Kelompok 9 RA
### 1. Muhammad Fathir Fadillah 121450098
### 2. Raditia Riandi 
### 3. Salwa Amelia Salsabila 
### 4. Frisca Sihotang 
### 5. Lulu Christin Sihombing

---

## Pendahuluan

C-MET atau MET proto-oncogene adalah gen yang mengkode protein reseptor tirosin kinase yang dikenal sebagai hepatocyte growth factor receptor (HGFR). Protein ini berperan penting dalam berbagai proses biologis, seperti proliferasi sel, motilitas sel, dan angiogenesis, serta memiliki implikasi besar dalam perkembangan kanker. Penelitian terkait C-MET bertujuan untuk memahami peranannya dalam kanker dan mengelompokkan ekspresi gen atau mutasi yang terkait dengan C-MET.

Dalam konteks ini, **algoritma K-Prototype** dapat digunakan untuk klustering data ekspresi gen atau mutasi C-MET, yang sering kali memiliki atribut campuran, yaitu data numerik (seperti tingkat ekspresi) dan kategorikal (seperti status mutasi).

---

## Apa itu C-MET?
C-MET adalah singkatan dari **MET proto-oncogene**, gen yang berperan sebagai reseptor tirosin kinase. Reseptor ini diaktifkan oleh hepatocyte growth factor (HGF), yang memicu berbagai jalur sinyal intraseluler untuk:
- Mendukung proliferasi dan migrasi sel.
- Meningkatkan angiogenesis.
- Membantu penyembuhan luka.
- Berperan dalam proses metastasis pada kanker.

Dalam penelitian, klustering data terkait C-MET penting untuk mengidentifikasi pola dalam ekspresi gen atau variasi mutasi yang dapat membantu memahami mekanisme penyakit dan pengembangan terapi.

---

## Algoritma K-Prototype
**K-Prototype** adalah algoritma klustering yang menggabungkan konsep K-Means untuk data numerik dan K-Modes untuk data kategorikal. Keunggulan algoritma ini meliputi:

1. **Fleksibilitas Bobot:**
   - Memberikan bobot yang fleksibel untuk atribut kategorikal, sehingga memengaruhi hasil klustering secara signifikan.

2. **Efisiensi:**
   - Dapat bekerja dengan data berskala besar dengan atribut campuran.

3. **Aplikasi Luas:**
   - Cocok untuk analisis data seperti ekspresi gen, mutasi gen, atau data biologis lainnya.

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
Penelitian tentang C-MET dengan algoritma K-Prototype memberikan pendekatan yang kuat untuk mengelompokkan data ekspresi gen atau mutasi yang terkait dengan MET proto-oncogene. Dengan kemampuan untuk menangani atribut campuran, algoritma ini membantu mengidentifikasi pola data yang relevan, yang dapat mendukung pengembangan terapi berbasis molekuler dan pemahaman mendalam tentang mekanisme kanker.

---
## Lebih Lengkap Silakan Kunjungi
1. File "KlusteringC-MET.Rmd" tidak dapat dilihat langsung outputnya.
2. Saat menjalankan file "KlusteringC-MET.Rmd" harus melakukan instalasi library ChemminerR dan ChemmineOB melaui BiocManager (#BiocManager::install("ChemmineR") dan
#BiocManager::install("ChemmineOB")).
3. Di sini kami menggunakan perintah "sample()" oleh karena itu, sampel tiap kluster bisa saja berbeda untuk setiap kali run. Digunakan "set.seed()" untuk mencegahnya.
4. Untuk output file "KlusteringC-MET.Rmd" dapat dilihat melalui tautan berikut.
https://drive.google.com/drive/folders/1EITRoyXf-OL-a_qIm9pFcbHOwzpOS1GY?usp=sharing
5. Berikut kami lampirkan tautan video YouTube
https://youtu.be/2vJpYevNmQ0
6. Berikut Kami lampirkan Posternya https://github.com/fadillah180403/Bioinformatika9RA/blob/main/Poster%20Kelompok%209.png
---
