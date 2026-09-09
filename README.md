# 🔬 Text Mining Lab - Pendidikan Teknologi Informasi

**Text Mining Lab** adalah sebuah aplikasi web interaktif yang dirancang untuk mendemonstrasikan dan melakukan eksperimen tahap awal dalam pemrosesan bahasa alami (NLP) dan *Text Mining*, khususnya untuk teks berbahasa Indonesia. 

Aplikasi ini berjalan sepenuhnya di sisi klien (client-side) menggunakan algoritma Vanilla JavaScript untuk memproses teks secara *real-time* tanpa memerlukan *backend server*.

> Dikembangkan oleh: **Dennis Kiftirul Azis**

---

## ✨ Fitur Utama

1. **📊 Dashboard Analisis Real-time**
   - Memantau metrik pemrosesan secara langsung.
   - Menampilkan statistik penting seperti: Total Teks Diproses, Total Kata Ekstrak (Token), Stopword Dihapus, dan Rata-rata Waktu eksekusi.
   - Visualisasi rasio filter teks dan tren produksi token menggunakan **Chart.js**.

2. **⚙️ Interactive Text Pre-processing**
   Alat visual langkah-demi-langkah yang menunjukkan bagaimana teks mentah diubah menjadi data terstruktur melalui 5 tahapan utama:
   *   **Case Folding:** Mengubah seluruh huruf menjadi huruf kecil (*lowercase*).
   *   **Cleaning:** Menghapus tautan URL, angka, simbol, dan tanda baca.
   *   **Tokenization:** Memecah kalimat utuh menjadi deretan kata (*array of tokens*).
   *   **Stopword Removal:** Menyaring kata-kata hubung atau kata umum bahasa Indonesia yang kurang memiliki bobot makna (menggunakan *Set* dinamis).
   *   **Stemming (Sederhana):** Mengembalikan kata berimbuhan menjadi kata dasar dengan algoritma penghapusan awalan/akhiran serta kamus pengecualian *(exception dictionary)*.

3. **📂 Manajemen Dataset & Riwayat**
   - Hasil pemrosesan teks secara otomatis disimpan ke dalam `localStorage` browser.
   - Melihat detail rincian (breakdown) dari setiap teks yang pernah diproses.
   - **Ekspor Data:** Mengunduh hasil teks yang sudah dibersihkan ke dalam format `.CSV` atau `.JSON` untuk keperluan analisis lanjutan atau pelatihan model *Machine Learning*.

4. **🌗 Dukungan Dark Mode**
   - Antarmuka yang modern dan responsif, dilengkapi dengan mode gelap (Dark Mode) untuk kenyamanan penggunaan.

---

## 💻 Teknologi yang Digunakan

Proyek ini dibangun tanpa *framework javascript* yang berat, sehingga sangat ringan dan cepat.

*   **HTML5** (Semantik struktur web)
*   **Tailwind CSS** (Styling via CDN)
*   **Vanilla JavaScript** (Logika pemrosesan teks & manipulasi DOM)
*   **Chart.js** (Visualisasi data pada Dashboard)
*   **FontAwesome** (Ikon UI)
*   **Browser LocalStorage** (Penyimpanan database riwayat secara lokal)

---

## 🚀 Cara Menjalankan Aplikasi

Karena aplikasi ini sepenuhnya berbasis *Client-Side*, Anda tidak perlu melakukan proses instalasi khusus seperti `npm install` atau menjalankan server lokal.

1. **Clone** atau **Download** repositori ini ke komputer Anda.
2. Ekstrak file jika mendownload dalam bentuk `.zip`.
3. Klik kanan pada file `index.html` dan pilih **Open with...** lalu pilih browser modern favorit Anda (Google Chrome, Mozilla Firefox, Microsoft Edge, atau Safari).
4. Aplikasi siap digunakan!

---

## 💡 Panduan Penggunaan

1. Buka tab **Pre-processing** di menu Sidebar.
2. Anda bisa **mengetik teks**, **mengunggah file `.txt`**, atau menekan salah satu tombol **Data Uji** untuk mencoba teks bawaan.
3. Klik tombol **"Mulai Proses Teks"**.
4. Gulir ke bawah untuk melihat bagaimana sistem memecah teks Anda di setiap tahapannya.
5. Klik **"Salin Teks Bersih"** untuk menyalin hasilnya.
6. Masuk ke tab **File History & Dataset** untuk mengelola riwayat atau mengekspor hasil ke format CSV/JSON.

---

## 📝 Lisensi & Hak Cipta

Proyek web ini dibuat sebagai bahan pembelajaran dan laboratorium eksperimen *Text Mining* untuk bidang Pendidikan Teknologi Informasi.

Dibuat oleh **Dennis Kiftirul Azis**
