# Hadoop Log Analysis

Analisis log sistem Hadoop untuk mengekstrak insight operasional

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk:

* Mengekstrak informasi penting dari log Hadoop.
* Menyediakan visualisasi dan statistik untuk membantu analisis performa dan stabilitas.

## 📂 Sumber Data

Menggunakan dataset dari repositori publik:

* GitHub: [logpai/loghub](https://github.com/logpai/loghub)
* Dataset: `Hadoop mapreduce job` log (tersedia dalam format teks)

## ⚙️ Teknologi yang Digunakan

* Python 3.10+
* Pandas & NumPy
* Regex / Log Parsing
* Matplotlib  (visualisasi)


## 🏗️ Struktur Proyek

```
├── Dataset/
│   └── hadoop/           # Folder log Hadoop mentah
├── Pengolahan File Log Aktivitas Pengguna.ipynb
├── README.md
```

## 🚀 Langkah Eksekusi

```bash
# Clone repositori
$ git clone git@github.com:fikrirazor/Pengolahan-dan-Analisis-Log-Hadoop-untuk-Pemantauan-Kinerja-Sistem.git
$ cd Pengolahan-dan-Analisis-Log-Hadoop-untuk-Pemantauan-Kinerja-Sistem

## ✅ Output

* Statistik jumlah error, warning, dan event per waktu.
* Visualisasi aktivitas_per_hari
* aktivitas_level_per_hari
* jumlah_log_per_level
* aktivitas_log (opsional: rolling mean)


## 📊 Contoh Visualisasi


## 🧪 Dataset & Format Log

```
<DATE> <TIME> <LEVEL> <COMPONENT>: <MESSAGE>
Example:
2015-10-17 15:37:56,547 INFO [main] org.apache.hadoop.mapreduce.v2.app.MRAppMaster: Created MRAppMaster for application appattempt_1445062781478_0011_000001
```

## 📎 Referensi

* [Loghub Dataset](https://github.com/logpai/loghub)

## 📬 Kontribusi

---

**Lisensi:** MIT

**Author:** @fikrirazor

