# Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma
## About Company
Kimia Farma merupakan perusahaan farmasi pertama di Indonesia yang didirikan oleh Pemerintah Hindia Belanda pada tahun 1817. Awalnya, perusahaan ini bernama NV Chemicalien Handle Rathkamp & Co. Setelah Indonesia merdeka, pemerintah menerapkan kebijakan nasionalisasi terhadap perusahaan-perusahaan Belanda, termasuk di sektor farmasi. Pada tahun 1958, beberapa perusahaan farmasi dilebur menjadi Perusahaan Negara Farmasi (PNF) Bhinneka Kimia Farma. Kemudian, pada 16 Agustus 1971, status hukum PNF berubah menjadi Perseroan Terbatas (PT), sehingga namanya diubah menjadi PT Kimia Farma (Persero). Dalam sektor ritel farmasi, perusahaan ini mengelola apotek, klinik kesehatan, dan laboratorium diagnostik di seluruh Indonesia. Sebagai industri farmasi, PT Kimia Farma memproduksi berbagai produk yang dikategorikan ke dalam empat jenis, yaitu obat generik, OTC & herbal, obat etikal, dan kosmetik.
## Latar Belakang
Sebagai salah satu BUMN farmasi terbesar di Indonesia, Kimia Farma memiliki ambisi untuk terus berkembang dan meningkatkan layanan kesehatan bagi masyarakat. Namun, di tengah persaingan yang semakin ketat dan perubahan dinamika bisnis yang cepat, perusahaan perlu melakukan evaluasi kinerja secara menyeluruh. Di sinilah peran Big Data Analytics menjadi krusial. Dengan jumlah data yang besar dari transaksi, inventaris, cabang, dan produk, Kimia Farma sebenarnya memiliki sumber informasi yang sangat berharga tetapi belum dimanfaatkan secara optimal. Melalui analisis data yang mendalam, perusahaan dapat memperoleh wawasan penting untuk menjawab berbagai pertanyaan strategis terkait kinerja bisnisnya.
## Sumber Data
 1. kf_final_transaction.csv
 2. kf_inventory.csv
 3. kf_kantor_cabang.csv
 4. kf_product.csv
## Problem Statement
 1. Menyajikan gambaran komprehensif meengenai kinerja Kimia Farma dalam rentang 2020 - 2023
 2. Mengidentifikasi aspek yang memerlukan perbaikan guna mengoptimalkan kinerja perusahaan.
 3. Membantu dalam mengambil keputusan strategis untuk meningkatkan pendapatan dan total transaksi di masa depan
 4. Menyajikan informasi mengenai cabang-cabang yang perlu ditingkatkan guna meningkatkan kepuasan pelanggan.
## Step Pengerjaan Final Task
### Import Dataset ke BigQuery
1. Buka BigQuery kemudian create new project dengan nama Rakamin_KF_Analytics
2. Download dataset yang telah disediakan.
3. Create dataset pada project Rakamin_KF_Analytics dengan nama kimia-farma.
4. Import dataset yang telah didownload dengan cara klik icon titik tiga pada bagian kanan kemudian create table, pada bagian source pilih upload kemudian browse dan select file dengan nama  kf_final_transaction.csv, kf_inventory.csv, kf_kantor_cabang.csv, dan kf_product.csv jika sudah lalu klik create table. Seperti pada gambar berikut
![alt text](https://github.com/AbazK/Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma/blob/b57809a282783f7ead4c647fb32cf6fc2a99a313/Final%20Task/Screenshot%202025-03-24%20120350.png?raw=true)
6. Tampilan setelah berhasil import dataset
![alt text](https://github.com/AbazK/Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma/blob/b57809a282783f7ead4c647fb32cf6fc2a99a313/Final%20Task/Screenshot%202025-03-24%20120402.png?raw=true)

### Membuat tabel analisa
1. Berikut merupakan tabel analisa dengan menggunakan BigQuery
![alt text](https://github.com/AbazK/Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma/blob/main/Screenshot%202025-03-24%20133934.png?raw=true)
![alt text](https://github.com/AbazK/Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma/blob/main/Screenshot%202025-03-24%20133959.png?raw=true)

### Membuat Query Syntax
1. Berikut merupaakan Query tabg digunakan untuk membuat tabel analisa
![alt text](https://github.com/AbazK/Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma/blob/main/Screenshot%202025-03-24%20153432.png?raw=true)
![alt text](https://github.com/AbazK/Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma/blob/main/Screenshot%202025-03-24%20153444.png?raw=true)

### Membuat Dashboard Performance Dengan Google Looker Studio
Berikut merupakan dashboard performance yang dibuat dengan google looker studio
![alt text](https://github.com/AbazK/Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma/blob/main/Screenshot%202025-03-24%20154437.png?raw=true)
