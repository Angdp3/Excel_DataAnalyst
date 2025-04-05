# Coffee Shop Dashboard With Excel 
*Preview* 
-tunggu beberapa saat jika preview gif tidak muncul
![coffeeDashboard](https://github.com/user-attachments/assets/951c810f-5a77-4ff7-8ae8-bb0aab94897b)

## 📌 Introduction

Proyek ini bertujuan untuk menganalisis jumlah penghasilan dan rata-rata berdasarkan *store location* dan *product category* menggunakan dataset fiktif dari Maven Analytics. Dengan bantuan Excel, saya membangun dashboard interaktif untuk memudahkan pengambilan keputusan dan eksplorasi data.

---

## 🛠️ What I Did

### ✅ 1. Data Preprocessing
- Memastikan **tidak ada missing value**
- Pemeriksaan konsistensi pada kolom lalu membuat kolom baru `total_revenue` berdasarkan `unit_price` dan `quantity`

### ✅ 2. Data Validation
- Menambahkan **drop-down list** (data validation) untuk memilih:
  - Store Location
  - Product Category

### ✅ 3. Formula Used
- `SUMIFS` – Menjumlahkan revenue berdasarkan kondisi tertentu
- `COUNTIFS` – Menghitung jumlah data sesuai filter
- `AVERAGEIFS` – Menghitung rata-rata revenue berdasarkan filter
- `IF` / `IFERROR` – Penanganan kondisi 
- `UNIQUE` – Menampilkan daftar unik

### ✅ 4. Dashboard & Visualization
- **Bar chart**: untuk menampilkan jumlah revenue per kategori dan lokasi
- ![Bar chart](https://github.com/user-attachments/assets/ac5aa055-eef0-4837-bb12-bd84ac9c57f6)
- ![Capture](https://github.com/user-attachments/assets/71ddc426-70b1-4fc9-b2c7-0501f1da7273)

- **Card Metrics**: jumlah transaksi , rata-rata transaksi, per lokasi dan kategori
- ![card](https://github.com/user-attachments/assets/5e9f4fbf-9225-45de-bc47-57fbe0367745)
- Dashboard disusun dengan layout bersih, menggunakan warna yang mudah dibaca

---

## 📈 Key Insights

- Lokasi dengan revenue tertinggi adalah **Hell Kithcen** melalui penjualan **Coffeee**
- Kategori produk **Coffee** cenderung memiliki Revenue tertinggi dari 3 lokasi jika dibandingkan dengan produk kategori lainnya

---


