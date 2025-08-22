# dataset
Harmful Content Dataset
Dataset: Klasifikasi Konten Online Berbahaya di Indonesia

Repositori ini berisi dataset yang digunakan dalam penelitian kami tentang klasifikasi konten online berbahaya yang kompleks dan tumpang tindih. Dataset ini bersumber dari catatan pemantauan 

Badan Siber dan Sandi Negara (BSSN) Indonesia.

Deskripsi 📖

Dataset ini terdiri dari 

7.140 catatan unik dari berita dan unggahan online berbahasa Indonesia yang dikumpulkan antara 1 Oktober hingga 31 Desember 2024. Dataset ini dibuat untuk mengatasi kelangkaan dataset beranotasi dan multi-level untuk konten berbahaya, khususnya untuk bahasa dengan sumber daya rendah. Dataset ini digunakan untuk melatih dan memvalidasi kerangka kerja 

KG-DToT-HTC kami, yang dirancang untuk klasifikasi konten berbahaya yang akurat dan transparan.

Sitasi ✍️

Jika Anda menggunakan dataset ini dalam penelitian Anda, mohon sitasi makalah kami:
Code snippet

@article{Authorl2025HarmfulContent,
  title   = {Unifying Knowledge, Reasoning, and Hierarchy for Classifying Harmful Content},
  author  = {Raden Budiarto H. and I Gede Maha Putra},
  journal = {-},
  year    = {2025},
  note    = {Data sourced from Badan Siber dan Sandi Negara (BSSN) Indonesia}
}

Struktur Dataset 📂

Dataset ini disediakan dalam satu file CSV: bssn_harmful_content_filtered.csv.

Setiap baris dalam file ini merepresentasikan satu konten online dan memiliki kolom-kolom berikut:
Nama Kolom	Tipe Data	Deskripsi
Title	String	

Judul berita atau unggahan.

Description	String	

Teks utama dari artikel, unggahan, atau komentar.

Cluster	Kategorikal	

Label kategori umum dari BSSN (misalnya, "Ekstremisme", "Penipuan Finansial").

Subcluster	Kategorikal	

Label subkategori yang lebih spesifik di dalam sebuah cluster.

Action	Kategorikal	

Tindakan moderasi yang direkomendasikan ("none", "block", "report to authorities").

Relation	Kategorikal	

Tipe atau format sumber konten (berita, tweet, unggahan, komentar).

Account	String	

Nama akun media sosial atau URL outlet media asal.

Timestamp	DateTime	

Waktu publikasi atau unggah (YYYY-MM-DD HH:MM:SS).

Geolocation	String	

Metadata lokasi unggahan (kota, provinsi, negara).

⚠️ Catatan Mengenai Pemfilteran Konten

Untuk tujuan keamanan dan etika, versi publik dari dataset ini telah melalui proses pemfilteran.

Sebagian konten yang bersifat sangat eksplisit, seperti pornografi grafis dan kekerasan ekstrem, telah dihapus dari file bssn_harmful_content_filtered.csv untuk mencegah penyebaran materi yang sangat berbahaya.

Akses ke Dataset Lengkap

Dataset lengkap dan tanpa filter tersedia untuk tujuan penelitian yang sah dan terbatas bagi para peneliti, akademisi, dan mahasiswa yang berafiliasi dengan institusi yang diakui.

Untuk meminta akses, silakan kirim email ke [alamat.email.anda@institusi.ac.id] dengan subjek "Permintaan Akses Dataset BSSN". Mohon sertakan informasi berikut dalam email Anda:

    Nama lengkap dan afiliasi institusional Anda.

    Tautan ke profil akademik Anda (misalnya, Google Scholar, halaman profil universitas).

    Deskripsi singkat tentang proyek penelitian Anda dan bagaimana dataset ini akan digunakan.

Setiap permintaan akan ditinjau secara individual.

Lisensi 📄

Dataset ini dilisensikan di bawah 

Creative Commons Attribution 4.0 International License (CC BY 4.0).

Kontak 📬

Untuk pertanyaan lebih lanjut mengenai dataset ini, silakan hubungi [Nama Anda/Nama Lab] di [alamat.email.anda@institusi.ac.id].
