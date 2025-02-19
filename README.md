## Ulasan Proyek

Tujuan dari proyek ini adalah untuk memperdalam descriptive statistics dan inferential statistics dengan Python. Menggunakan apa yang telah dipelajari; unduh Kumpulan Data Penjualan Properti NYC dari Kaggle. Kumpulan data ini adalah catatan dari setiap bangunan atau unit bangunan (apartemen, dll.) yang dijual di pasar properti Kota New York selama periode 12 bulan.

Kumpulan data ini berisi:  
- `BOROUGH`: **Kode digit untuk wilayah tempat properti berada; arti kode ini adalah Manhattan (1), Bronx (2), Brooklyn (3), Queens (4), dan Staten Island (5).**
- `NEIGHBORHOOD`: **Nama lingkungan dalam proses penilaian properti.** 
- `BUILDING CLASS CATEGORY`: **Ini adalah bidang yang kami sertakan agar pengguna File Penjualan Bergulir dapat dengan mudah mengidentifikasi properti serupa dengan penggunaan luas(mis. Rumah Satu Keluarga) tanpa melihat ke atas Kelas Bangunan individu.**
- `TAX CLASS AT PRESENT`: **Setiap properti di kota ditetapkan ke salah satu dari empat kelas pajak (Kelas 1, 2, 3, dan 4), berdasarkan penggunaan properti tersebut.**
- `BLOCK`: **Blok Pajak adalah sub-divisi wilayah tempat properti sebenarnya berada.** 
- `LOT`: **Lot Pajak adalah subdivisi dari Blok Pajak dan mewakili lokasi unik properti.**
- `EASE-MENT`: **An easement is a right, such as a right of way, which allows an entity to make limited use of another’s real property.**
- `BUILDING CLASS AT PRESENT`: **Klasifikasi Bangunan digunakan untuk menggambarkan penggunaan konstruktif properti.**
- `ADDRESS`: **Alamat jalan properti seperti yang tercantum pada File Penjualan.**
- `APARTMENT NUMBER`: **Nomor apartemen**
- `ZIP CODE`: **Kode pos properti**
- `RESIDENTIAL UNITS`: **Jumlah unit hunian di properti yang terdaftar.**
- `COMMERCIAL UNITS`: **Jumlah unit komersial di properti yang terdaftar.**
- `TOTAL UNITS`: **Jumlah total unit di properti yang terdaftar.**
- `LAND SQUARE FEET`: **Luas tanah properti tercantum dalam persegi.**
- `GROSS SQUARE FEET`: **Luas total semua lantai bangunan yang diukur dari permukaan luar bangunan dinding luar bangunan, termasuk luas tanah dan ruang di dalam setiap bangunan atau struktur di properti**
- `YEAR BUILT`: **Tahun bangunan di properti itu dibangun.**
- `TAX CLASS AT TIME OF SALE`: **-**
- `BUILDING CLASS AT PRESENT dan BUILDING CLASS AT TIME OF SALE`: **Klasifikasi Bangunan digunakan untuk menggambarkan penggunaan konstruktif properti.**   
- `SALE PRICE`: **Harga yang dibayarkan untuk properti.**
- `SALE DATE`: **Tanggal properti terjual.**

Untuk referensi lebih lanjut tentang masing-masing data, lihat <a href="http://www1.nyc.gov/assets/finance/downloads/pdf/07pdf/glossary_rsf071607.pdf">Glossary of Terms</a>.

Merumuskan pertanyaan dan menurunkan uji hipotesis statistik untuk menjawab pertanyaan tersebut. Anda harus menunjukkan bahwa Anda dapat membuat keputusan menggunakan data secara ilmiah. Contoh soal bisa berupa:  

- Apakah ada perbedaan unit yang terjual antara properti yang dibangun tahun 1900-2000 dengan tahun 2001 seterusnya?
- Apakah ada perbedaan unit yang dijual berdasarkan kategori bangunan?
- Apa yang dapat Anda temukan tentang real estat Kota New York dengan melihat catatan transaksi mentah selama satu tahun? Bisakah Anda melihat tren di pasar?

## Rubrik Proyek

Ulasan Kode

| Kriteria | Memenuhi Harapan 
| ----------- | ----------- |
| Measure of Central Tendency: Mean | Student Mengimplementasikan Mean dari Kolom/Data Spesifik Menggunakan Pandas, Numpy, Atau Scipy.
| Measure of Central Tendency: Median | Student Mengimplementasikan Median dari Kolom/Data Spesifik Menggunakan Pandas, Numpy, Atau Scipy.
| Measure of Central Tendency: Modus | Student Mengimplementasikan Modus dari Kolom/Data Spesifik Menggunakan Pandas, Numpy, Atau Scipy.
| Measure of Spread: Range | Student Mengimplementasikan Range dari Kolom/Data Spesifik Menggunakan Pandas, Numpy, Atau Scipy.
| Measure of Spread: Variance| Student Mengimplementasikan Variance dari Kolom/Data Spesifik Menggunakan Pandas, Numpy, Atau Scipy.
| Measure of Spread: Standard Deviation | Student Mengimplementasikan SD dari Kolom/Data Spesifik Menggunakan Pandas, Numpy, Atau Scipy.
| Probability Distribution | Student Menganalisa Distribusi Data Dan Menarik Informasi Dari Distribusi Tersebut.
| Confidence Intervals | Mengimplementasikan Confidence Intervals.
| Hypothesis Testing | Membuat 1 Hipotesis Dan Menarik Kesimpulan Dari Data Yang Ada.
| Preprocessing | Student Melakukan Preproses Dataset Sebelum Melakukan Proses Statistik.
| Apakah Kode Berjalan Tanpa Ada Eror? | Kode Berjalan Tanpa Ada Eror. Seluruh Kode Berfungsi Dan Dibuat Dengan Benar.
  
Readability/Keterbacaan  

| Kriteria | Memenuhi Harapan 
| ----------- | ----------- |
| Tertata Dengan Baik | Semua Cell Di Notebook Terdokumentasi Dengan Baik Dengan Markdown Pada Tiap Cell Untuk Penjelasan Kode.
  
Analisis

| Kriteria | Memenuhi Harapan 
| ----------- | ----------- |
| Overall Analisis | Menarik Informasi/Kesimpulan Dari Keseluruhan Plot Yang Dapat Menjawab Hipotesis.