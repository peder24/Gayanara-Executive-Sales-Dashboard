# Executive Sales Dashboard - Gayanara

![Executive Sales Dashboard]([https://res.cloudinary.com/dk2tex4to/image/upload/v1787499083/Screenshot_2026-08-23_223049_mqmaau.png](https://res.cloudinary.com/dk2tex4to/image/upload/v1787539761/Screenshot_2026-08-24_094838_rhq48b.png))

## Overview

**Executive Sales Dashboard** adalah dashboard interaktif berbasis **Power BI** untuk mengevaluasi performa penjualan Gayanara dari sisi revenue, order, customer, produk, brand, kategori, wilayah, dan courier.

Dashboard menyediakan filter:

- Year
- Quarter
- Month
- Province
- City
- Brand

Analisis utama menggunakan transaksi valid dengan mengecualikan order berstatus `cancelled` dan `returned`.

---

## Business Objective

Dashboard ini dibuat untuk menjawab:

- Bagaimana perkembangan revenue dari 2022 hingga 2024?
- Bagaimana performa revenue dan orders pada setiap quarter?
- Apakah pertumbuhan revenue didorong oleh pertambahan customer atau peningkatan aktivitas transaksi?
- Produk dan kategori apa yang menjadi driver utama penjualan?
- Bagaimana perubahan product mix dan brand performance antar tahun?
- Wilayah mana yang menjadi core market?
- Kota dan provinsi mana yang menunjukkan peluang maupun performa rendah?
- Seberapa besar ketergantungan bisnis terhadap courier tertentu?

---

# KPI Summary

| KPI | All Year | 2022 | 2023 | 2024 |
|---|---:|---:|---:|---:|
| **Revenue** | Rp1.139.848.951 | Rp198.754.942 | Rp427.857.597 | Rp513.236.412 |
| **Total Orders** | 2.287 | 389 | 871 | 1.027 |
| **Total Units Sold** | 4.913 | 839 | 1.842 | 2.232 |
| **Average Order Value** | Rp498.404 | Rp510.938 | Rp491.226 | Rp499.743 |
| **Unique Customers** | 757 | 308 | 527 | 579 |

### KPI Interpretation

Dari 2022 hingga 2024, seluruh KPI utama menunjukkan peningkatan pada skala bisnis. Pada 2024 dibandingkan 2023:

- Revenue naik sekitar **20,0%**
- Orders naik sekitar **17,9%**
- Units Sold naik sekitar **21,2%**
- Unique Customers naik sekitar **9,9%**
- AOV naik sekitar **1,7%**

Pertumbuhan revenue dan order yang lebih cepat daripada pertumbuhan customer menunjukkan bahwa customer existing semakin penting terhadap pertumbuhan bisnis.

Rasio agregat orders per customer juga meningkat:

- 2022: sekitar **1,26**
- 2023: sekitar **1,65**
- 2024: sekitar **1,77**

Rasio tersebut bukan repeat purchase rate formal, tetapi dapat digunakan sebagai indikasi awal bahwa aktivitas transaksi per customer meningkat.

---

# Business Insights

## 1. Gayanara mengalami ekspansi sangat kuat pada 2023, lalu memasuki pertumbuhan yang lebih moderat pada 2024

Revenue meningkat dari:

- **Rp198,75 juta pada 2022**
- **Rp427,86 juta pada 2023**
- **Rp513,24 juta pada 2024**

Pertumbuhan 2023 terhadap 2022 mencapai sekitar **115%**, sedangkan pertumbuhan 2024 terhadap 2023 sekitar **20%**.

### Kondisi bisnis

Gayanara terus mengalami pertumbuhan dan 2024 menjadi tahun dengan revenue tertinggi. Namun, laju pertumbuhan sudah tidak seagresif 2023.

### Implikasi

Bisnis terlihat berpindah dari fase ekspansi yang sangat cepat menuju fase pertumbuhan yang lebih moderat.

### Rekomendasi

Strategi pertumbuhan sebaiknya mulai bergeser dari hanya mengejar acquisition dan volume menuju:

- customer retention,
- repeat purchase,
- peningkatan nilai customer,
- optimasi produk,
- dan ekspansi pada market yang sudah menunjukkan traction.

---

## 2. Pertumbuhan 2024 lebih banyak ditopang oleh peningkatan aktivitas transaksi daripada pertambahan customer

Perubahan 2023 ke 2024:

| KPI | Perubahan |
|---|---:|
| Revenue | +20,0% |
| Orders | +17,9% |
| Units Sold | +21,2% |
| Unique Customers | +9,9% |
| AOV | +1,7% |

### Kondisi bisnis

Customer bertambah sekitar 10%, tetapi order bertambah hampir 18% dan revenue bertambah 20%.

AOV relatif stabil, sehingga peningkatan revenue lebih banyak berjalan seiring dengan peningkatan volume transaksi dan unit terjual.

### Implikasi

Customer yang sudah ada semakin penting dalam menghasilkan revenue.

### Rekomendasi

Prioritaskan:

- customer retention,
- repeat purchase,
- cross-selling,
- bundling,
- personalized promotion.

Untuk tahap analisis berikutnya, hitung **repeat purchase rate** dan **cohort retention** agar kontribusi customer existing dapat diukur secara formal.

---

## 3. Q3 menjadi titik pelemahan yang konsisten, tetapi stabilitas bisnis membaik pada 2024

### 2022

| Quarter | Revenue | Orders |
|---|---:|---:|
| Q1 | Rp54,16 juta | 97 |
| Q2 | Rp43,24 juta | 94 |
| Q3 | Rp42,25 juta | 92 |
| Q4 | Rp59,10 juta | 106 |

### 2023

| Quarter | Revenue | Orders |
|---|---:|---:|
| Q1 | Rp115,34 juta | 216 |
| Q2 | Rp124,44 juta | 247 |
| Q3 | Rp92,72 juta | 206 |
| Q4 | Rp95,37 juta | 202 |

### 2024

| Quarter | Revenue | Orders |
|---|---:|---:|
| Q1 | Rp124,37 juta | 258 |
| Q2 | Rp135,69 juta | 274 |
| Q3 | Rp123,87 juta | 234 |
| Q4 | Rp129,31 juta | 261 |

### Kondisi bisnis

Q2 menjadi quarter terkuat pada 2023 dan 2024. Q3 menjadi titik pelemahan.

Penurunan Q2 ke Q3:

- 2023: sekitar **25,5%**
- 2024: sekitar **8,7%**

### Implikasi

Q3 masih merupakan periode yang perlu diperhatikan, tetapi stabilitas 2024 jauh lebih baik daripada 2023.

### Rekomendasi

Jangan hanya mencari alasan mengapa Q3 turun. Bandingkan Q3 2023 dengan Q3 2024 untuk menemukan faktor yang membuat penurunan pada 2024 jauh lebih terkendali.

---

## 4. Product mix berubah dari tahun ke tahun

Top product pada setiap tahun tidak sepenuhnya sama.

### 2022

Produk teratas antara lain:

- T-Shirt Graphic SandangIndo
- T-Shirt Graphic Riang Apparel
- Shirt Slim Fit Tropika Style
- Dress Bodycon Pesona Indo

### 2023

Produk teratas bergeser ke:

- T-Shirt Graphic BajuKita
- Kaos Striped Kanvas Lokal
- Dress Mini Casual SandangIndo
- Dompet Kulit Pesona Indo

### 2024

Produk teratas kembali berubah:

- Tas Selempang Riang Apparel
- Celana Jeans Slim SandangIndo
- Kemeja Oxford NusaBrand
- Dress Wrap Pesona Indo

### Kondisi bisnis

Produk yang menjadi top performer tidak sepenuhnya bertahan dari tahun ke tahun.

### Implikasi

Demand pada level produk bersifat dinamis. Ranking historical sepanjang periode tidak cukup untuk menjadi satu-satunya dasar keputusan inventory.

### Rekomendasi

Gunakan kombinasi:

**Recent Revenue + Units Sold + Stock + Trend**

untuk membedakan:

- produk yang konsisten laku,
- produk yang sedang naik,
- produk yang hanya mengalami peak pada periode tertentu.

---

## 5. Accessories semakin penting dalam product mix 2024

### 2022

- Jacket: Rp37 juta
- Dress: Rp36 juta
- Accessories: Rp33 juta

### 2023

- Dress: Rp77 juta
- Jacket: Rp77 juta
- Accessories: Rp73 juta

### 2024

- **Accessories: Rp93 juta**
- **Jacket: Rp91 juta**
- **Dress: Rp82 juta**

### Kondisi bisnis

Jacket, Dress, dan Accessories merupakan kategori utama sepanjang periode, tetapi pada 2024 **Accessories menjadi kategori dengan kontribusi terbesar**.

### Implikasi

Terdapat indikasi perubahan product mix menuju kontribusi Accessories yang lebih tinggi.

### Rekomendasi

Accessories layak dipantau sebagai potential growth category. Namun, peningkatan inventory sebaiknya tetap didasarkan pada performa SKU di dalam kategori, bukan hanya total category revenue.

---

## 6. Brand portfolio relatif terdiversifikasi dan brand leadership berubah

Pada 2024, brand dengan kontribusi terbesar antara lain:

- Riang Apparel — sekitar Rp71 juta
- NusaBrand — sekitar Rp65 juta
- Cendana Co — sekitar Rp64 juta
- SandangIndo — sekitar Rp52 juta
- Tropika Style — sekitar Rp47 juta

### Kondisi bisnis

Pertumbuhan tidak bergantung pada satu brand saja.

### Implikasi

Portfolio brand relatif terdiversifikasi, tetapi performa brand berubah mengikuti periode dan product mix.

### Rekomendasi

Evaluasi brand berdasarkan:

- revenue growth,
- product contribution,
- consistency,
- dan breadth of assortment,

bukan hanya berdasarkan revenue absolut.

---

## 7. Jawa Barat merupakan core market, tetapi kontribusi regional semakin beragam

Revenue Jawa Barat:

- 2022: sekitar **Rp35,49 juta**
- 2023: sekitar **Rp88,28 juta**
- 2024: sekitar **Rp104,07 juta**
- All Year: sekitar **Rp227,85 juta**

### Kondisi bisnis

Jawa Barat merupakan market utama yang konsisten dari tahun ke tahun.

Pada saat yang sama, kontribusi dari provinsi lain juga terlihat cukup luas.

### Implikasi

Gayanara memiliki core market yang kuat, tetapi juga memiliki basis permintaan di berbagai wilayah lain.

### Rekomendasi

Gunakan dua pendekatan:

**Protect the core market:** pertahankan availability dan customer retention di Jawa Barat.

**Diversify the growth:** cari provinsi atau kota dengan growth tinggi untuk mengurangi ketergantungan terhadap satu market.

---

## 8. Market leadership antar kota berubah setiap tahun

### 2022

Top city antara lain:

- Tangerang
- Makassar
- Yogyakarta
- Malang
- Semarang

### 2023

Top city antara lain:

- Medan
- Makassar
- Bekasi
- Surabaya
- Padang

### 2024

Top city antara lain:

- Semarang
- Depok
- Pontianak
- Manado
- Banjarmasin

### Kondisi bisnis

Tidak ada satu kota yang selalu menjadi market terbesar sepanjang periode.

### Implikasi

Market attractiveness berubah dari tahun ke tahun.

### Rekomendasi

Untuk menentukan prioritas ekspansi, jangan hanya melihat **Top Revenue City**. Tambahkan **Revenue Growth by City** agar emerging market dapat dibedakan dari market yang hanya besar secara historical.

---

## 9. Courier mix relatif stabil dan terkonsentrasi

### 2022

- J&T: 30,3%
- JNE: 29,8%
- SiCepat: 24,2%

### 2023

- J&T: 29,4%
- SiCepat: 28,0%
- JNE: 27,6%

### 2024

- J&T: 28,8%
- JNE: 28,8%
- SiCepat: 27,0%

### Kondisi bisnis

J&T, JNE, dan SiCepat konsisten menjadi tiga courier utama setiap tahun dan menangani sekitar 85% order.

### Implikasi

Struktur delivery relatif stabil, tetapi konsentrasi pada tiga partner menciptakan operational dependency.

### Rekomendasi

Monitor:

- SLA,
- delivery reliability,
- shipping cost,
- return rate,
- cancellation rate,
- customer experience.

Dashboard ini hanya menunjukkan volume order sehingga belum cukup untuk menentukan courier terbaik secara kualitas layanan.

---

## 10. Bottom 5 perlu digunakan sebagai alat diagnosis, bukan keputusan langsung

Dashboard menyediakan Bottom 5 Product, Province, dan City by Revenue.

### Kondisi bisnis

Wilayah dan produk dengan revenue rendah berbeda antar tahun. Area yang rendah pada satu tahun tidak otomatis tetap rendah pada tahun berikutnya.

### Implikasi

Performa rendah merupakan sinyal untuk investigasi, bukan bukti langsung bahwa produk atau wilayah harus dihentikan.

### Rekomendasi

Gunakan pendekatan:

**Current Performance + Historical Trend + Growth**

Produk dengan revenue rendah tetapi growth tinggi dapat memiliki potensi yang berbeda dibandingkan produk dengan revenue besar tetapi terus menurun.

---

# Overall Business Condition

Secara keseluruhan:

### Growth
Gayanara mengalami pertumbuhan sangat kuat pada 2023 dan tetap tumbuh pada 2024, tetapi laju pertumbuhannya mulai moderat.

### Customer
Revenue dan orders tumbuh lebih cepat daripada unique customers pada 2024, sehingga customer existing menjadi semakin penting.

### Sales Stability
Q3 merupakan periode yang relatif lemah, tetapi penurunan Q3 pada 2024 jauh lebih terkendali dibandingkan 2023.

### Product
Product leadership berubah antar tahun sehingga product-level monitoring diperlukan.

### Category
Jacket, Dress, dan Accessories menjadi core categories, dengan Accessories menjadi kategori terbesar pada 2024.

### Brand
Kontribusi brand relatif tersebar dan brand leadership berubah antar periode.

### Geography
Jawa Barat menjadi core market yang konsisten, tetapi market leadership antar kota berubah dari tahun ke tahun.

### Operations
J&T, JNE, dan SiCepat menangani mayoritas order secara konsisten.

---

# Priority Business Recommendations

| Priority | Focus | Business Reason |
|---|---|---|
| **1** | Customer Retention | Customer tumbuh lebih lambat daripada revenue dan orders pada 2024 |
| **2** | Q3 Investigation | Q3 menjadi titik lemah yang muncul berulang |
| **3** | Product Trend | Top product berubah antar tahun |
| **4** | Accessories | Menjadi kategori terbesar pada 2024 |
| **5** | Core Market | Jawa Barat tetap menjadi market terbesar |
| **6** | Emerging Market | Top city berubah antar tahun |
| **7** | Courier Management | Tiga courier menangani sekitar 85% order |

---

# Metric Considerations

## Total Revenue

KPI utama menggunakan `total_amount_idr` pada level order.

## Revenue by Brand / Category

Visual Brand dan Category menggunakan `subtotal_idr` pada level item.

Karena discount berada pada level order, `subtotal_idr` tidak secara langsung menunjukkan net revenue setelah discount dialokasikan ke masing-masing brand atau category.

Untuk menghindari interpretasi yang keliru, visual tersebut lebih tepat menggunakan istilah:

- **Gross Sales by Brand**
- **Gross Sales by Category**

daripada **Net Revenue by Brand/Category**.

---

# Transaction Status

KPI dan analisis penjualan menggunakan transaksi valid dan tidak memasukkan:

- `cancelled`
- `returned`

Status tersebut tetap dapat dianalisis secara terpisah untuk cancellation rate dan return rate.

---

# Dashboard Components

### KPI

- Revenue
- Total Orders
- Total Units Sold
- Average Order Value
- Unique Customers

### Sales Performance

- Revenue Trend
- Revenue & Total Orders per Quarter
- Perbandingan YoY Total Revenue

### Product & Brand

- Top 10 Product by Revenue
- Revenue by Brand
- Revenue by Category
- Bottom 5 Product by Revenue

### Geography

- Top 10 Province by Revenue
- Top 10 City by Revenue
- Bottom 5 Province by Revenue
- Bottom 5 City by Revenue

### Operations

- Courier Performance

---

# Interactive Filters

- Year
- Quarter
- Month
- Province
- City
- Brand

---

# Data Model

Project menggunakan tabel:

- `orders`
- `order_items`
- `products`
- `customers`
- `reviews`

Relasi utama menggunakan:

```text
customers
   │
   │ customer_id
   ▼
orders
   │
   │ order_id
   ▼
order_items
   │
   │ product_id
   ▼
products
```

---

# Tools & Skills

- Power BI Desktop
- DAX
- SQL
- Data Modeling
- KPI Development
- Business Analysis
- Data Visualization
- Time-Series Analysis
- Top-N / Bottom-N Analysis
- Geographic Analysis

---

# Portfolio Takeaway

Project ini menunjukkan pendekatan analisis sales yang tidak berhenti pada ranking produk atau wilayah. Analisis dilakukan dengan membandingkan **2022, 2023, dan 2024** untuk memahami perubahan skala bisnis, customer activity, quarter performance, product mix, category contribution, geographic market, dan courier dependency.

Kesimpulan utamanya adalah bahwa Gayanara berada dalam kondisi **bertumbuh**, tetapi karakter pertumbuhannya mulai berubah. Setelah ekspansi sangat kuat pada 2023, 2024 menunjukkan pertumbuhan yang lebih moderat dan semakin dipengaruhi oleh aktivitas customer existing. Di saat yang sama, Q3 masih menjadi periode yang perlu diperhatikan, Accessories mulai menjadi kategori utama, Jawa Barat tetap menjadi core market, dan market leadership antar kota terus berubah.

Karena itu, prioritas bisnis berikutnya adalah **memperkuat customer retention, memahami penyebab pelemahan Q3, mengoptimalkan product mix pada level produk, mempertahankan core market, dan mengembangkan emerging market berdasarkan growth**.

---

# Tools

- **Power BI Desktop**
- **DAX**
- **SQL**
- **Data Visualization**
- **Business Analysis**
