# EXCEL- ecommerce-sales-analysis
-Commerce Sales Performance &amp; Customer Behavior Analysis using Excel and Power BI)

# 📊 E-Commerce Sales Performance & Customer Behavior Analysis

## 📌 Executive Summary
Proyek ini bertujuan untuk menganalisis performa penjualan, efektivitas strategi diskon, performa logistik pengiriman, serta perilaku/frekuensi pembelanjaan pelanggan pada platform e-commerce (5.000 transaksi). Analisis dilakukan menggunakan **Microsoft Excel (Pivot Table & Data Modeling)** dan divisualisasikan secara interaktif melalui **Power BI Desktop**.

---

## 🔑 Key Business Metrics (KPIs)
* **Total Sales Volume:** 5,000 Order
* **Top Revenue Category:** Electronics ($1.83M Revenue | 1,777 Orders)
* **Highest AOV Category:** Home (~$1,145 per order)
* **Optimal Discount Range:** 20% - 30% (Sweet Spot)
* **Total Unique Customers:** 989 Pelanggan

---

## 💡 Key Insights & Business Recommendations

### 1. Performa Kategori Produk & Revenue
* **Insight:** Kategori **Electronics** mendominasi volume transaksi (1.777 order) sekaligus total pendapatan tertinggi. Sebaliknya, kategori **Home** memiliki nilai rata-rata transaksi (*Average Order Value / AOV*) tertinggi (~$1,145 per transaksi).
* **Rekomendasi Bisnis:** 
  * Pertahankan ketersediaan stok & alokasi promo pada *Electronics* sebagai penggerak utama volume penjualan.
  * Terapkan strategi *product bundling* pada kategori *Home* untuk memaksimalkan nilai keranjang belanja pelanggan.

### 2. Efektivitas Diskon (*Discount Impact Analysis*)
* **Insight:** Besaran diskon **20% - 30%** merupakan *sweet spot* psikologis pembeli dengan total kuantiti barang terjual tertinggi (6.117 item). Diskon di bawah 10% atau di atas 30% terbukti kurang efektif mendongkrak kuantiti penjualan.
* **Rekomendasi Bisnis:** Batasi alokasi promo diskon di kisaran 20%–30% untuk menjaga tingkat profitabilitas tanpa mengorbankan volume penjualan.

### 3. Logistik Pengiriman vs. Kepuasan Pelanggan
* **Insight:** Durasi pengiriman **1–3 hari** menghasilkan rata-rata rating kepuasan pelanggan tertinggi (**3.08**). Kepuasan pelanggan cenderung menurun secara konsisten pada estimasi pengiriman di atas 4 hari.
* **Rekomendasi Bisnis:** Tingkatkan kerja sama dengan mitra ekspedisi/kurir lokal guna memastikan mayoritas pengiriman sampai dalam waktu maksimal 3 hari.

### 4. Distribusi Frekuensi Belanja Pelanggan
* **Insight:** Dari total 989 pelanggan unik, mayoritas pelanggan bertransaksi sebanyak 3–6 kali. Terdapat 39 pelanggan baru yang baru melakukan 1 kali transaksi (*one-time buyers*).
* **Rekomendasi Bisnis:** Buat program retensi (*loyalty reward* / voucher transaksi kedua) khusus untuk kelompok pembeli 1 kali agar terdorong menjadi pelanggan setia (*repeat customers*).

---

## 📸 Visualisasi Dashboard

![Revenue by Category](./category_revenue_chart.png)
*Gambar 1: Perbandingan Total Revenue & Volume Order per Kategori Produk*

![Discount Sweet Spot](./discount_quantity_chart.png)
*Gambar 2: Distribusi Kuantitas Penjualan berdasarkan Tingkat Diskon*

---

## 🛠️ Tools & Technologies Used
* **Microsoft Excel:** Pivot Table, Data Cleaning, Conditional Formatting, Executive Summary Dashboard.
* **Power BI Desktop:** DAX Calculations, Data Visualization & Interactive Dashboard.
* **Python:** Data verification & automated plotting (Pandas, Matplotlib, Seaborn).
