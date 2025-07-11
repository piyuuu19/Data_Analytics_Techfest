# 📊 Analisis Data Eksplorasi (EDA): Efektivitas Penyaluran Dana TKDD dan Dampaknya pada IPM Provinsi di Indonesia Tahun 2023

## 📁 Ringkasan Proyek

Proyek ini bertujuan untuk menganalisis hubungan antara alokasi dana **Transfer ke Daerah dan Dana Desa (TKDD)**, realisasinya, dan dampaknya terhadap kualitas hidup masyarakat di berbagai provinsi di Indonesia. Fokus utama analisis adalah korelasi antara penyerapan dana dan **Indeks Pembangunan Manusia (IPM)** tahun 2023 sebagai indikator kesejahteraan masyarakat.

---

## 📌 Informasi Proyek

- **Kompetisi:** TECHFEST Data Analytics Competition 2025  
- **Anggota Tim:** Azzrial Arfiansyah, Ilham Rizky Ramadhan  
- **Universitas:** UPN Veteran Jakarta

---

## 📂 Latar Belakang

Setiap tahunnya, pemerintah pusat mengalokasikan anggaran melalui TKDD guna mempercepat pembangunan daerah. Meskipun dana yang dialokasikan cukup besar, tidak semua provinsi dapat menyerap anggaran tersebut secara optimal. Studi ini bertujuan mengevaluasi efektivitas penyerapan dana dan dampaknya terhadap kesejahteraan masyarakat melalui analisis IPM.

---

## ❓ Rumusan Masalah

Analisis ini berupaya menjawab pertanyaan berikut:
- Bagaimana perbandingan antara pagu dan realisasi TKDD di setiap provinsi?
- Provinsi mana yang memiliki tingkat realisasi tertinggi dan terendah?
- Faktor-faktor apa saja yang memengaruhi realisasi TKDD?
- Adakah hubungan antara realisasi TKDD dengan IPM?
- Apa faktor-faktor utama yang memengaruhi IPM pada tahun 2023?

---

## 📊 Dataset

**Sumber:** Dataset Lomba Data Analytics TECHFEST 2025 (tersedia di file terlampir)

Variabel penting dalam dataset:
- Provinsi
- Indeks Pembangunan Manusia (IPM)
- Pagu TKDD
- Realisasi TKDD
- Jumlah Penduduk
- APBN per Kapita
- Persentase Penduduk Miskin
- PDRB
- Indikator ekonomi dan sosial lainnya

---

## 🔍 Metodologi Analisis

1. **Pembersihan & Persiapan Data**
   - Menghapus simbol mata uang, mengubah tipe data.
   - Menangani missing value (terutama dari DOB/Daerah Otonomi Baru).
   - Outlier tidak dihapus agar tetap mencerminkan realitas data.

2. **Rekayasa Fitur**
   - Persentase Realisasi: Mengukur efektivitas penggunaan anggaran.
   - Kategori Realisasi: Dikategorikan untuk kebutuhan visualisasi dan klasifikasi.

3. **EDA dan Visualisasi**
   - **Univariat:** Distribusi dan ringkasan variabel.
   - **Bivariat:** Korelasi antar 2 variabel seperti Realisasi vs IPM.
   - **Multivariat:** Heatmap dan scatter matrix untuk eksplorasi mendalam.

---

## 📚 Library yang Digunakan

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

## ▶️ Cara Menjalankan Notebook

### 🔸 Opsi 1: Jalankan di Google Colab (disarankan)
1. Buka [Google Colab](https://colab.research.google.com)
2. Klik **"Upload"**, lalu pilih file `EDA_ayambumbuhitam_UPNVeteranJakarta.ipynb`
3. Jalankan setiap sel sesuai urutan

### 🔸 Opsi 2: Jalankan secara lokal
1. Pastikan Python sudah terinstal di komputer kamu
2. Buka terminal dan jalankan:
   ```bash
   pip install notebook pandas numpy matplotlib seaborn
3. Lalu buka notebook:
   ```bash
    jupyter notebook
4. Buka file EDA_ayambumbuhitam_UPNVeteranJakarta.ipynb melalui browser
