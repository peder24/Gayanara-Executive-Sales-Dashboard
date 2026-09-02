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
- Bagaimana perubahan product mix dan brand performance antar tahun?
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

## 4. Kinerja Per Tahun (2022-2024)

### 2022 - Performa Awal

Revenue Rp198,7 juta dengan 389 order dari 308 customer. AOV 2022 sebesar Rp510.938 merupakan yang tertinggi dalam periode 2022–2024.

Distribusi quarterly: Q1 (Rp54.1M, 97 orders), Q2 (Rp43.2M, 94 orders), Q3 (Rp42.3M, 92 orders), Q4 (Rp59.1M, 106 orders). Ada pola U-shape di mana Q1 dan Q4 lebih kuat dari Q2-Q3.

Top brand: Cendana Co (13.18%), Riang Apparel (12.46%), SandangIndo (12.24%), Tropika Style (11.88%).

**Kondisi bisnis:** Pada 2022, jumlah customer dan order masih relatif lebih rendah dibandingkan tahun berikutnya. Revenue juga lebih rendah dibandingkan 2023 dan 2024. Dari sisi quarterly, revenue lebih tinggi pada Q1 dan Q4 dibandingkan Q2 dan Q3.

**Implikasi:** Pertumbuhan sangat bergantung pada akuisisi customer baru.

**Rekomendasi:** Bangun sistem retention sejak awal agar customer 2022 tetap aktif di tahun berikutnya.

### 2023 - Pertumbuhan Tinggi

Lompatan besar ke **Rp427.8 juta** (+115% YoY). Order naik 2.2x (389 ke 871). Ini menandakan adanya intervensi signifikan di 2023, apakah kampanye marketing besar, ekspansi channel, atau onboarding reseller/distributor baru.

Distribusi quarterly: Q1 (Rp115.3M, 216 orders), Q2 (Rp124.4M, 247 orders), Q3 (Rp92.7M, 206 orders), Q4 (Rp95.4M, 202 orders).

Penurunan Q2 ke Q3 di 2023 mencapai **25.5%** - penurunan yang sangat tajam.

NusaBrand muncul sebagai brand dominan (12.85%). Revenue by category mulai menunjukkan dominasi dress (17.58%) dan jacket (17.44%).

**Kondisi bisnis:** Penjualan meningkat cukup tinggi pada 2023, tetapi terjadi penurunan revenue yang cukup besar pada Q3.

**Implikasi:** Pertumbuhan yang cepat bisa menyembunyikan masalah operasional atau ketidakstabilan demand.

**Rekomendasi:** Investigasi penyebab kenaikan revenue yang cukup besar pada 2023 agar faktor yang mendorong pertumbuhan tersebut dapat dipertahankan dan dikembangkan.

### 2024 - Tahun Normalisasi

Revenue **Rp513.2 juta** (+20% YoY), dengan 1,027 order, pertama kali melampaui 1,000 order/tahun. Riang Apparel kembali memimpin brand share (13.45%).

Distribusi quarterly: Q1 (Rp124.4M, 258 orders), Q2 (Rp135.7M, 274 orders), Q3 (Rp123.9M, 234 orders), Q4 (Rp129.3M, 261 orders).

Penurunan Q2 ke Q3 di 2024 hanya **8.7%**, jauh lebih terkendali dibanding 2023.

**Kondisi bisnis:** Revenue masih meningkat pada 2024, tetapi pertumbuhannya lebih lambat dibandingkan 2023. Di sisi lain, distribusi revenue per quarter lebih merata.

**Implikasi:** Pertumbuhan masih berjalan pada 2024, tetapi mulai melambat dibandingkan 2023. Perusahaan perlu mencari cara untuk menjaga pertumbuhan di tahun berikutnya.

**Rekomendasi:** Tetap memperkuat akuisisi customer baru, sekaligus meningkatkan customer retention, repeat purchase, dan nilai transaksi dari customer yang sudah ada. Selain itu, optimasi produk dapat dilakukan untuk mendukung pertumbuhan revenue.

## 5. Performa Brand

### Brand Revenue Share (2024)

| Brand | Revenue | Share |
|---|---|---|
| Riang Apparel | Rp71M | 13.45% |
| NusaBrand | Rp65M | 12.37% |
| Cendana Co | Rp64M | 12.20% |
| SandangIndo | Rp52M | 9.83% |
| Pesona Indo | Rp51M | 9.70% |
| Tropika Style | Rp47M | 9.02% |
| BajuKita | Rp47M | 9.00% |
| Senja Wear | Rp47M | 8.87% |
| Ratu Mode | Rp43M | 8.18% |
| Kanvas Lokal | Rp39M | 7.38% |

### Kondisi Bisnis

