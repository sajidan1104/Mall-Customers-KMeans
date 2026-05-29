# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Deskripsi Proyek
Proyek ini mengimplementasikan algoritma **K-Means Clustering** untuk melakukan segmentasi pelanggan (*Customer Segmentation*) pada sebuah pusat perbelanjaan (Mall). Tujuan utamanya adalah untuk mengelompokkan pelanggan ke dalam beberapa kategori berdasarkan perilaku finansial mereka, sehingga tim *marketing* dapat merancang strategi promosi yang lebih tepat sasaran.

## 📊 Dataset
Dataset yang digunakan adalah **Mall Customers Dataset**.
Fitur utama yang digunakan untuk proses *clustering* adalah:
* **Annual Income (k$)**: Pendapatan tahunan pelanggan dalam ribuan dolar.
* **Spending Score (1-100)**: Skor yang diberikan oleh pihak mall berdasarkan perilaku belanja pelanggan (semakin tinggi skor, semakin sering/banyak berbelanja).

## 🛠️ Teknologi yang Digunakan
* **Bahasa Pemrograman:** Python
* **Library Data Analisis:** Pandas, NumPy
* **Library Machine Learning:** Scikit-Learn
* **Library Visualisasi:** Matplotlib

## 📈 Hasil Analisis (Business Insights)
Berdasarkan visualisasi menggunakan K-Means (dengan nilai *K=5*), pelanggan berhasil dikelompokkan ke dalam 5 klaster yang sangat jelas:

1. **Klaster 0 (Pendapatan Sedang, Pengeluaran Sedang):** Kelompok pelanggan standar dan mayoritas. Strategi: Berikan program loyalitas reguler.
2. **Klaster 1 (Pendapatan Rendah, Pengeluaran Rendah):** Pelanggan yang hemat. Strategi: Berikan promosi barang kebutuhan pokok atau diskon harian.
3. **Klaster 2 (Pendapatan Tinggi, Pengeluaran Rendah):** Pelanggan kaya yang sangat selektif. Strategi: Tawarkan produk investasi, asuransi, atau barang berkualitas premium.
4. **Klaster 3 (Pendapatan Rendah, Pengeluaran Tinggi):** Pelanggan boros/impulsif (umumnya anak muda). Strategi: Targetkan dengan tren terbaru dan *fast-fashion*.
5. **Klaster 4 (Pendapatan Tinggi, Pengeluaran Tinggi):** **Target Pasar Utama (Sultan)**. Strategi: Berikan fasilitas VIP, promosi barang mewah (*luxury brand*), dan pelayanan personal (*personal shopper*).

## 🚀 Cara Menjalankan Proyek
1. Clone repositori ini ke dalam *local machine* Anda:
   ```bash
   git clone [https://github.com/username-anda/nama-repositori.git](https://github.com/username-anda/nama-repositori.git)
