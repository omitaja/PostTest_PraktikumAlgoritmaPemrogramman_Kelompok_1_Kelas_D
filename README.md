📊 Post Test & Prajilid — Praktikum Algoritma Pemrograman 2026

Visualisasi Data Kebahagiaan Dunia menggunakan Python (Pandas, Matplotlib, Seaborn)


👥 Anggota Kelompok 1
Faisal Al Hafiz Siregar (21060125130071)
Nabila Nur Fitri Arifin (21060125140164)
Nisrina Najwa Luthfiyyah (21060125130118)
Timoty Turnip (21060125130125)
Vimoty Turnip (21060125140137)


📋 Pembagian Tugas Detail
🔵 Vimo — Soal A (Kategori Agregasi)
Pengolahan Data:

Menghitung rata-rata kepuasan hidup (adjusted_satisfaction, skala 0–100) berdasarkan wilayah regional (Region)
Visualisasi menggunakan Horizontal Bar Chart dengan pendekatan ax=axes[0, 0]

Infografis:

Membuat desain layout infografis Grafik A
Menyusun insight/kesimpulan singkat hasil analisis agregasi

PPT:

Membuat slide presentasi bagian analisis Grafik A


🟠 Timo — Soal B (Kategori Tren/Filter) + Kelola GitHub
Pengolahan Data:

Menemukan negara di wilayah Sub-Saharan Africa yang memiliki skor kepuasan di atas nilai median wilayah tersebut
Visualisasi menggunakan Bar Chart dengan pendekatan ax=axes[0, 1]

Infografis:

Membuat desain layout infografis Grafik B
Menyusun insight/kesimpulan singkat hasil analisis tren/filter

PPT:

Membuat slide presentasi bagian analisis Grafik B

GitHub (Kelola Repository):

Membuat dan mengelola repository kelompok
Meng-upload source code .ipynb, dataset, dan file pendukung
Memastikan struktur repository rapi dan lengkap
Mencantumkan rincian jobdesk seluruh anggota


🩷 Nabila — Soal C (Kategori Korelasi)
Pengolahan Data:

Menganalisis hubungan korelasi antara skor kebahagiaan (Happy Score, skala 0–10) dengan tingkat GDP negara
Visualisasi menggunakan Scatter Plot dengan pendekatan ax=axes[1, 0]

Infografis:

Membuat desain layout infografis Grafik C
Menyusun insight/kesimpulan singkat hasil analisis korelasi

PPT:

Membuat slide presentasi bagian analisis Grafik C


🟡 Nisrina — Soal D (Kategori Distribusi)
Pengolahan Data:

Mencari sebaran dan pencilan pada kolom ketimpangan pendapatan (income_inequality)
Visualisasi menggunakan Boxplot dengan pendekatan ax=axes[1, 1]

Infografis:

Membuat desain layout infografis Grafik D
Menyusun insight/kesimpulan singkat hasil analisis distribusi

PPT:

Membuat slide presentasi bagian analisis Grafik D


🟢 Faisal — Soal E (Grafik Gabungan) + Koordinasi Infografis & PPT
Pengolahan Data:

Menggabungkan Grafik A, B, C, dan D ke dalam satu layout grid 2×2 menggunakan plt.subplots(2, 2, figsize=(...))
Menggunakan pendekatan ax=axes[x, y] agar grafik individu dapat digabungkan tanpa menulis ulang logika data

Infografis:

Mengintegrasikan desain infografis Grafik A–D dari seluruh anggota menjadi satu infografis utuh yang estetis dan profesional

PPT:

Membuat slide cover, intro kelompok, dan slide penutup/kesimpulan keseluruhan


🤝 Tugas Bersama (Semua Anggota)

 Publikasi infografis ke Instagram Story (rasio 9:16) masing-masing akun dengan tag/mention pihak terkait
 Publikasi ke LinkedIn (rasio 1:1 / 4:5 atau format PDF Slider) masing-masing akun dengan tag/mention pihak terkait
 Mengisi formulir absensi yang telah disediakan


🗂️ Struktur Repository
📁 repository
├── 📄 README.md
├── 📄 dataset.csv
└── 📓 posttest_kelompok1.ipynb
└── 📄 PPT
└── 📄 Infografis

⚙️ Library yang Digunakan
pythonimport pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns


📌 Ketentuan Teknis

Format file pengumpulan: .ipynb (Jupyter Notebook)
Setiap grafik wajib disertai insight/kesimpulan singkat yang edukatif dan mudah dipahami audiens awam
Semua kode visualisasi menggunakan pendekatan objek ax=axes[x, y]
Visualisasi tidak boleh hanya menampilkan grafik mentah tanpa analisis
