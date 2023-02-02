# customer-segmentation-using-clustering-model

Repository ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Full Time Program khususnya pada Phase 1 dalam konsep clustering. Dalam hal ini akan melakukan segmentasi pelanggan dengan menggunakan model clustering.

## Dataset

Dataset yang digunakan merupakan dataset yang diambil dari Google BigQuery, namun **tidak akan menggunakan `bigquery-public-data`**. Dataset terdapat dari
query berikut ini ```select * from `ftds-hacktiv8-project.phase1_ftds_016_rmt.credit-card-information` where mod(CUST_ID,2) = 0 ```

## Problem Statement

Membuat model clustering untuk melakukan Customer Segmentation dari data kartu kredit sebuah bank berdasarkan informasi penggunaan selama 6 bulan terakhir.

## Objectives

- Mampu memperoleh data menggunakan BigQuery
- Mampu mempersiapkan data untuk digunakan dalam Clustering
- Mampu memahami konsep Clustering dengan menggunakan Scikit-Learn
- Mampu mengimplementasikan Clustering pada data yang diberikan