Distribusi brand sangat merata. Tidak ada satu brand pun yang mendominasi di atas 15%. Pertumbuhan tidak bergantung pada satu brand saja.

### Implikasi

Risiko bisnis terdiversifikasi — kehilangan satu brand tidak akan collapse revenue. Namun tidak ada anchor brand yang bisa dijadikan differentiator kuat di benak konsumen. Performa brand berubah mengikuti periode dan product mix.

### Rekomendasi

**Riang Apparel** konsisten masuk Top 3 di semua tahun dan berpotensi dijadikan flagship brand dengan investasi lebih besar.

**Kanvas Lokal** (7.38% di 2024) konsisten di posisi bawah. Evaluasi berdasarkan revenue growth, product contribution, consistency, dan breadth of assortment, bukan hanya revenue absolut.

## 6. Performa Kategori Produk

### Revenue by Category

| Kategori | 2022 | 2023 | 2024 |
|---|---|---|---|
| Accessories | Rp33M | Rp73M | **Rp93M** |
| Jacket | Rp37M | Rp77M | Rp91M |
| Dress | Rp36M | Rp77M | Rp82M |
| Kemeja | - | - | Rp56M |
| Kaos | - | - | Rp50M |
| Pants | - | - | Rp49M |
| Celana | - | - | Rp46M |
| Shirt | - | - | Rp32M |
| T-Shirt | - | - | Rp27M |

### Kondisi Bisnis

Jacket, Dress, dan Accessories merupakan kategori utama sepanjang periode. Pada 2024, Accessories menjadi kategori dengan kontribusi terbesar untuk pertama kalinya.

### Implikasi

Terdapat indikasi perubahan product mix menuju kontribusi Accessories yang lebih tinggi. T-Shirt dan Shirt di posisi terbawah mengindikasikan average selling price rendah per item.

### Rekomendasi

Accessories layak dipantau sebagai potential growth category — cenderung memiliki margin lebih tinggi dan basket size lebih fleksibel. Namun peningkatan inventory sebaiknya tetap didasarkan pada performa SKU di dalam kategori, bukan hanya total category revenue.

Pertimbangkan apakah T-Shirt dan Shirt berkontribusi sebagai traffic driver atau justru menjadi beban margin.

## 7. Performa Regional (Provinsi & Kota)

### Top Provinsi by Revenue (2024)

| Provinsi | Revenue |
|---|---|
| **Jawa Barat** | Rp104,065,391 |
| Jawa Timur | Rp47,808,155 |
| Jawa Tengah | Rp35,444,799 |
| Kalimantan Barat | Rp31,640,527 |
| Sumatera Selatan | Rp29,861,034 |
| Sulawesi Utara | Rp29,462,539 |

### Top Kota by Revenue per Tahun

| Tahun | Top Cities |
|---|---|
| 2022 | Tangerang, Makassar, Yogyakarta, Malang, Semarang |
| 2023 | Medan, Makassar, Bekasi, Surabaya, Padang |
| 2024 | Semarang, Depok, Pontianak, Manado, Banjarmasin |

### Kondisi Bisnis

Jawa Barat merupakan market utama yang konsisten. Market leadership antar kota berubah setiap tahun — tidak ada satu kota yang selalu menjadi market terbesar sepanjang periode.

### Implikasi

Gayanara memiliki core market yang kuat sekaligus basis permintaan yang tersebar di berbagai wilayah. Market attractiveness berubah dari tahun ke tahun.

**Anomali penting:** Semarang melompat ke posisi kota #1 di 2024 dari tidak masuk top 5 di 2022. Perlu investigasi faktor pendorongnya.

**Kalimantan Barat (Pontianak) dan Sulawesi Utara (Manado)** masuk top revenue padahal bukan kota tier-1 — indikasi penetrasi pasar yang kuat di luar Jawa.

**DKI Jakarta masuk Bot 5 Provinsi** padahal merupakan pusat ekonomi terbesar Indonesia — sinyal bahwa penetrasi pasar di Jakarta sangat belum optimal.

### Rekomendasi

Protect the core market: pertahankan availability dan customer retention di Jawa Barat.

Diversify the growth: gunakan Revenue Growth by City (bukan hanya Revenue absolut) untuk membedakan emerging market dari market yang hanya besar secara historical.

Aktifkan program regional ambassador atau dropshipper network di Pontianak, Manado, Banjarmasin, Palembang untuk memperkuat penetrasi yang sudah organik terbentuk.

Lakukan targeted campaign untuk Jakarta berbasis geo-targeting.

## 8. Performa Kurir

### Distribusi Order per Kurir

| Kurir | 2022 | 2023 | 2024 |
|---|---|---|---|
| J&T | 30.3% | 29.4% | 28.82% |
| JNE | 29.8% | 27.6% | 28.82% |
| SiCepat | 24.2% | 28.0% | 26.97% |
| Anteraja | 10.0% | 9.8% | 10.03% |
| Pos Indonesia | 5.7% | 5.7% | 5.36% |

