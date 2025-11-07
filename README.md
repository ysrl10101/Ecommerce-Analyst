🛒 E-Commerce Product Analysis
📘 Project Overview

Proyek ini bertujuan untuk menganalisis data penjualan produk e-commerce menggunakan Python (Pandas, Matplotlib, Seaborn) dan SQL-style analysis.
Analisis ini berfokus pada tren penjualan, performa produk, rating pelanggan, serta hubungan antara diskon, harga, dan volume penjualan.

Dataset terdiri dari 1.000 baris data yang mencakup informasi produk, kategori, harga, diskon, stok, penjualan, rating, dan kota.

🧩 Dataset Information

Nama file: ecommerce_product_dataset.csv
Jumlah baris: 1000
Jumlah kolom: 11

Kolom	Deskripsi
ProductID	ID unik untuk setiap produk
ProductName	Nama produk
Category	Kategori produk
Price	Harga produk (USD)
Rating	Rating pelanggan (1–5)
NumReviews	Jumlah ulasan pelanggan
StockQuantity	Jumlah stok produk tersedia
Discount	Diskon dalam bentuk desimal (contoh: 0.25 = 25%)
Sales	Jumlah produk terjual
DateAdded	Tanggal produk ditambahkan
City	Kota tempat penjualan dilakukan
🧠 Key Business Questions

Produk mana yang memiliki total penjualan tertinggi?

Kategori mana yang menghasilkan penjualan rata-rata tertinggi?

Kota mana yang memiliki penjualan total tertinggi dan terendah?

Apakah ada hubungan antara diskon dan jumlah penjualan?

Produk dengan rating tertinggi di setiap kategori.

Kategori dengan rata-rata rating tertinggi dan terendah.

Apakah jumlah ulasan berbanding lurus dengan rating?

Produk mana yang stoknya hampir habis tetapi memiliki penjualan tinggi?

Apakah harga memengaruhi tingkat penjualan?

Kategori apa yang paling sering memberikan diskon besar?

📊 Tools & Libraries

Python 3

Pandas → Data wrangling & agregasi

Matplotlib & Seaborn → Visualisasi

NumPy → Analisis numerik dasar

Jupyter Notebook / Google Colab

🔍 Insights Summary
No	Insight Utama	Kesimpulan
1	Produk dengan penjualan tertinggi	Biography (23,947 unit)
2	Kategori penjualan tertinggi	Bedsheets dan Art & Crafting Materials
3	Kota dengan penjualan tertinggi	Pittsburgh
4	Diskon vs Penjualan	Korelasi sangat lemah (0.027)
5	Rating tertinggi per kategori	Bamboo Sheets, Biography, Laptop, Jeans
6	Rating tertinggi/terendah	Socks (3.51) dan Makeup (2.76)
7	Ulasan vs Rating	Tidak berkorelasi signifikan (-0.009)
8	Stok rendah tapi penjualan tinggi	Screen Protector, Sketchbook, Earbuds
9	Harga vs Penjualan	Korelasi lemah (0.029)
10	Kategori dengan diskon besar	Makeup paling sering memberi diskon besar
📈 Visualization Ideas

Beberapa visualisasi yang direkomendasikan:

Bar Chart: Top 10 produk berdasarkan penjualan

Box Plot: Distribusi harga antar kategori

Heatmap: Korelasi antar variabel numerik

Scatter Plot: Diskon vs Penjualan / Harga vs Penjualan

Pie Chart: Proporsi penjualan per kategori

🧾 Project Structure
📁 ecommerce-analysis/
 ┣ 📄 README.md
 ┣ 📄 ecommerce_product_dataset.csv
 ┗ 📄 analysis.ipynb

💬 Conclusion

Analisis ini menunjukkan bahwa:

Kategori tertentu seperti Bedsheets dan Art & Crafting Materials memberikan kontribusi besar terhadap total penjualan.

Tidak terdapat korelasi kuat antara diskon, harga, dan volume penjualan — artinya faktor lain seperti kualitas produk dan popularitas lebih berpengaruh.

Produk dengan rating tinggi tidak selalu memiliki banyak ulasan, sehingga ulasan bukan satu-satunya indikator kepuasan pelanggan.

🚀 Next Steps

Mengintegrasikan data historis untuk analisis tren waktu (time series).

Menambahkan dashboard interaktif dengan Power BI atau Tableau.

Membandingkan performa kota berdasarkan waktu dan kategori produk.

👨‍💻 Author

Yasril Jahja
📧 [yasril10@gmail.com]
]
📍 Indonesia
💼 Aspiring Data Analyst | SQL | Python | Power BI
