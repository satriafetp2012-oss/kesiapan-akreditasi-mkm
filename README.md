# Kesiapan Akreditasi MKM 2028

Dashboard persiapan akreditasi LAM-PTKes (instrumen kualitatif pengajuan status **Unggul**, Magister Kesehatan Masyarakat, INS-KU-KM-M-24-044-01, 27 Maret 2025) dengan target pengajuan LED melalui SIMAk pada akhir 2027.

## Isi

| Tab | Fungsi |
|---|---|
| Ringkasan | Hitung mundur ke pengajuan, fase kerja, meter kesiapan, simulasi status (Buku II 3.4), kesiapan per kriteria |
| Kriteria & elemen | 8 kriteria, 26 sub-kriteria, 121 elemen; status M/MS/TM, PIC, catatan, bukti terkait |
| Daftar persiapan | 60 dokumen bukti, 38 tabel data dukung, 25 komponen LED, 9 persiapan asesmen lapangan, daftar resmi LAM-PTKes; ekspor Excel |
| Contoh dokumen | 60 templat dokumen bukti; unduh kerangka `.docx` |
| Unggah & petakan | Baca PDF/DOCX/XLSX/CSV/PPTX/TXT di peramban dan petakan ke elemen serta kode bukti |
| Linimasa | 6 fase dan 19 tonggak Oktober 2026 – Juni 2028 |
| Isi folder | Inventaris berkas folder akreditasi (per 14 Oktober 2026) |

## Cara pakai

Buka `index.html` (atau alamat GitHub Pages). Semua berjalan di peramban; tidak ada server.

- **Penyimpanan**: status yang diisi tersimpan di peramban masing-masing (localStorage). Untuk berbagi progres, pakai **Ekspor data (.json)** lalu rekan tim memakai **Impor data**.
- **Pembacaan dokumen**: berkas tidak dikirim ke mana pun; teks diekstrak di peramban dengan pdf.js, mammoth, SheetJS, dan JSZip (dimuat dari jsDelivr saat dibutuhkan). PDF hasil pindai perlu OCR terlebih dahulu.
- **Analisis Claude** dan basis data bersama hanya tersedia pada versi artifact di claude.ai.

## Deploy ke GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → Branch `main`, folder `/ (root)`.