### Kondisi Bisnis

J&T, JNE, dan SiCepat konsisten menjadi tiga courier utama setiap tahun dan menangani sekitar 85% order. Struktur delivery relatif stabil dari tahun ke tahun.

### Implikasi

Konsentrasi pada tiga partner menciptakan operational dependency. Dashboard ini hanya menunjukkan volume order sehingga belum cukup untuk menentukan courier terbaik secara kualitas layanan.

### Rekomendasi

Negosiasikan rate lebih baik dengan JNE dan J&T mengingat volume yang signifikan. Monitor SLA, delivery reliability, shipping cost, return rate, cancellation rate, dan customer experience per kurir.

Evaluasi Pos Indonesia yang konsisten di posisi terbawah — pertimbangkan apakah partnership ini masih relevan atau bisa digantikan dengan kurir yang lebih performatif di area tertentu.

## 9. Radar Performa Rendah (Red Zone)

Section "Performa Rendah (Perlu Perhatian)" adalah bagian kritis yang harus dimonitor setiap bulan.

### Bot 5 Produk by Revenue (Agregat All Years)

| Produk | Revenue |
|---|---|
| Kemeja Linen Senja Wear | Rp472,000 |
| Jaket Varsity SandangIndo | Rp595,000 |
| Kaos Raglan Riang Apparel | Rp686,000 |
| Dress A-Line Pesona Indo | Rp693,000 |
| Dompet Kulit Ratu Mode | Rp784,000 |

### Cara Membaca Red Zone

Performa rendah merupakan sinyal untuk investigasi, bukan bukti langsung bahwa produk atau wilayah harus dihentikan. Wilayah dan produk dengan revenue rendah berbeda antar tahun — area yang rendah pada satu tahun tidak otomatis tetap rendah pada tahun berikutnya.

Untuk setiap produk atau wilayah di Red Zone, gunakan pendekatan:

**Current Performance + Historical Trend + Growth**

Produk dengan revenue rendah tetapi growth tinggi memiliki potensi yang berbeda dibandingkan produk dengan revenue besar tetapi terus menurun.

**Kemeja Linen Senja Wear (Rp472K total)** adalah produk dengan performa paling lemah. Jika produk ini sudah berjalan lebih dari 6 bulan dengan angka ini, keputusan discontinue perlu dipertimbangkan serius.

## 10. Temuan Kritis & Rekomendasi Strategis

### Temuan #1: Deceleration Growth yang Signifikan

**Fakta:** +115% (2022 ke 2023), +20% (2023 ke 2024).

**Implikasi:** Jika tren ini berlanjut, pertumbuhan 2025 bisa single-digit. Bisnis harus mengidentifikasi growth lever baru sebelum fase plateau tercapai.

**Rekomendasi:**
- Lakukan analisis cohort retention: apakah pelanggan 2022 dan 2023 masih aktif membeli di 2024?
- Evaluasi customer lifetime value per akuisisi tahun.
- Pertimbangkan ekspansi ke channel baru atau offline pop-up untuk penetrasi Jabodetabek.

### Temuan #2: AOV Stagnan

**Fakta:** AOV 2022: Rp510K, 2023: Rp491K, 2024: Rp499K. Flat, bahkan sedikit turun.

**Implikasi:** Customer tidak membeli lebih banyak atau lebih mahal per transaksi. Semua revenue growth berasal dari volume customer baru, bukan peningkatan spending per customer.

**Rekomendasi:**
- Implementasi bundle product (misalnya: kemeja + celana dengan diskon 10%).
- Aktifkan minimum purchase threshold untuk free ongkir agar mendorong AOV naik.
- Riset apakah ada price ceiling di segmen target — apakah produk Rp700K-1M bisa terjual.
- Prioritaskan cross-selling dan personalized promotion untuk customer existing.

### Temuan #3: Jakarta Underperforming

**Fakta:** DKI Jakarta masuk Bot 5 Provinsi padahal merupakan pasar terbesar Indonesia.

**Implikasi:** Kompetisi di Jakarta sangat ketat, atau produk GAYANARA belum mendapat awareness yang cukup.

**Rekomendasi:**
- Investigasi kehadiran kompetitor kuat di Jakarta yang menekan share.
- Targeted campaign berbasis Instagram/TikTok ads dengan geo-targeting Jakarta.
- Evaluasi kurir mana yang paling cepat dan kompetitif untuk pengiriman dalam Jakarta.

### Temuan #4: Akuisisi Pelanggan Baru Melambat

**Fakta:** Unique Customers: 308 ke 527 (+219) ke 579 (+52). Penurunan drastis di pertambahan customer baru 2024.

