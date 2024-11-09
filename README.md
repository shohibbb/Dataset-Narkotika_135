## Dataset Putusan Pengadilan Negeri Banjarbaru - Kasus Pidana Narkotika

![Logo contoh](https://www.google.com/url?sa=i&url=https%3A%2F%2Fpa-makassar.go.id%2Flayanan-publik%2Flayanan-informasi-perkara%2Fdirektori-putusan&psig=AOvVaw1fy5Z7geXxzRr7NnDncH6D&ust=1731216458975000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCNixq4PCzokDFQAAAAAdAAAAABAJ)

Dataset ini berisi 50 dokumen putusan pengadilan terkait kasus pidana khusus narkotika dan psikotropika dari Pengadilan Negeri Kota Banjarbaru. Data ini digunakan sebagai bahan praktikum untuk mata kuliah Temu Kembali Informasi, dengan tujuan mendukung pemahaman proses pengolahan dan pengindeksan teks hukum.

## Deskripsi Dataset

- Jumlah Dokumen: 50
- Jenis Kasus: Pidana Khusus (Narkotika dan Psikotropika)
- Sumber: Putusan Pengadilan Negeri Kota Banjarbaru

## Struktur Data

- Dataset terdiri dari beberapa fitur utama:
- no: Nomor urut dokumen dalam dataset
- no_putusan: Nomor putusan dalam format lengkap (misalnya, 125/Pid.Sus/2024/PN Bjb)
- lembaga_peradilan: Nama lembaga peradilan yang memutuskan kasus
- barang_bukti: Daftar barang bukti yang terkait dengan kasus
- amar_putusan: Amar putusan atau hasil putusan pengadilan, termasuk sanksi atau hukuman yang dijatuhkan

## Struktur Repository

- **dataset/Putusan pengadilan.zip**
- **overview/Overview.xlsx**

## Tujuan Penggunaan

Dataset ini difokuskan untuk mendukung proses:

- Preprocessing Teks: Mengolah data untuk mendapatkan teks bersih yang siap diindeks.
- Pengindeksan: Mengindeks dokumen untuk keperluan pencarian informasi berdasarkan kata kunci atau kata unik yang terdapat di dalam dokumen.

## Panduan Penggunaan

Anda dapat menggunakan dataset ini untuk keperluan praktikum, penelitian, atau eksplorasi metode dalam Information Retrieval dan Natural Language Processing. Sebelum memulai, pastikan Anda - telah menginstall pustaka yang diperlukan, Seperti `nltk`, `pandas`, dan `scikit-learn`.
