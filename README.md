## Dataset Putusan Pengadilan Negeri Banjarbaru - Kasus Pidana Narkotika

![Putusan Mahkamah Agung](https://drive.google.com/uc?export=view&id=1wmXF9DtznreZv6eMrr1o08r0G7II-tpz)

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

    .
    ├── Dataset
    |    └── Putusan Pengadilan.zip
    ├── Overview
    |    └── Overview.xlsx
    └── README.md

## Tujuan Penggunaan

Dataset ini difokuskan untuk mendukung proses:

- Preprocessing Teks: Mengolah data untuk mendapatkan teks bersih yang siap diindeks.
- Pengindeksan: Mengindeks dokumen untuk keperluan pencarian informasi berdasarkan kata kunci atau kata unik yang terdapat di dalam dokumen.

## Panduan Penggunaan

Anda dapat menggunakan dataset ini untuk keperluan praktikum, penelitian, atau eksplorasi metode dalam Information Retrieval dan Natural Language Processing. Sebelum memulai, pastikan Anda - telah menginstall pustaka yang diperlukan, Seperti `nltk`, `pandas`, dan `scikit-learn`.