**Implikasi:** Saluran akuisisi yang ada mulai jenuh atau cost per acquisition meningkat.

**Rekomendasi:**
- Analisis sumber akuisisi customer baru: organic, paid, referral, atau reseller?
- Program referral/affiliate yang terstruktur untuk memanfaatkan basis customer yang ada.
- Eksplorasi B2B channel: apakah ada peluang penjualan ke corporate atau reseller?

### Temuan #5: Mid-Year Slump Tidak Termitigasi

**Fakta:** Setiap tahun terjadi penurunan revenue di Jun-Jul.

**Rekomendasi:**
- Desain mid-year campaign khusus sebagai event brand tahunan.
- Persiapkan pre-order atau product launch baru di bulan Jun-Jul.
- Maksimalkan momen Harbolnas 7.7 yang jatuh di periode ini.

### Peluang #1: Ekspansi Kota Tier-2 di Luar Jawa

**Fakta:** Pontianak, Manado, Banjarmasin, Palembang masuk Top 10 kota, mengalahkan kota-kota besar Jawa.

**Rekomendasi:** Aktifkan program regional ambassador atau dropshipper network di kota-kota ini.

### Peluang #2: Accessories sebagai Growth Category

**Fakta:** Accessories naik ke posisi #1 revenue kategori di 2024 (Rp93M).

**Rekomendasi:** Perluas portofolio accessories dan cross-sell dengan kategori apparel yang sudah kuat.

## 11. Metric Considerations

### Total Revenue

KPI utama menggunakan `total_amount_idr` pada level order.

### Revenue by Brand / Category

Visual Brand dan Category menggunakan `subtotal_idr` pada level item. Karena discount berada pada level order, `subtotal_idr` tidak secara langsung menunjukkan net revenue setelah discount dialokasikan ke masing-masing brand atau category.

Untuk menghindari interpretasi yang keliru, visual tersebut lebih tepat menggunakan istilah **Gross Sales by Brand** dan **Gross Sales by Category**, bukan Net Revenue by Brand/Category.

### Transaction Status

KPI dan analisis penjualan menggunakan transaksi valid dan tidak memasukkan status cancelled dan returned. Status tersebut tetap dapat dianalisis secara terpisah untuk cancellation rate dan return rate.

## 12. Data Model

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

## 13. Catatan Metodologi

- Data yang digunakan adalah valid orders, tidak termasuk cancelled dan returned.
- Revenue dikalkulasi dari nilai transaksi aktual per order.
- Unique Customers dihitung per tahun, bukan lifetime unique — seorang pelanggan yang membeli di 2022 dan 2023 dihitung di keduanya.
- Perbandingan YoY menggunakan data penuh per tahun fiskal.
- Angka "Total" di ringkasan adalah agregat semua tahun (2022 + 2023 + 2024).
- Bottom 5 digunakan sebagai alat diagnosis, bukan dasar keputusan langsung.

### Overall Business Condition

Gayanara mengalami pertumbuhan sangat kuat pada 2023 dan tetap tumbuh pada 2024, tetapi laju pertumbuhannya mulai moderat. Revenue dan orders tumbuh lebih cepat daripada unique customers pada 2024, sehingga customer existing menjadi semakin penting. Q3 merupakan periode yang relatif lemah, tetapi penurunan Q3 pada 2024 jauh lebih terkendali dibandingkan 2023. Product leadership berubah antar tahun. Jacket, Dress, dan Accessories menjadi core categories dengan Accessories sebagai kategori terbesar pada 2024. Jawa Barat menjadi core market yang konsisten, tetapi market leadership antar kota berubah dari tahun ke tahun. J&T, JNE, dan SiCepat menangani mayoritas order secara konsisten.

### Priority Business Recommendations

| Priority | Focus | Business Reason |
|---|---|---|
| 1 | Customer Retention | Customer tumbuh lebih lambat daripada revenue dan orders pada 2024 |
| 2 | Q3 Investigation | Q3 menjadi titik lemah yang muncul berulang |
| 3 | Product Trend | Top product berubah antar tahun |
| 4 | Accessories | Menjadi kategori terbesar pada 2024 |
| 5 | Core Market | Jawa Barat tetap menjadi market terbesar |
| 6 | Emerging Market | Top city berubah antar tahun |
| 7 | Courier Management | Tiga courier menangani sekitar 85% order |

*Dokumen ini dibuat berdasarkan data yang ditampilkan pada Executive Sales Dashboard GAYANARA, periode 2022-2024.*
*Untuk pertanyaan analitik lebih lanjut atau permintaan drill-down data, hubungi tim Data & Analytics.*

**Dibuat oleh:** Data & Analytics Team
**Last Updated:** 2024
