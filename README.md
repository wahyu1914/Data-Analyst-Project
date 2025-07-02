# Data Analisis Penjualan Rumah di Amerika Serikat

## Deskripsi Dataset:
Dataset ini merupakan kumpulan data sintetis yang berisi 3.000 listing properti residensial. Data ini dimodelkan menyerupai data penjualan rumah sungguhan di A.S. (dalam format ala Zillow) dan dirancang khusus untuk analisis real estat, machine learning, visualisasi data, serta praktik web scraping.

Setiap baris merepresentasikan properti unik dan mencakup 16 fitur utama yang umum digunakan oleh agen real estat, investor, dan analis. Data ini mencakup berbagai negara bagian dan kota di A.S., dengan nilai-nilai realistis untuk harga, luas area, jumlah kamar tidur/mandi, tipe properti, dan banyak lagi.

## Sumber Data:
Dataset ini diperoleh dari platform Kaggle. Dataset dapat ditemukan pada link berikut: 

https://www.kaggle.com/datasets/abdulwadood11220/usa-house-sales-data 

## Kolom Data:
Dataset ini memiliki kolom-kolom berikut, yang memberikan detail tentang setiap properti:

* **Price**: Harga penjualan properti. 

* **Address**: Alamat lengkap properti. 

 **City**: Kota lokasi properti. 

* **Zipcode**: Kode pos properti. 

* **State**: Negara bagian lokasi properti (misal: CA, NY, TX, dll.). 

* **Bedrooms**: Jumlah kamar tidur di properti (format "X bds", perlu diekstrak angka). 

* **Bathrooms**: Jumlah kamar mandi di properti (format "X ba", perlu diekstrak angka). 

* **Area (Sqft)**: Luas area dalam kaki persegi (sqft) (format "X sqft", perlu diekstrak angka). 


* **Lot Size**: Ukuran luas tanah dalam kaki persegi (sqft) (format "X sqft", perlu diekstrak angka). 


* **Year Built**: Tahun pembangunan properti. 


* **Days on Market**: Jumlah hari properti berada di pasar. 


* **Property Type**: Jenis properti (misal: Townhouse, Apartment, Single Family, Multi-Family, Condo). 


* **MLS ID**: ID Multiple Listing Service properti. 


* **Listing Agent**: Nama agen properti yang listing properti tersebut. 


* **Status**: Status penjualan properti (misal: For Sale, Sold, Pending). 


* **Listing URL**: Tautan URL ke listing properti

## Tujuan dan Penggunaan Potensial:
Dataset ini dapat dimanfaatkan untuk berbagai tujuan analisis, antara lain:

* **Eksplorasi Data Analisis (EDA)**: Untuk memahami distribusi dan hubungan antar variabel serta mendapatkan insight awal pasar real estat AS.

* **Pelatihan Model Regresi/Klasifikasi**: Membangun model machine learning untuk memprediksi harga rumah atau mengklasifikasikan tipe properti.

* **Rekayasa Fitur dan Pra-pemrosesan**: Latihan membersihkan, mengubah, dan membuat fitur baru dari data mentah.

* **Dashboard Real Estat dan Mockup Aplikasi Web**: Membuat visualisasi interaktif atau prototipe aplikasi.

* **Latihan dengan Pustaka Data**: Berlatih menggunakan alat seperti BeautifulSoup, Pandas, atau Power BI untuk memanipulasi dan menganalisis data.