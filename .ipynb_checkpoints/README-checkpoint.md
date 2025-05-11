# Hadoop Log Analysis

Analisis log sistem Hadoop untuk mengekstrak insight operasional, mendeteksi anomali, dan mengoptimalkan kinerja sistem distribusi berbasis Hadoop.

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk:

* Mengekstrak informasi penting dari log Hadoop.
* Mengidentifikasi anomali atau error yang sering terjadi.
* Menyediakan visualisasi dan statistik untuk membantu analisis performa dan stabilitas.

## 📂 Sumber Data

Menggunakan dataset dari repositori publik:

* GitHub: [logpai/loghub](https://github.com/logpai/loghub)
* Dataset: `Hadoop` log (tersedia dalam format teks)

## ⚙️ Teknologi yang Digunakan

* Python 3.10+
* Pandas & NumPy
* Regex / Log Parsing
* Matplotlib / Seaborn / Plotly (visualisasi)
* Scikit-learn (analisis/anomali)
* LogParser Toolkit (opsional)

## 🏗️ Struktur Proyek

```
├── data/
│   └── hadoop_logs/           # Folder log Hadoop mentah
├── notebooks/
│   └── exploratory_analysis.ipynb
├── src/
│   ├── preprocess.py          # Pembersihan dan parsing log
│   ├── analysis.py            # Statistik dan deteksi anomali
│   └── visualize.py           # Pembuatan grafik dan chart
├── README.md
└── requirements.txt
```

## 🚀 Langkah Eksekusi

```bash
# Clone repositori
$ git clone https://github.com/namauser/hadoop-log-analysis.git
$ cd hadoop-log-analysis

# Install dependensi
$ pip install -r requirements.txt

# Jalankan analisis
$ python src/preprocess.py
$ python src/analysis.py
```

## ✅ Output

* Statistik jumlah error, warning, dan event per waktu.
* Visualisasi frekuensi event.
* Deteksi anomali log.
* Ringkasan top N event dominan dan error.

## 📊 Contoh Visualisasi

* Histogram frekuensi error
* Heatmap korelasi event antar komponen
* Timeline error & warning

## 🧪 Dataset & Format Log

```
<DATE> <TIME> <LEVEL> <COMPONENT>: <MESSAGE>
Example:
2009-07-20 03:59:57,796 INFO org.apache.hadoop.hdfs.server.datanode.DataNode: Receiving block blk_-5627252809418057504
```

## 📎 Referensi

* [Loghub Dataset](https://github.com/logpai/loghub)
* [LogParser Toolkit](https://github.com/logpai/logparser)

## 📬 Kontribusi

Pull request dan issue dipersilakan! Pastikan format log konsisten dan dokumentasi jelas.

---

**Lisensi:** MIT

**Author:** @namapengguna

