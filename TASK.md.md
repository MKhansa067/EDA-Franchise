# **Tugas Exploratory Data Analysis (EDA) & Data Storytelling**

## **Analisis Data Penjualan BBM PT. P**

### **📌 Konfigurasi Path Kode & Dataset Pada Google Collab**

```
BASE_PATH = '/content/drive/MyDrive/Colab_Notebooks/Sains_Data/Tugas_Mandiri_2'
DATASET_PATH = os.path.join(BASE_PATH, 'Dataset', 'data_franchise.csv')

```

📝 Deskripsi Tugas

Berdasarkan data penjualan BBM pada setiap wilayah perusahaan PT. P, lakukan **Exploratory Data Analysis (EDA)** menggunakan bahasa pemrograman **Python**.

Sajikan hasil eksplorasi dalam bentuk visualisasi data yang informatif, kemudian susun **data storytelling** dalam bentuk slide presentasi (*presentation deck*) untuk menyampaikan temuan, *insight*, dan rekomendasi yang relevan bagi pemilik usaha.

### **📋 Instruksi Tugas**

1. **Analisis Revenue Pulau Jawa–Bali**  
   1. Hitung rata-rata *revenue* pada bulan Januari untuk wilayah Pulau Jawa–Bali.  
   2. Sajikan hasilnya dalam bentuk visualisasi yang sesuai.  
2. **Analisis Pertumbuhan Revenue Provinsi**  
   1. Identifikasi 10 provinsi dengan pertumbuhan *revenue* tertinggi sepanjang tahun 2021\.  
   2. Tampilkan hasil analisis dalam bentuk visualisasi yang informatif dan mudah dipahami.  
3. **Analisis Kolom Class**  
   1. Eksplorasi faktor-faktor yang berkaitan dengan pemberian label pada kolom class.  
   2. Gunakan karakteristik data yang tersedia untuk mendukung analisis dan jelaskan temuan Anda berdasarkan hasil eksplorasi.  
4. **Temuan Utama EDA**  
   1. Identifikasi dan jelaskan temuan-temuan penting lainnya dari hasil eksplorasi data.  
   2. Sertakan visualisasi yang relevan untuk mendukung setiap temuan.  
5. **Insight dan Rekomendasi Bisnis**  
   1. Berdasarkan hasil eksplorasi, rumuskan *insight* dan rekomendasi yang dapat dipertimbangkan oleh pemilik usaha untuk meningkatkan *revenue*.

### **⚙️ Ketentuan Pengerjaan**

* Gunakan **Python** untuk melakukan eksplorasi dan analisis data.  
* Gunakan **visualisasi yang sesuai** dengan jenis data dan tujuan analisis.  
* Susun hasil analisis dalam bentuk **presentation deck** dengan pendekatan *data storytelling*.  
* Pastikan setiap visualisasi memiliki **judul, label sumbu, dan keterangan** yang diperlukan.  
* Dukung setiap kesimpulan dengan **hasil analisis atau visualisasi** yang relevan.  
* Bedakan **temuan berbasis data** dengan **dugaan/rekomendasi** yang memerlukan validasi lebih lanjut.

### **📊 Sumber Data & Keterangan Kolom**

**Sumber Data:** Data Franchise – Google Sheets

| Kolom | Deskripsi |
| :---- | :---- |
| id | Identitas unik (*unique key*) setiap franchise |
| month\_period | Periode bulan pencatatan data |
| revenue | Total pendapatan (*revenue*) dalam satu bulan |
| revenue\_avg | Rata-rata *revenue* per hari dalam satu bulan |
| Province | Provinsi lokasi franchise |
| regional | Wilayah regional franchise |
| class | Kategori franchise |

konteks nyata setiap kolom dari dataset:&nbsp;

id=sst0ss0s, sst1ss1s, dan seterusnya;&nbsp;

month\_period=2021-01-01, 2021-01-02, dan seterusnya;

revenue=17012788.37, 16703720.12 dan seterusnya(acak);

revenue\_avg=5.965.614.328.571.420, 5.487.996.248.387.090, dan seterusnya;

max\_avg=6.989.333.667.741.930, 6.989.333.667.741.930, dan seterusnya;

revenue\_loss=15.013.374.193.548.300, 10.237.193.391.705.000, dan seterusnya;

loss\_perc=21.480.408.444.141.100, 1.464.688.034.419.220, dan seterusnya;

province=Nangroe Aceh Darussalam(dari Regional 1 di kolom ‘regional’, sama halnya dengan Regional bernomor lainnya dan seterusnya), Sumatera Utara(Regional 1), Sumatera Barat(Regional 1), Sumatera Selatan(Regional 1), Riau(Regional 1), Kepulauan Riau(Regional 1), Lampung(Regional 1), Sumatera Selatan(Regional 1), Jambi(Regional 1), DKI Jakarta(Regional 2), Banten(Regional 2), Jawa Barat(Regional 3), Jawa Tengah(Regional 4), DI Yogyakarta(Regional 4), Jawa Timur(Regional 5), Bali(Regional 5), Nusa Tenggara Barat(Regional 5), Nusa Tenggara Timur(Regional 5), Bali(Regional 5), Kalimantan Selatan(Regional 6), Kalimantan Tengah(Regional 6), Kalimantan Timur(Regional 6), Kalimantan Barat(Regional 6), Sulawesi Selatan(Regional 7), Sulawesi Utara(Regional 7), Gorontalo(Regional 7), Maluku(Regional 7), Sulawesi Barat(Regional 7);

regional=Regional 1, Regional 2, Regional 3, Regional 4, Regional 5, Regional 6, Regional 7;

class=no\_class, silver, gold.

📤 Output Akhir

1. **Notebook Python (.ipynb)** berisi proses EDA dan visualisasi data.  
2. **Presentation Deck** yang merangkum temuan utama, *insight*, serta rekomendasi bisnis berdasarkan hasil analisis.

Kamu adalah seorang Data Analyst, Data Scientist, dan Data Engineer yang telah bekerja selama 10 tahun, dan seorang senior di perusahaan besar. Dari konteks, metode step by step untuk EDA ini di .ipynb apa saja?