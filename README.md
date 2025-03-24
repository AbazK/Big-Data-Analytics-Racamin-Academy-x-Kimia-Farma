# Big-Data-Analytics-Racamin-Academy-x-Kimia-Farma
## About Company
Kimia Farma adalah perusahaan industri farmasi pertama di Indonesia yang didirikan oleh Pemerintah Hindia Belanda tahun 1817. Nama perusahaan ini pada awalnya adalah NV Chemicalien Handle Rathkamp & Co. Berdasarkan kebijaksanaan nasionalisasi atas eks perusahaan Belanda di masa awal kemerdekaan, pada tahun 1958, Pemerintah Republik Indonesia melakukan peleburan sejumlah perusahaan farmasi menjadi PNF (Perusahaan Negara Farmasi) Bhinneka Kimia Farma. Kemudian pada tanggal 16 Agustus 1971, bentuk badan hukum PNF diubah menjadi Perseroan Terbatas, sehingga nama perusahaan berubah menjadi PT Kimia Farma (Persero). Kegiatan PT Kimia Farma di bidang ritel farmasi meliputi apotek, klinik kesehatan, dan laboratorium diagnostik yang tersebar di seluruh Indonesia. Sebagai perusahaan industri farmasi, PT Kimia Farma tentu saja memproduksi produk farmasi yang dapat dibedakan dalam empat kategori, yakni generik, OTC & herbal, etikal, dan kosmetik.
## Latar Belakang
Kimia Farma, sebagai salah satu BUMN farmasi terbesar di Indonesia, tentunya memiliki ambisi untuk terus bertumbuh dan meningkatkan pelayanan kesehatan masyarakat. Namun, di era persaingan yang ketat dan landscape bisnis yang dinamis, Kimia Farma perlu terus mengevaluasi kinerjanya secara komprehensif. Disinilah peran Big Data Analytics menjadi penting.  Dengan volume data transaksi, inventaris, cabang, dan produk yang besar, Kimia Farma memiliki harta karun informasi berharga yang belum sepenuhnya tergali. Analisis data yang mendalam dapat membantu Kimia Farma menjawab berbagai pertanyaan krusial terkait kinerja bisnis mereka.
## Sumber Data
 1. kf_final_transaction.csv
 2. kf_inventory.csv
 3. kf_kantor_cabang.csv
 4. kf_product.csv
## Problem Statement
 1. Memberikan gambaran menyeluruh tentang kinerja Kimia Farma selama periode 2020-2023
 2. Membantu para pemangku kepentingan dalam memahami tren dan pola kinerja perusahaan
 3. Mengidentifikasi area yang perlu dioptimalkan untuk meningkatkan kinerja perusahaan
 4. Membantu dalam mengambil keputusan strategis untuk meningkatkan pendapatan dan total transaksi di masa depan
 5. Memberikan informasi tentang cabang-cabang yang perlu dioptimalkan untuk meningkatkan customer satisfaction
## Step Pengerjaan Final Task
### Import Dataset ke BigQuery
1. Buka BigQuery kemudian create new project dengan nama Rakamin_KF_Analytics
2. Download dataset yang telah disediakan.
3. Create dataset pada project Rakamin_KF_Analytics dengan nama kimia-farma.
4. Import dataset yang telah didownload dengan cara klik icon titik tiga pada bagian kanan kemudian create table, pada bagian source pilih upload kemudian browse dan select file dengan nama  kf_final_transaction.csv, kf_inventory.csv, kf_kantor_cabang.csv, dan kf_product.csv jika sudah lalu klik create table.
5. Setelah dataset berhasil di import selanjutnya cek apakah dataset yang di import sudah tersedia pada dataset kimia_farma.
