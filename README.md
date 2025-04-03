# Analisis Sentimen X

Repositori ini berisi kode untuk melakukan analisis sentimen pada data komentar dari platform X (Twitter), menggunakan metode **Naive Bayes** atau **IndoBERT**.

## 🚀 Fitur
- **Scraping Data**: Mengambil data komentar dari X (Twitter), YouTube, dan Facebook.
- **Preprocessing**: Tokenisasi, stemming, normalisasi teks.
- **Analisis Sentimen**: Menggunakan **Naive Bayes** atau **IndoBERT**.
- **Analisis Polarisasi & Deteksi Buzzer**:
  - WordCloud
  - Network Analysis
- **Visualisasi Hasil**:
  - Bar Chart
  - Pie Chart
  - Timeline Analysis
  - Heatmap
  - Cluster Analysis

## 🛠 Instalasi
Pastikan kamu sudah menginstal **Python** dan pustaka yang dibutuhkan. Jalankan perintah berikut untuk menginstal dependensi:

```bash
pip install -r requirements.txt
```

Jika menggunakan Google Colab, tambahkan perintah berikut:
```python
!pip install nltk seaborn wordcloud requests beautifulsoup4 scikit-learn pandas matplotlib
```

## 📌 Cara Penggunaan
1. **Clone repositori**
   ```bash
   git clone https://github.com/aditrachman/analisa-sentimen-X.git
   cd analisa-sentimen-X
   ```
2. **Jalankan notebook atau script utama**
   - Untuk Google Colab, buka file `.ipynb`
   - Untuk Python script, jalankan:
     ```bash
     python index.py
     ```

3. **Scraping Data**
   - Pastikan sudah memiliki API Key (jika scraping dari X atau YouTube).
   - Jalankan fungsi scraping untuk mengumpulkan data komentar.

4. **Preprocessing**
   - Jalankan fungsi preprocessing untuk membersihkan data sebelum analisis sentimen.

5. **Analisis Sentimen**
   - Gunakan **Naive Bayes** atau **IndoBERT** untuk klasifikasi sentimen.

6. **Visualisasi Hasil**
   - Hasil analisis akan divisualisasikan dalam berbagai bentuk grafik.

## 📂 Struktur Folder
```
analisa-sentimen-X/
│── data/               # Folder untuk menyimpan dataset
│── models/             # Folder untuk menyimpan model yang sudah dilatih
│── notebooks/          # Notebook Jupyter untuk eksplorasi data
│── scripts/            # Script Python untuk scraping & analisis
│── requirements.txt    # Daftar pustaka yang diperlukan
│── README.md           # Dokumentasi ini
│── main.py             # Script utama untuk menjalankan analisis
```

## 📊 Contoh Output
![WordCloud](assets/wordcloud_example.png)

## 💡 Catatan
- Untuk scraping dari X (Twitter), YouTube, dan Facebook, pastikan memiliki API Key.
- Jika ingin menggunakan IndoBERT, pastikan model telah diunduh terlebih dahulu.

## 📜 Lisensi
Proyek ini menggunakan lisensi **MIT**.

---
Dibuat oleh [Tuan Adit](https://github.com/aditrachman) 
