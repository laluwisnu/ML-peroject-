# 🇮🇩 Analisis Sentimen Berita Ekonomi Indonesia Menggunakan IndoBERT

Project ini bertujuan untuk melakukan analisis sentimen terhadap kumpulan berita ekonomi nasional Indonesia. Prosesnya meliputi pembersihan data, pelabelan berbasis leksikon sederhana, ekstraksi fitur klasik, hingga fine-tuning model **IndoBERT** untuk klasifikasi sentimen (**Positif**, **Netral**, **Negatif**).

---

## ⚙️ Fitur Utama

* **Pembersihan Data Otomatis:** Melakukan *light text preprocessing* (membersihkan tag HTML, URL, angka berlebihan, karakter non-esensial, dan menangani *missing value*/duplikasi).
* **Pelabelan Berbasis Leksikon:** Implementasi metode *lexicon-based* sederhana untuk memberikan label awal (positif/negatif/netral) pada data berita.
* **Ekstraksi Fitur Klasik:** Menerapkan **Bag of Words (BoW)**, **TF-IDF Unigram**, dan **TF-IDF N-gram** untuk representasi teks dan visualisasi frekuensi kata.
* **Fine-Tuning IndoBERT:** Menggunakan model pra-latih **IndoBERT** dari Hugging Face (`indobenchmark/indobert-base-p1`) untuk tugas klasifikasi sentimen guna mencapai akurasi yang lebih tinggi.
* **Analisis Temporal Sentimen:** Visualisasi dan analisis tren sentimen (Positif, Netral, Negatif) dari berita-berita per bulan.

---

## 🛠️ Teknologi dan Dependensi

Project ini dikembangkan menggunakan Python dan memanfaatkan ekosistem data science/NLP yang populer.

| Kategori | Teknologi | Peran Kunci |
| :--- | :--- | :--- |
| **Bahasa** | Python 3.x | Bahasa Pemrograman Utama |
| **Inti NLP/ML** | `transformers` (Hugging Face) | Implementasi model IndoBERT |
| | `torch` atau `tensorflow/keras` | Backend deep learning |
| | `scikit-learn` | Ekstraksi fitur klasik dan metrik evaluasi |
| **Model Utama** | `indobenchmark/indobert-base-p1` | Model Pre-trained untuk Fine-Tuning |
| **Data & Visualisasi**| `pandas`, `matplotlib`, `numpy`, `datasets` | Manipulasi data dan pembuatan visualisasi |

### 🚀 Instalasi Dependensi

Untuk menginstal semua dependensi yang dibutuhkan, jalankan perintah berikut:

```bash
pip install pandas scikit-learn numpy matplotlib transformers torch datasets
💻 Prasyarat dan Struktur Project
Prasyarat Instalasi
Python 3.x: Pastikan Anda memiliki Python 3 terinstal.

Dataset: Siapkan file data masukan dengan nama dataset penelitian.csv di direktori project. File ini harus memiliki kolom yang berisi teks berita yang akan dianalisis (sesuai yang digunakan dalam notebook, diasumsikan bernama Interpretasi singkat).

🌳 Susunan Project
Struktur utama project ini adalah sebagai berikut:

.
├── final project ML.ipynb          # Notebook utama (Jupyter/Colab) berisi seluruh alur kerja.
├── dataset penelitian.csv          # File CSV input (dataset berita awal).
├── berita_cleaned.csv              # Output: Dataset setelah proses pembersihan teks.
├── berita_prabowo_labeled.csv      # Output: Dataset setelah pelabelan sentimen berbasis leksikon.
├── train_dataset.csv               # Output: Data training untuk model IndoBERT.
├── test_dataset.csv                # Output: Data testing untuk model IndoBERT.
└── indobert_finetuned/             # Direktori output: Menyimpan model dan tokenizer IndoBERT hasil fine-tuning.
🏃 Contoh Penggunaan
Kloning Repositori
Bash

git clone [https://github.com/USERNAME/REPO_NAME.git](https://github.com/USERNAME/REPO_NAME.git)
cd REPO_NAME
Siapkan Data
Pastikan file dataset penelitian.csv ada di direktori project.

Jalankan Analisis
Buka final project ML.ipynb di lingkungan Jupyter (seperti Google Colab atau Jupyter Notebook lokal).

Jalankan setiap sel secara berurutan.

Notebook ini akan memproses data dari awal hingga menghasilkan model IndoBERT yang terlatih dan visualisasi analisis sentimen bulanan.

Contoh langkah yang akan dieksekusi oleh notebook:

Membaca dataset penelitian.csv.

Membersihkan teks dan menghasilkan berita_cleaned.csv.

Pelabelan sentimen dan menghasilkan berita_prabowo_labeled.csv.

Memuat model IndoBERT, melakukan fine-tuning, dan menyimpan hasilnya di indobert_finetuned/.

Menampilkan grafik perbandingan jumlah fitur klasik dan tren sentimen per bulan.

🤝 Kontribusi
Kami menyambut kontribusi dari komunitas! Jika Anda ingin berkontribusi, silakan ikuti langkah-langkah berikut:

Fork repositori ini.

Buat cabang baru untuk fitur Anda (git checkout -b feature/AmazingFeature).

Lakukan perubahan dan commit (git commit -m 'Add AmazingFeature').

Push ke cabang Anda (git push origin feature/AmazingFeature).

Buka Pull Request (PR).

📄 Lisensi
Project ini dilisensikan di bawah Lisensi MIT.

MIT License

Copyright (c) [Tahun] [Nama atau Organisasi Anda]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
