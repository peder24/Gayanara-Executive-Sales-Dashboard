# GAYANARA - Executive Sales Dashboard
### Data Coverage: 2022-2024

![Executive Sales Dashboard](https://res.cloudinary.com/dk2tex4to/image/upload/v1787539761/Screenshot_2026-08-24_094838_rhq48b.png) 

> **Catatan penting:** Seluruh KPI dan analisis **tidak termasuk** order berstatus *cancelled* dan *returned*.

## Daftar Isi

1. [Overview](#1-overview)
2. [Business Objective](#2-business-objective)
3. [Ringkasan Eksekutif](#3-ringkasan-eksekutif)
4. [Kinerja Per Tahun (2022-2024)](#4-kinerja-per-tahun-2022-2024)
5. [Tren Revenue & Pola Musiman](#5-tren-revenue--pola-musiman)
6. [Performa Brand](#6-performa-brand)
7. [Performa Kategori Produk](#7-performa-kategori-produk)
8. [Performa Regional (Provinsi & Kota)](#8-performa-regional-provinsi--kota)
9. [Performa Kurir](#9-performa-kurir)
10. [Radar Performa Rendah (Red Zone)](#10-radar-performa-rendah-red-zone)
11. [Temuan Kritis & Rekomendasi Strategis](#11-temuan-kritis--rekomendasi-strategis)
12. [Pertanyaan Bisnis yang Perlu Dijawab Selanjutnya](#12-pertanyaan-bisnis-yang-perlu-dijawab-selanjutnya)
13. [Metric Considerations](#13-metric-considerations)
14. [Data Model](#14-data-model)
15. [Catatan Metodologi](#15-catatan-metodologi)

## 1. Overview

Executive Sales Dashboard adalah dashboard interaktif berbasis Power BI untuk mengevaluasi performa penjualan Gayanara dari sisi revenue, order, customer, produk, brand, kategori, wilayah, dan courier.

Dashboard menyediakan filter: Year, Quarter, Month, Province, City, Brand.

Analisis utama menggunakan transaksi valid dengan mengecualikan order berstatus cancelled dan returned.

## 2. Business Objective

Dashboard ini dibuat untuk menjawab:

- Bagaimana perkembangan revenue dari 2022 hingga 2024?
- Bagaimana performa revenue dan orders pada setiap quarter?
- Apakah pertumbuhan revenue didorong oleh pertambahan customer atau peningkatan aktivitas transaksi?
- Produk dan kategori apa yang menjadi driver utama penjualan?
- Bagaimana perubahan performa brand dan kategori produk antar tahun?
- Wilayah mana yang menjadi core market?
- Kota dan provinsi mana yang menunjukkan peluang maupun performa rendah?
- Seberapa besar ketergantungan bisnis terhadap courier tertentu?

## 3. Ringkasan Eksekutif

| Metrik | 2022 | 2023 | 2024 | Total |
|---|---|---|---|---|
| **Revenue** | Rp198,754,942 | Rp427,857,597 | Rp513,236,412 | **Rp1,139,848,951** |
| **Total Orders** | 389 | 871 | 1,027 | **2,287** |
| **Total Units Sold** | 839 | 1,842 | 2,232 | **4,913** |
| **Avg Order Value** | Rp510,938 | Rp491,226 | Rp499,743 | Rp498,404 |
| **Unique Customers** | 308 | 527 | 579 | **757** |

### KPI Interpretation

Seluruh KPI utama tumbuh konsisten dari 2022 hingga 2024. Pada periode 2023 ke 2024, pertumbuhannya sebagai berikut:

| KPI | Perubahan |
|---|---|
| Revenue | +20.0% |
| Orders | +17.9% |
| Units Sold | +21.2% |
| Unique Customers | +9.9% |
| AOV | +1.7% |

Pertumbuhan revenue dan orders yang lebih tinggi dibandingkan pertumbuhan jumlah pelanggan mengindikasikan bahwa aktivitas transaksi dari pelanggan yang sudah ada kemungkinan semakin berperan dalam mendorong pertumbuhan bisnis


### Headline Insight

- Revenue meningkat 115% dari 2022 ke 2023, menunjukkan pertumbuhan yang cukup besar.
- Revenue masih tumbuh 20% dari 2023 ke 2024, tetapi pertumbuhannya lebih lambat dibandingkan tahun sebelumnya.
- **AOV relatif stagnan** di kisaran Rp490-511 ribu. Pertumbuhan revenue sepenuhnya didorong oleh volume order, bukan kenaikan nilai transaksi per pelanggan.
- Unique customers meningkat dari 308 pada 2022 menjadi 527 pada 2023 dan 579 pada 2024. Pertambahan unique customers turun dari 219 pada 2023 menjadi 52 pada 2024. Di sisi lain, revenue masih meningkat 20% pada 2024 dibandingkan 2023. Hal ini mengindikasikan bahwa peningkatan revenue pada 2024 kemungkinan semakin didukung oleh aktivitas transaksi dari pelanggan yang sudah ada.

## 4. Performa Brand

### Brand Revenue Share

| Brand         |               2022 |               2023 |               2024 |
| ------------- | -----------------: | -----------------: | -----------------: |
| Riang Apparel |     Rp25M (12.46%) |     Rp50M (11.36%) | **Rp71M (13.45%)** |
| NusaBrand     |      Rp19M (9.56%) | **Rp56M (12.85%)** |     Rp65M (12.37%) |
| Cendana Co    | **Rp27M (13.18%)** |     Rp44M (10.01%) |     Rp64M (12.20%) |
| SandangIndo   |     Rp25M (12.24%) |      Rp44M (9.92%) |      Rp52M (9.83%) |
| Pesona Indo   |      Rp18M (8.65%) |      Rp33M (7.48%) |      Rp51M (9.70%) |
| Tropika Style |     Rp24M (11.88%) |     Rp50M (11.40%) |      Rp47M (9.02%) |
| BajuKita      |      Rp17M (8.47%) |      Rp44M (9.96%) |      Rp47M (9.00%) |
| Senja Wear    |      Rp18M (8.89%) |     Rp45M (10.33%) |      Rp47M (8.87%) |
| Ratu Mode     |      Rp15M (7.25%) |      Rp33M (7.15%) |      Rp43M (8.18%) |
| Kanvas Lokal  |      Rp15M (7.41%) |      Rp42M (9.53%) |      Rp39M (7.38%) |

### Kondisi Bisnis

**Performa brand mengalami perubahan posisi antar tahun, meskipun distribusi revenue tetap relatif tersebar.** Pada 2022, Cendana Co memiliki revenue terbesar sebesar Rp27M (13.18%). Pada 2023, posisi teratas bergeser ke NusaBrand dengan Rp56M (12.85%), kemudian pada 2024 Riang Apparel menjadi brand dengan revenue terbesar sebesar Rp71M (13.45%).

Secara keseluruhan, **seluruh brand mengalami peningkatan revenue dari 2022 ke 2024**, kecuali Tropika Style dan Kanvas Lokal yang mengalami penurunan dari 2023 ke 2024. Riang Apparel mencatat peningkatan terbesar secara nominal dari **Rp25M menjadi Rp71M**, sementara NusaBrand meningkat dari Rp19M menjadi Rp65M.

### Implikasi

**Pertumbuhan revenue tidak hanya berasal dari satu brand**, karena beberapa brand juga mengalami peningkatan revenue yang signifikan sepanjang 2022–2024. Namun, **posisi brand teratas berubah setiap periode**, dari Cendana Co (2022), NusaBrand (2023), menjadi Riang Apparel (2024).

Hal ini menunjukkan bahwa **performa brand bersifat dinamis**, sehingga evaluasi sebaiknya tidak hanya melihat brand dengan revenue terbesar pada satu tahun, tetapi juga melihat **tren pertumbuhan dan perubahan kontribusi revenue antar tahun**.

### Rekomendasi
Prioritaskan evaluasi dan pengembangan brand dengan tren pertumbuhan revenue yang kuat, terutama Riang Apparel dan NusaBrand. Riang Apparel meningkat dari Rp25M pada 2022 menjadi Rp71M pada 2024 dan menjadi brand dengan revenue tertinggi pada 2024, sedangkan NusaBrand meningkat dari Rp19M menjadi Rp65M.

Evaluasi penurunan revenue pada Tropika Style dan Kanvas Lokal, yang masing-masing turun dari Rp50M menjadi Rp47M dan Rp42M menjadi Rp39M pada 2023–2024. Analisis lebih lanjut dapat diarahkan pada produk, kategori, dan periode penjualan untuk mengetahui faktor yang berkaitan dengan penurunan tersebut.

Pantau tren revenue dan kontribusi seluruh brand secara berkala, karena posisi brand teratas berubah setiap tahun.

## 5. Performa Kategori Produk

### Top 10 Product by Revenue

| Rank | 2022                            | Revenue | 2023                            |  Revenue | 2024                          | Revenue |
| ---: | ------------------------------- | ------: | ------------------------------- | -------: | ----------------------------- | ------: |
|    1 | T-Shirt Graphic SandangIndo     | Rp4,64M | T-Shirt Graphic BajuKita        | Rp11,17M | Tas Selempang Riang Apparel   | Rp9,18M |
|    2 | Kaos Striped Riang Apparel      | Rp4,25M | Kaos Striped Kanvas Lokal       |  Rp9,24M | Celana Jeans Slim SandangIndo | Rp9,11M |
|    3 | Tshirt Slim Fit Tropika Style   | Rp4,20M | Dress Mini Casual SandangIndo   |  Rp8,88M | Kemeja Oxford NusaBrand       | Rp8,02M |
|    4 | Dress Bodycon Pesona Indo       | Rp4,19M | Dompet Kulit Pesona Indo        |  Rp7,37M | Dress Wrap Pesona Indo        | Rp7,79M |
|    5 | Ikat Pinggang Kulit SandangIndo | Rp3,99M | T-Shirt Graphic SandangIndo     |  Rp7,21M | Celana Cargo NusaBrand        | Rp7,43M |
|    6 | Dress Midi Floral Riang Apparel | Rp3,31M | Celana Jeans Slim Riang Apparel |  Rp7,12M | Kaos Oversize BajuKita        | Rp7,41M |
|    7 | Celana Jogger SandangIndo       | Rp3,29M | Dress Bodycon Senja Wear        |  Rp6,86M | Jaket Parasut Riang Apparel   | Rp7,14M |
|    8 | Hoodie Cendana Co               | Rp3,00M | Celana Jogger Tropika Style     |  Rp6,59M | Kemeja Batik NusaBrand        | Rp7,08M |
|    9 | Jacket Denim Riang Apparel      | Rp2,99M | Jacket Denim Tropika Style      |  Rp6,38M | Shirt Slim Fit Cendana Co     | Rp6,91M |
|   10 | Dress Mini Casual SandangIndo   | Rp2,84M | Celana Kulot Tropika Style      |  Rp6,34M | Celana Jogger SandangIndo     | Rp6,81M |

### Kondisi Bisnis

Komposisi Top 10 juga berubah antar periode. Hanya beberapa produk yang kembali muncul pada tahun berbeda, seperti T-Shirt Graphic SandangIndo, Dress Mini Casual SandangIndo, dan Celana Jogger SandangIndo. Sementara itu, sebagian besar produk Top 10 berbeda dari satu tahun ke tahun berikutnya.

Selain perubahan komposisi, nilai revenue Top 10 meningkat dari sekitar Rp36,7M pada 2022 menjadi Rp77,1M pada 2023 dan Rp76,9M pada 2024. Ini menunjukkan bahwa produk-produk yang masuk kelompok Top 10 memberikan kontribusi revenue yang jauh lebih besar pada 2023–2024 dibandingkan 2022.

### Implikasi

Performa produk tidak bersifat tetap dari tahun ke tahun. Karena produk unggulan dan komposisi Top 10 berubah, evaluasi produk sebaiknya tidak hanya melihat produk dengan revenue terbesar dalam satu tahun, tetapi juga melihat pola perubahan dan konsistensi performanya antarperiode.

Produk yang berulang kali muncul di Top 10 dapat dipandang sebagai produk yang perlu mendapat perhatian lebih lanjut karena menunjukkan performa yang relatif konsisten dalam periode yang dianalisis.

### Rekomendasi

* **Evaluasi produk dengan revenue tertinggi** pada setiap tahun.
* Evaluasi perubahan produk Top 10 antar tahun untuk mengidentifikasi produk yang mengalami peningkatan, penurunan, atau kehilangan posisi.
* **Pantau tren revenue produk secara berkala** untuk melihat perubahan performa dan menentukan keputusan bisnis.

Betul. Kalau **Kondisi Bisnis** dan **Implikasi** ingin benar-benar berbasis data, kita harus menghindari asumsi seperti *“Accessories memiliki margin lebih tinggi”* atau *“T-Shirt menjadi traffic driver”*, karena data yang kamu tampilkan **tidak menyediakan margin, quantity, atau traffic** untuk membuktikan itu.

Selain itu, tabelmu juga perlu diperbaiki: **semua kategori sebenarnya sudah ada sejak 2022**, bukan baru muncul pada 2024. Dari gambar, totalnya sekitar Rp203M (2022), Rp439M (2023), dan Rp526M (2024).

Saya akan susun ulang seperti ini.

---

## Revenue by Category

| Kategori        |      2022 |      2023 |      2024 |
| --------------- | --------: | --------: | --------: |
| **Accessories** |     Rp33M |     Rp73M | **Rp93M** |
| **Jacket**      | **Rp37M** | **Rp77M** |     Rp91M |
| **Dress**       |     Rp36M | **Rp77M** |     Rp82M |
| Kemeja          |     Rp25M |     Rp44M |     Rp56M |
| Kaos            |     Rp21M |     Rp52M |     Rp50M |
| Pants           |     Rp16M |     Rp34M |     Rp49M |
| Celana          |     Rp13M |     Rp38M |     Rp46M |
| Shirt           |      Rp9M |     Rp16M |     Rp32M |
| T-Shirt         |      Rp8M |     Rp16M |     Rp27M |

### Kondisi Bisnis

**Jacket, Dress, dan Accessories merupakan tiga kategori dengan kontribusi revenue terbesar sepanjang 2022–2024.** Pada 2022, Jacket menjadi kategori dengan revenue tertinggi sebesar Rp37M, sedangkan pada 2023 Jacket dan Dress sama-sama mencapai Rp77M. Pada 2024, Accessories menjadi kategori dengan revenue tertinggi sebesar **Rp93M**, diikuti Jacket Rp91M dan Dress Rp82M.

Secara keseluruhan, **seluruh kategori mengalami peningkatan revenue dari 2022 ke 2024**. Namun, pertumbuhan antar kategori berbeda. 

### Implikasi

Kontribusi revenue semakin besar pada beberapa kategori utama, terutama Accessories, Jacket, dan Dress. Pada 2024, Accessories mengambil posisi sebagai kategori dengan revenue terbesar, menunjukkan bahwa kontribusi kategori tersebut semakin penting terhadap total penjualan.

Di sisi lain, Shirt dan T-Shirt berada pada kelompok dengan revenue terendah pada 2024, masing-masing sebesar Rp32M dan Rp27M. Namun, keduanya tetap mengalami peningkatan revenue dibandingkan 2022. Artinya, revenue yang relatif rendah belum menunjukkan bahwa kategori tersebut mengalami masalah, sehingga tidak tepat langsung menyarankan pengurangan kategori hanya berdasarkan revenue.

---

### Rekomendasi

1. **Pertahankan dan evaluasi lebih lanjut tiga kategori utama - Accessories, Jacket, dan Dress**, karena secara konsisten memberikan kontribusi terbesar terhadap revenue.

2. Pantau kategori dengan revenue lebih rendah seperti Shirt dan T-Shirt, tetapi jangan langsung mengurangi atau menghentikannya karena revenue keduanya tetap mengalami pertumbuhan. Analisis lebih lanjut dapat dilakukan pada jumlah units sold, jumlah produk yang berkontribusi, dan perkembangan revenue masing-masing produk untuk mengetahui apakah pertumbuhannya berasal dari beberapa produk tertentu atau tersebar di dalam kategori.

---

# 6. Performa Regional (Province & City)

## A. Top 10 Province by Revenue

| Rank | 2022               | Revenue | 2023             | Revenue | 2024               |  Revenue |
| ---: | ------------------ | ------: | ---------------- | ------: | ------------------ | -------: |
|    1 | **Jawa Barat**     | Rp38,5M | **Jawa Barat**   | Rp88,3M | **Jawa Barat**     | Rp104,1M |
|    2 | Jawa Timur         | Rp23,6M | Jawa Timur       | Rp40,5M | Jawa Timur         |  Rp47,8M |
|    3 | Banten             | Rp15,3M | Sumatera Utara   | Rp30,0M | Jawa Tengah        |  Rp35,4M |
|    4 | Sulawesi Selatan   | Rp13,1M | Sulawesi Selatan | Rp25,3M | Kalimantan Barat   |  Rp31,6M |
|    5 | DI Yogyakarta      | Rp12,5M | Sumatera Barat   | Rp23,7M | Sumatera Selatan   |  Rp29,9M |
|    6 | Jawa Tengah        | Rp12,2M | DKI Jakarta      | Rp23,2M | Sulawesi Utara     |  Rp29,5M |
|    7 | Bali               | Rp11,6M | Riau             | Rp23,1M | Kalimantan Selatan |  Rp28,0M |
|    8 | Kalimantan Timur   | Rp11,2M | Banten           | Rp22,6M | Sumatera Utara     |  Rp28,0M |
|    9 | Sumatera Utara     | Rp10,4M | Kalimantan Timur | Rp22,5M | Kalimantan Timur   |  Rp27,1M |
|   10 | Kalimantan Selatan |  Rp9,7M | Sulawesi Utara   | Rp22,5M | Sumatera Barat     |  Rp25,8M |

### Penjelasan

Pada level provinsi, **Jawa Barat menjadi kontributor revenue terbesar secara konsisten selama 2022–2024**. Revenue Jawa Barat meningkat dari sekitar **Rp38,5M pada 2022 menjadi Rp88,3M pada 2023 dan Rp104,1M pada 2024**.

**Jawa Timur juga konsisten berada di posisi kedua** selama tiga tahun, dengan revenue meningkat dari Rp23,6M menjadi Rp40,5M dan kemudian Rp47,8M.

Sementara itu, posisi setelah dua provinsi tersebut mengalami perubahan. Misalnya, **Banten berada di posisi ketiga pada 2022**, tetapi turun ke posisi kedelapan pada 2023 dan tidak lagi masuk lima besar pada 2024. Sebaliknya, **Jawa Tengah berada di posisi keenam pada 2022 dan naik ke posisi ketiga pada 2024**.

Artinya, terdapat **perubahan kontribusi revenue antarprovinsi**, meskipun Jawa Barat dan Jawa Timur tetap menjadi dua provinsi dengan posisi teratas.

---

## B. Top 10 City by Revenue

| Rank | 2022          | Revenue | 2023       | Revenue | 2024         | Revenue |
| ---: | ------------- | ------: | ---------- | ------: | ------------ | ------: |
|    1 | **Tangerang** | Rp25,2M | **Medan**  | Rp30,0M | **Semarang** | Rp35,4M |
|    2 | Makassar      | Rp13,1M | Makassar   | Rp25,3M | Depok        | Rp31,8M |
|    3 | Yogyakarta    | Rp12,5M | Bekasi     | Rp24,6M | Pontianak    | Rp31,6M |
|    4 | Malang        | Rp12,2M | Surabaya   | Rp23,9M | Palembang    | Rp29,9M |
|    5 | Semarang      | Rp12,2M | Padang     | Rp23,7M | Manado       | Rp29,5M |
|    6 | Denpasar      | Rp11,6M | Jakarta    | Rp23,2M | Banjarmasin  | Rp28,0M |
|    7 | Surabaya      | Rp11,3M | Pekanbaru  | Rp23,1M | Medan        | Rp28,0M |
|    8 | Balikpapan    | Rp11,2M | Depok      | Rp22,8M | Bekasi       | Rp27,6M |
|    9 | Bandung       | Rp11,0M | Tangerang  | Rp22,6M | Balikpapan   | Rp27,1M |
|   10 | Medan         | Rp10,4M | Balikpapan | Rp22,5M | Padang       | Rp25,8M |

### Penjelasan

Berbeda dengan provinsi, **tidak ada satu kota yang secara konsisten menjadi kontributor revenue terbesar selama tiga tahun**.

Kota dengan revenue tertinggi berubah dari:

* **2022 → Tangerang: Rp25,2M**
* **2023 → Medan: Rp30,0M**
* **2024 → Semarang: Rp35,4M**

Selain perubahan posisi teratas, komposisi Top 10 juga berubah. **Makassar dan Balikpapan**, misalnya, muncul dalam Top 10 selama tiga tahun, sedangkan beberapa kota lainnya hanya muncul pada tahun tertentu.

Pada 2024, **Semarang, Depok, dan Pontianak** menjadi tiga kota dengan revenue terbesar. Hal ini menunjukkan bahwa kontribusi revenue pada level kota mengalami perubahan dari tahun ke tahun.

---

# Kondisi Bisnis

### Province

**Jawa Barat menunjukkan posisi yang paling konsisten**, karena menjadi provinsi dengan revenue tertinggi pada 2022, 2023, dan 2024. Jawa Timur juga mempertahankan posisi kedua selama periode tersebut.

Namun, **peringkat provinsi lainnya mengalami perubahan**. Jawa Tengah, misalnya, meningkat dari posisi keenam pada 2022 menjadi posisi ketiga pada 2024. Sebaliknya, Banten mengalami penurunan posisi dari peringkat ketiga pada 2022 menjadi peringkat kedelapan pada 2023.

### City

Pada level kota, **peringkat revenue lebih dinamis dibandingkan provinsi**. Kota dengan revenue tertinggi berubah setiap tahun, yaitu Tangerang pada 2022, Medan pada 2023, dan Semarang pada 2024.

Dengan demikian, **kontribusi revenue di level provinsi lebih konsisten pada wilayah teratas, sedangkan kontribusi di level kota mengalami perubahan yang lebih besar.**

---

# Implikasi

1. **Jawa Barat merupakan wilayah yang paling konsisten memberikan kontribusi revenue**, sehingga perubahan performa di provinsi ini dapat memberikan dampak yang signifikan terhadap total revenue.

2. **Perubahan ranking provinsi menunjukkan bahwa kontribusi antarwilayah tidak sepenuhnya tetap.** Beberapa provinsi mengalami peningkatan posisi, sementara yang lain mengalami penurunan.

3. **Perubahan posisi Top 10 city menunjukkan bahwa performa kota perlu dilihat secara periodik**, karena kota dengan revenue tertinggi dapat berubah dari satu tahun ke tahun berikutnya.

---

# Rekomendasi

1. Pertahankan penjualan di Jawa Barat dan Jawa Timur karena keduanya konsisten menjadi penyumbang revenue terbesar selama 2022–2024.
2. Analisis pertumbuhan revenue per provinsi dan kota untuk mengetahui wilayah yang mengalami peningkatan penjualan paling besar.
3. Pantau perubahan posisi kota setiap tahun, terutama kota yang mengalami peningkatan signifikan seperti Semarang pada 2024.
4. Evaluasi wilayah yang mengalami penurunan atau perubahan posisi dengan membandingkan perkembangan revenue dari tahun ke tahun sebelum menentukan tindakan selanjutnya.

# 7. Performa Kurir

### Distribusi Order per Kurir

| Kurir             |         2022 |         2023 |         2024 |
| ----------------- | -----------: | -----------: | -----------: |
| **J&T**           | 118 (30,33%) | 256 (29,39%) | 296 (28,82%) |
| **JNE**           | 116 (29,82%) | 240 (27,55%) | 296 (28,82%) |
| **SiCepat**       |  94 (24,16%) | 244 (28,01%) | 277 (26,97%) |
| **Anteraja**      |  39 (10,03%) |   85 (9,76%) | 103 (10,03%) |
| **Pos Indonesia** |   22 (5,66%) |   46 (5,28%) |   55 (5,36%) |
| **Total Orders**  |      **389** |      **871** |    **1.027** |

### Kondisi Bisnis

J&T, JNE, dan SiCepat menjadi **tiga kurir dengan jumlah order terbesar selama 2022–2024**. Gabungan ketiganya menangani sekitar **84%–85% dari total order setiap tahun**.

Pada 2022, J&T menjadi kurir dengan order terbanyak sebanyak **118 order (30,33%)**, sedikit di atas JNE sebanyak 116 order (29,82%). Pada 2023, J&T tetap berada di posisi pertama dengan 256 order (29,39%), sementara SiCepat meningkat menjadi 244 order (28,01%). Pada 2024, **J&T dan JNE sama-sama menangani 296 order (28,82%)**.

Anteraja memiliki kontribusi sekitar **10%** setiap tahun, sedangkan Pos Indonesia berada di sekitar **5%** dari total order.

### Implikasi

**Distribusi order berdasarkan kurir relatif stabil selama 2022–2024.** Tiga kurir utama secara konsisten menangani sebagian besar order, sementara Anteraja dan Pos Indonesia memiliki porsi yang lebih kecil.

Perubahan terbesar terlihat pada **komposisi tiga kurir utama**. Porsi J&T sedikit menurun dari 30,33% pada 2022 menjadi 28,82% pada 2024, sedangkan SiCepat meningkat dari 24,16% menjadi 26,97%. Pada 2024, J&T dan JNE memiliki jumlah serta persentase order yang sama.

Dengan demikian, dari data ini kita dapat melihat **pola penggunaan kurir**, tetapi belum dapat menentukan kurir mana yang memiliki layanan terbaik karena tidak terdapat data seperti waktu pengiriman, biaya pengiriman, atau tingkat keterlambatan.

### Rekomendasi

1. **Pertahankan pemantauan terhadap J&T, JNE, dan SiCepat** karena ketiganya menangani sebagian besar order Gayanara.

2. **Pantau perubahan distribusi order antar kurir**, terutama perkembangan SiCepat yang porsi ordernya meningkat dibandingkan 2022.

3. **Evaluasi kurir berdasarkan metrik layanan tambahan** sebelum mengambil keputusan terkait pemilihan atau pengurangan penggunaan kurir. Metrik yang dapat ditambahkan antara lain waktu pengiriman, biaya pengiriman, keterlambatan, cancellation, dan return rate.

4. **Pertahankan Anteraja dan Pos Indonesia sebagai bagian dari evaluasi distribusi kurir**, tetapi keputusan mengenai perubahan penggunaan keduanya sebaiknya tidak hanya didasarkan pada jumlah order.

---

Betul. Bagian **Red Zone** sebelumnya terlalu jauh karena langsung mengarah ke keputusan seperti *discontinue*, padahal visual yang kamu punya hanya menunjukkan **revenue terendah pada masing-masing tahun**. Kita harus membaca tabel itu sebagai **indikator untuk diperhatikan**, bukan bukti bahwa produk atau wilayah bermasalah.

Karena gambar yang kamu kirim adalah **2022, 2023, dan 2024**, analisisnya justru bisa dibuat lebih kuat dengan melihat **apakah posisi rendah tersebut terus berulang atau berubah**.

# 8. Radar Performa Rendah (Perlu Perhatian)

Bagian ini digunakan untuk melihat **produk, provinsi, dan kota dengan revenue terendah pada masing-masing tahun** sebagai dasar untuk menentukan area yang perlu dianalisis lebih lanjut.

## 2022

### Top 5 Produk dengan Revenue Terendah

| Rank | Produk                         | Revenue |
| ---: | ------------------------------ | ------: |
|    1 | Kaos Raglan Riang Apparel      |   Rp49K |
|    2 | Jaket Varsity Kanvas Lokal     |   Rp69K |
|    3 | Dompet Kulit SandangIndo       |   Rp79K |
|    4 | Dompet Kulit Ratu Mode         |   Rp98K |
|    5 | Dress Mini Casual Kanvas Lokal |   Rp98K |

### Top 5 Province dengan Revenue Terendah

| Rank | Province         | Revenue |
| ---: | ---------------- | ------: |
|    1 | DKI Jakarta      |  Rp5,1M |
|    2 | Sumatera Barat   |  Rp6,6M |
|    3 | Kalimantan Barat |  Rp7,1M |
|    4 | Sumatera Selatan |  Rp7,1M |
|    5 | Riau             |  Rp8,3M |

### Top 5 City dengan Revenue Terendah

| Rank | City      | Revenue |
| ---: | --------- | ------: |
|    1 | Jakarta   |  Rp5,1M |
|    2 | Bogor     |  Rp5,6M |
|    3 | Padang    |  Rp6,6M |
|    4 | Pontianak |  Rp7,1M |
|    5 | Palembang |  Rp7,1M |

---

## 2023

### Top 5 Produk dengan Revenue Terendah

| Rank | Produk                       | Revenue |
| ---: | ---------------------------- | ------: |
|    1 | Jaket Denim Kanvas Lokal     |   Rp59K |
|    2 | Jaket Varsity SandangIndo    |  Rp119K |
|    3 | Pants Wide Leg Tropika Style |  Rp129K |
|    4 | Kaos Oversize Ratu Mode      |  Rp158K |
|    5 | Kemeja Linen Senja Wear      |  Rp177K |

### Top 5 Province dengan Revenue Terendah

| Rank | Province           | Revenue |
| ---: | ------------------ | ------: |
|    1 | Bali               | Rp14,2M |
|    2 | DI Yogyakarta      | Rp15,9M |
|    3 | Sumatera Selatan   | Rp17,1M |
|    4 | Kalimantan Selatan | Rp19,7M |
|    5 | Kalimantan Barat   | Rp19,7M |

### Top 5 City dengan Revenue Terendah

| Rank | City          | Revenue |
| ---: | ------------- | ------: |
|    1 | Denpasar      | Rp14,2M |
|    2 | Yogyakarta    | Rp15,9M |
|    3 | Palembang     | Rp16,7M |
|    4 | **Pekanbaru** | Rp17,1M |
|    5 | Bogor         | Rp19,5M |

---

## 2024

### Top 5 Produk dengan Revenue Terendah

| Rank | Produk                       | Revenue |
| ---: | ---------------------------- | ------: |
|    1 | Dress Maxi Polos Pesona Indo |  Rp118K |
|    2 | T-Shirt Graphic Cendana Co   |  Rp119K |
|    3 | Dress Wrap BajuKita          |  Rp147K |
|    4 | Kemeja Linen Senja Wear      |  Rp177K |
|    5 | Dress A-Line Pesona Indo     |  Rp198K |

### Top 5 Province dengan Revenue Terendah

| Rank | Province         | Revenue |
| ---: | ---------------- | ------: |
|    1 | Bali             | Rp17,8M |
|    2 | DI Yogyakarta    | Rp19,5M |
|    3 | Riau             | Rp20,1M |
|    4 | DKI Jakarta      | Rp20,2M |
|    5 | Sulawesi Selatan | Rp22,7M |

### Top 5 City dengan Revenue Terendah

| Rank | City       | Revenue |
| ---: | ---------- | ------: |
|    1 | Denpasar   | Rp17,8M |
|    2 | Yogyakarta | Rp19,5M |
|    3 | Pekanbaru  | Rp20,1M |
|    4 | Jakarta    | Rp20,2M |
|    5 | Bogor      | Rp20,4M |

---

# Kondisi Bisnis

**Produk, provinsi, dan kota yang berada pada kelompok revenue terendah berubah dari tahun ke tahun.** Pada sisi produk, tidak ada daftar produk yang sama secara keseluruhan pada 2022–2024.

Namun, terdapat beberapa produk yang muncul kembali. **Kemeja Linen Senja Wear**, misalnya, masuk Top 5 revenue terendah pada 2023 dan tetap berada di posisi tersebut pada 2024 dengan revenue **Rp177K pada kedua tahun**.

Pada sisi wilayah, terdapat beberapa pola yang berulang. **Bali dan DI Yogyakarta** masuk lima provinsi dengan revenue terendah pada 2023 dan 2024. **DKI Jakarta** berada di lima terbawah pada 2022 dan kembali muncul pada 2024.

Pada level kota, **Denpasar dan Yogyakarta** muncul dalam lima terbawah pada 2023 dan 2024, sedangkan **Jakarta dan Bogor** muncul pada 2022 maupun 2024.

---

# Implikasi

1. **Performa rendah tidak selalu bersifat tetap.** Perubahan daftar Top 5 dari tahun ke tahun menunjukkan bahwa produk dan wilayah dengan revenue rendah pada satu tahun tidak selalu tetap berada di posisi tersebut pada tahun berikutnya.

2. **Beberapa area menunjukkan pola yang lebih konsisten.** Kemeja Linen Senja Wear tetap berada di kelompok revenue terendah pada 2023 dan 2024 dengan nilai Rp177K. Hal serupa terlihat pada Bali dan DI Yogyakarta di level provinsi serta Denpasar dan Yogyakarta di level kota yang kembali muncul pada kelompok terbawah pada 2024.

3. **Karena itu, revenue saja belum cukup untuk mengambil keputusan menghentikan produk atau mengurangi aktivitas di suatu wilayah.** Yang lebih penting adalah melihat apakah revenue rendah tersebut hanya terjadi pada satu tahun atau berlangsung dalam beberapa periode.

---

# Rekomendasi

1. **Pantau produk dan wilayah yang berulang kali masuk kelompok revenue terendah**, karena kondisi tersebut lebih perlu diperhatikan dibandingkan yang hanya muncul satu kali.

2. **Lakukan analisis perkembangan revenue dari tahun ke tahun** pada produk dan wilayah yang berulang di kelompok terbawah untuk melihat apakah kondisinya membaik, tetap, atau menurun.

3. **Untuk produk yang konsisten memiliki revenue rendah, lakukan pengecekan pada jumlah unit terjual dan produk terkait** sebelum menentukan tindakan lebih lanjut.

4. **Untuk wilayah yang berulang di kelompok terbawah, bandingkan perkembangan revenue antar tahun** sebelum menentukan apakah perlu dilakukan evaluasi atau strategi khusus.

---

## 9. Metric Considerations

### Total Revenue

KPI utama menggunakan `total_amount_idr` pada level order.

### Revenue by Brand / Category

Visual Brand dan Category menggunakan `subtotal_idr` pada level item. Karena discount berada pada level order, `subtotal_idr` tidak secara langsung menunjukkan net revenue setelah discount dialokasikan ke masing-masing brand atau category.

Untuk menghindari interpretasi yang keliru, visual tersebut lebih tepat menggunakan istilah **Gross Sales by Brand** dan **Gross Sales by Category**, bukan Net Revenue by Brand/Category.

### Transaction Status

KPI dan analisis penjualan menggunakan transaksi valid dan tidak memasukkan status cancelled dan returned. Status tersebut tetap dapat dianalisis secara terpisah untuk cancellation rate dan return rate.

## 10. Data Model

Project menggunakan lima tabel dengan relasi sebagai berikut:

```
customers
   |
   | customer_id
   v
orders
   |
   | order_id
   v
order_items
   |
   | product_id
   v
products

reviews --> orders (order_id)
reviews --> products (product_id)
```

### Dashboard Components

**KPI:** Revenue, Total Orders, Total Units Sold, Average Order Value, Unique Customers

**Sales Performance:** Revenue Trend, Revenue & Total Orders per Quarter, Perbandingan YoY Total Revenue

**Product & Brand:** Top 10 Product by Revenue, Revenue by Brand, Revenue by Category, Bottom 5 Product by Revenue

**Geography:** Top 10 Province by Revenue, Top 10 City by Revenue, Bottom 5 Province by Revenue, Bottom 5 City by Revenue

**Operations:** Courier Performance

**Interactive Filters:** Year, Quarter, Month, Province, City, Brand

### Tools & Skills

Power BI Desktop, DAX, SQL, Data Modeling, KPI Development, Business Analysis, Data Visualization, Time-Series Analysis, Top-N / Bottom-N Analysis, Geographic Analysis

## 11. Catatan 

- Data yang digunakan adalah valid orders, tidak termasuk cancelled dan returned.
- Revenue dikalkulasi dari nilai transaksi aktual per order.
- Unique Customers dihitung per tahun, bukan lifetime unique — seorang pelanggan yang membeli di 2022 dan 2023 dihitung di keduanya.
- Perbandingan YoY menggunakan data penuh per tahun fiskal.
- Angka "Total" di ringkasan adalah agregat semua tahun (2022 + 2023 + 2024).
- Bottom 5 digunakan sebagai alat diagnosis, bukan dasar keputusan langsung.

### Overall Business Condition

Gayanara mengalami pertumbuhan sangat kuat pada 2023 dan tetap tumbuh pada 2024, tetapi laju pertumbuhannya mulai moderat. Revenue dan orders tumbuh lebih cepat daripada unique customers pada 2024, sehingga customer existing menjadi semakin penting. Q3 merupakan periode yang relatif lemah, tetapi penurunan Q3 pada 2024 jauh lebih terkendali dibandingkan 2023. Product leadership berubah antar tahun. Jacket, Dress, dan Accessories menjadi core categories dengan Accessories sebagai kategori terbesar pada 2024. Jawa Barat menjadi core market yang konsisten, tetapi market leadership antar kota berubah dari tahun ke tahun. J&T, JNE, dan SiCepat menangani mayoritas order secara konsisten.


*Dokumen ini dibuat berdasarkan data yang ditampilkan pada Executive Sales Dashboard GAYANARA, periode 2022-2024.*
