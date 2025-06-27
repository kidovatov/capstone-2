# capstone-2
Capstone 2 Project Data Analysis

Latar Belakang
Dalam era digital saat ini, perusahaan yang bergerak di bidang Software as a Service (SaaS) mengandalkan data penjualan sebagai dasar pengambilan keputusan strategis. Data penjualan yang terekam mencakup berbagai dimensi, mulai dari produk yang dijual, pelanggan yang membeli, wilayah geografis, hingga performa keuntungan dan diskon.

Data historis penjualan SaaS dapat membantu mengidentifikasi pola perilaku konsumen, efektivitas strategi harga dan diskon, serta segmentasi pasar yang paling menguntungkan. Namun, tanpa analisis yang sistematis, potensi insight dari data ini bisa terlewatkan. Oleh karena itu, diperlukan analisis menyeluruh terhadap data penjualan untuk mendukung optimalisasi strategi bisnis.  

Pernyataan Masalah

RUMUSAN MASALAH
Berdasarkan latar belakang tersebut, berikut beberapa pertanyaan penelitian atau pernyataan masalah yang dapat dikembangkan:
1. Siapa penyumbang pendapatan terbesar beserta hasil analisisnya?
2. Produk apa yang paling banyak dijual dan paling menguntungkan?
3. Bagaimana tren penjualan produk SaaS dari waktu ke waktu?
4. Wilayah geografis mana yang menghasilkan penjualan dan profit terbesar?
5. Customer Value: Siapa pelanggan VIP dengan kontribusi tinggi?

Missing Value
1. Tidak ada missing value di file SaaS-Sales.csv
2. Dataset siap untuk dianalisis langsung tanpa perlu imputasi data hilang
3. Kita bisa langsung masuk ke tahap EDA (Exploratory Data Analysis), visualisasi, atau analisis lanjutan seperti clustering, prediksi, segmentasi pelanggan, dll.

Rumusan Masalah 
1. Siapa penyumbang pendapatan terbesar beserta hasil analisisnya
Hasil:
•	Anthem adalah pelanggan dengan total penjualan (sales) tertinggi: $55.719
•	Diikuti oleh Ford Motor, Allianz, dan Bank of America Corp.

SARAN
1.	Fokus pada Retensi Pelanggan Utama (Top-Tier Clients)
2.	Bangun Program Kemitraan Strategis
3.	Analisis Preferensi dan Perilaku Pelanggan Top
4.	Perluas Target ke Pelanggan Sejenis
5.	Pemantauan Berkala & Early Warning System
“Pelanggan besar bukan hanya penyumbang revenue, tapi juga aset jangka panjang. Fokus pada retensi, pelayanan premium, dan perluasan ke segmen serupa akan memperkuat pertumbuhan bisnis yang berkelanjutan.”

2. Produk apa yang paling banyak dijual dan paling menguntungkan?
Hasil Analisis:
Produk dengan Penjualan Terbanyak (Quantity):
1.	ContactMatcher — 7.215 unit
2.	Support — 5.825 unit
3.	FinanceHub — 3.756 unit

Produk dengan Keuntungan Tertinggi (Total Profit):
	Site Analytics menghasilkan profit tertinggi meskipun hanya di urutan ke-5 dalam jumlah terjual.
•	Produk seperti Support dan FinanceHub juga memberikan kontribusi profit besar.

SARAN
1. Pertahankan Produk Terlaris dengan Strategi Volume
2. Dorong Penjualan Produk dengan Margin Tinggi
 3. Kombinasikan Produk Volume & Margin
 4. Analisis Lebih Lanjut: ROI per Produk
5. Manfaatkan Temuan untuk Strategi Produk & Marketing
Kesimpulan Strategis
“Produk yang sering dibeli belum tentu yang paling menguntungkan. Gabungkan strategi berdasarkan kuantitas (volume driver) dan profitabilitas (margin driver) untuk mencapai pertumbuhan penjualan yang seimbang dan berkelanjutan.”


3. Bagaimana tren penjualan produk SaaS dari waktu ke waktu?
Penjelasan Hasil:
•	Grafik menunjukkan pergerakan total penjualan setiap bulan dari Januari 2020 hingga akhir periode dataset.
•	Terlihat bahwa penjualan mengalami fluktuasi yang signifikan, dengan beberapa bulan memiliki lonjakan tinggi seperti Maret 2020.
•	Tren ini berguna untuk mengidentifikasi musim puncak (peak season) dan masa penurunan (off season).

SARAN
Penjualan produk SaaS mengalami fluktuasi bulanan yang signifikan sepanjang periode 2020–2023. Beberapa bulan seperti Maret 2020 menunjukkan lonjakan penjualan yang mencolok. Pola ini penting untuk mengenali musim puncak dan masa lesu penjualan. Perusahaan dapat memanfaatkan data ini untuk mengatur kampanye promosi secara lebih tepat waktu. Selain itu, perencanaan kapasitas dan stok juga bisa disesuaikan berdasarkan tren bulanan ini.


4. Wilayah geografis mana yang menghasilkan penjualan dan profit terbesar?
Berdasarkan Region:
•	Region dengan total penjualan dan profit tertinggi adalah EMEA (Europe, Middle East, Africa), diikuti oleh AMER dan APAC.

SARAN
Wilayah EMEA sebaiknya dijadikan prioritas dalam strategi pemasaran dan pengembangan bisnis karena kontribusi penjualan dan profitnya paling tinggi. Perusahaan dapat meningkatkan penetrasi pasar di EMEA melalui kampanye lokal yang lebih tersegmentasi. Wilayah AMER dan APAC tetap menjanjikan dan layak didorong dengan pendekatan yang disesuaikan. Perbandingan antar region juga bisa dimanfaatkan untuk mengevaluasi efektivitas strategi distribusi dan penawaran produk. Investasi dalam customer engagement dan partner lokal di EMEA akan membantu mempertahankan dominasi pasar di kawasan tersebut.


5. Customer Value: Siapa pelanggan VIP dengan kontribusi tinggi?
Valero Energy memiliki profit per unit tertinggi di antara pelanggan top → bisa jadi pelanggan prioritas untuk upselling atau loyalty program.

SARAN
Valero Energy sebaiknya diprioritaskan sebagai pelanggan utama karena profit per unit yang dihasilkan sangat tinggi. Perusahaan dapat menawarkan program loyalitas eksklusif atau bundling produk premium untuk meningkatkan retensi. Strategi upselling juga layak diterapkan dengan pendekatan personalisasi kebutuhan bisnis mereka. Analisis lebih lanjut terhadap pola pembelian Valero dapat membantu mereplikasi strategi ke pelanggan sejenis. Menjaga hubungan jangka panjang dengan pelanggan seperti Valero akan berdampak langsung pada stabilitas dan pertumbuhan profit perusahaan.
