# Tugas Analisis 1 - Transformer dan Self-Attention

Paket ini berisi laporan, skrip praktikum yang disesuaikan dengan kalimat Bahasa Indonesia, dan hasil visualisasi Attention Heatmap.

## Isi paket

- `Laporan_Tugas_Analisis_1_Transformer.pdf` - laporan analisis maksimal 3 halaman.
- `lab_pekan_05_transformer_self_attention.py` - skrip Python yang sudah diubah.
- `attention_heatmap_pekan_05.png` - heatmap hasil eksekusi skrip.
- `requirements.txt` - pustaka Python yang dibutuhkan.

## Cara menjalankan

1. Pastikan Python terpasang.
2. Instal pustaka dengan perintah:

   ```bash
   pip install -r requirements.txt
   ```

3. Jalankan skrip:

   ```bash
   python lab_pekan_05_transformer_self_attention.py
   ```

4. Skrip akan menampilkan hasil perhitungan dan menyimpan `attention_heatmap_pekan_05.png` di folder kerja saat skrip dijalankan.

## Kalimat uji

> Hewan itu tidak menyeberangi jalan karena ia kelelahan.

Kalimat terdiri dari 8 token. Dalam simulasi, baris query `ia` memberi bobot perhatian tertinggi pada key `Hewan` sebesar 29,0%.

**Catatan metodologis:** embedding pada latihan ini dibuat secara acak dan bias hubungan konteks dimasukkan secara manual. Karena itu, heatmap adalah ilustrasi mekanisme perhitungan Self-Attention, bukan keluaran model bahasa yang telah dilatih.

## Pengumpulan GitHub

Repositori GitHub belum dibuat atau diunggah dari sini. Untuk memenuhi bagian tautan repositori pada LMS, unggah file-file paket ini ke repositori milik Anda lalu salin URL repositori tersebut ke LMS. Sebelum mengumpulkan PDF, isi kolom Nama dan NIM pada halaman pertama.
