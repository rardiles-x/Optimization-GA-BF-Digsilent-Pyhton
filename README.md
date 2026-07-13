# Bus Coupler Configuration Optimization Using Hybrid GA–Brute Force
Program ini dikembangkan untuk mengoptimalkan konfigurasi disconnecting switch dan bus coupler pada sistem transmisi tenaga listrik. Program mengintegrasikan Python dengan DIgSILENT PowerFactory untuk menjalankan simulasi aliran daya dan hubung singkat secara otomatis.
Metode optimasi yang digunakan adalah Hybrid Genetic Algorithm–Brute Force. Genetic Algorithm digunakan untuk mencari konfigurasi DS bus pada ruang pencarian yang besar, sedangkan Brute Force digunakan untuk mengevaluasi kombinasi pembukaan bus coupler pada gardu induk kandidat.
Pemilihan konfigurasi terbaik dilakukan berdasarkan Indeks Performa Total dengan pembobotan Analytical Hierarchy Process (AHP), yang mencakup:

•	indeks arus hubung singkat;

•	indeks profil tegangan;

•	indeks pembebanan saluran transmisi; dan

•	evaluasi keamanan sistem pada kondisi kontingensi N-1.


**Batasan Operasi**

Konfigurasi hasil optimasi harus memenuhi batas operasi berikut:

•	arus hubung singkat maksimum sesuai kapasitas pemutusan circuit breaker;

•	tegangan bus antara 0,95–1,10 pu;

•	pembebanan saluran transmisi sesuai batas operasi yang ditetapkan; dan

•	tidak menyebabkan pelanggaran sistem pada kondisi N-1.

**Teknologi**

•	Python

•	DIgSILENT PowerFactory

•	Genetic Algorithm

•	Brute Force

•	Analytical Hierarchy Process

•	Microsoft Excel sebagai keluaran hasil evaluasi

**Tujuan Pengembangan**

Program ini dikembangkan sebagai bagian dari penelitian optimasi konfigurasi bus coupler pada subsistem Krian–Gresik setelah penambahan Inter-Bus Transformer di GISTET Waru.
