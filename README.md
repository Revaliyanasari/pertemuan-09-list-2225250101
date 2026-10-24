# Pertemuan 09 - List dan Pengolahan Data Numerik

**Nama:** Reva Liyanasari  
**NIM:** 2225250101  
**Kelas:** 3A  
**Mata Kuliah:** Algoritma dan Pemrograman  
**Dosen Pengampu:** Dr. Aan Hendrayana, S.Si., M.Pd.

## Tujuan

Mempelajari penggunaan list Python untuk menyimpan, mengakses, memodifikasi, dan mengolah data numerik sederhana.

## Struktur Program

```text
pertemuan-09-list-NIM/
├── latihan/
│   ├── 01_buat_list.py
│   ├── 02_indeks_slicing.py
│   ├── 03_manipulasi_list.py
│   ├── 04_agregasi_nilai.py
│   ├── 05_filter_kelulusan.py
│   └── 06_fungsi_statistik.py
├── praktik/
│   └── analisis_nilai_mahasiswa.py
└── README.md
```

## Deskripsi Program

- **Latihan 1:** Membuat list dan menghitung jumlah elemen.
- **Latihan 2:** Mengakses elemen menggunakan indeks dan slicing.
- **Latihan 3:** Mengubah, menambahkan, menyisipkan, dan menghapus elemen list.
- **Latihan 4:** Menghitung total, rata-rata, nilai minimum, dan maksimum.
- **Latihan 5:** Menyaring nilai mahasiswa yang memenuhi batas kelulusan.
- **Latihan 6:** Membuat fungsi untuk menghitung rata-rata.
- **Praktik:** Menganalisis nilai mahasiswa menggunakan list, perulangan, seleksi, dan fungsi.

## Cara Menjalankan

Jalankan program melalui terminal VS Code dengan perintah:

```bash
python latihan/01_buat_list.py
```

Untuk menjalankan program praktik:

```bash
python praktik/analisis_nilai_mahasiswa.py
```

## Test Case

| Data | Proses yang Diuji | Hasil yang Diharapkan |
|---|---|---|
| `[75, 80, 65, 90, 88]` | Menghitung jumlah data | 5 |
| `[60, 70, 80]` | Menghitung rata-rata | 70.00 |
| `[60, 70, 80]` | Minimum dan maksimum | 60 dan 80 |
| `[59, 60, 61]` | Menentukan nilai lulus | 2 nilai lulus |
| `[]` | Menghitung rata-rata list kosong | Tidak menghasilkan error pada fungsi `rata_rata()` |

## Refleksi

Melalui praktikum ini, saya mempelajari bahwa list dapat menyimpan banyak data dalam satu variabel. Saya juga memahami penggunaan indeks, slicing, serta operasi untuk mengubah dan mengolah elemen list. Selain itu, penggunaan perulangan dan fungsi membantu proses pengolahan data menjadi lebih terstruktur.

## Referensi dan Bantuan

- Bahan Ajar Pertemuan 09: *List/Array dan Pengolahan Data Numerik Sederhana*.
- Dokumentasi Python: https://docs.python.org/3/tutorial/datastructures.html