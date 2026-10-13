# Tulis ulang isi README.md
Proyek Akuisisi dan Manajemen Data

- Mata Kuliah    :Data Acquisition & Management
- Program Studi  :Informatika - INSTIKI
- Nama Lengkap   :Si Ngurah Rai Krisna Pranajaya 
- NIM            :2501010375
- Kelas          : Kelas E

## Deskripsi Proyek
Repositori ini dibuat untuk memenuhi tugas dan dokumentasi praktikum Modul 01 mengenai Pengantar Data Acquisition & Management serta Penyiapan Environment. Seluruh tahapan pengerjaan proyek, mulai dari struktur direktori, pemetaan lifecycle, hingga dokumentasi kode, diatur secara sistematis di dalam repositori ini.

## Struktur Folder Proyek
- data/
  - raw/ : Berisi data mentah orisinal yang bersifat read-only.
  - interim/ : Berisi data dalam tahap transisi atau pembersihan sementara.
  - processed/ : Berisi data bersih yang siap digunakan untuk tahap analisis lebih lanjut.
- docs/ : Berisi dokumen pendukung proyek, termasuk tabel pemetaan data science lifecycle (lifecycle_mapping.csv).
- notebooks/ : Berisi file Jupyter Notebook / Google Colab tempat eksperimen dan praktikum dikerjakan.
- reports/ : Berisi laporan hasil analisis atau visualisasi data.
- src/ : Berisi skrip kode sumber modular (Python script).
- README.md : Dokumentasi utama proyek.

---

## Tugas 3: Reproducibility dalam Akuisisi Data

Reproducibility (kemampuan untuk mereproduksi atau menghasilkan ulang suatu analisis) memegang peranan penting di bidang akuisisi dan manajemen data. Hal ini dikarenakan proses pengambilan data sering kali melibatkan sumber eksternal yang dinamis seperti API publik atau situs web yang dapat berubah sewaktu-waktu. Dengan prinsip reproducibility, seluruh tahapan mulai dari URL sumber, skrip pengambilan, hingga kondisi lingkungan eksekusi tercatat secara sistematis di dalam repositori, sehingga peneliti lain maupun sistem otomatis dapat menjalankan ulang proses tersebut untuk memverifikasi keaslian data.

Sebagai contoh nyata, disebuah tim riset yang melakukan akuisisi data cuaca historis secara otomatis melalui API publik untuk memprediksi risiko bencana. Jika skrip pengambilan data tidak terdokumentasi dengan baik dan tidak reproducible, ketika terjadi anomali pada hasil prediksi, tim tidak dapat membuktikan apakah kesalahan berasal dari algoritma analisis atau dari perubahan format respons JSON pihak penyedia API di masa lalu. Hal ini akan berakibat fatal pada pengambilan keputusan darurat karena kredibilitas sumber data dipertanyakan dan tidak dapat divalidasi ulang.
