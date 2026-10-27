# Pertemuan 11 - Dictionary/Map

**Nama:** Ahmad Nurikhsan  
**NIM:** 2225250042  
**Kelas:** 3E

## Tujuan

Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value, mengakses data berdasarkan key, memanipulasi data, melakukan iterasi, serta menggunakan fungsi untuk mengolah data mahasiswa.

## Struktur Data

Program menggunakan dictionary `data_mahasiswa` dengan NIM sebagai key utama. Setiap value berupa dictionary yang berisi nama, kelas, dan nilai mahasiswa.

Contoh:

```python
"A001": {"nama": "Ayu", "kelas": "A", "nilai": 85}
```

## Struktur Folder

```text
pertemuan-11-dictionary-2225250042/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_dasar_dictionary.py
│   ├── 02_akses_get.py
│   ├── 03_manipulasi_dictionary.py
│   ├── 04_iterasi_dictionary.py
│   ├── 05_dictionary_bersarang.py
│   └── 06_fungsi_dictionary.py
└── praktik/
    └── data_mahasiswa.py
```

## Cara Menjalankan

Jalankan program praktik melalui terminal VS Code:

```bash
python praktik/data_mahasiswa.py
```

Jika perintah `python` tidak tersedia, coba:

```bash
py praktik/data_mahasiswa.py
```

## Test Case

| Kasus | Input/Aksi | Hasil yang Diharapkan |
|---|---|---|
| Pencarian tersedia | A003 | Data Citra ditampilkan |
| Pencarian tidak tersedia | A999 | Pesan "Data tidak ditemukan" |
| Pembaruan nilai | A002 menjadi 82 | Nilai A002 berubah menjadi 82 |
| Penambahan data | A006 | Key A006 tersedia setelah ditambahkan |
| Rekap | `items()` | Semua NIM dan data tampil |

## Refleksi

Kesalahan yang dapat terjadi saat menggunakan dictionary adalah mengakses key yang tidak tersedia sehingga menimbulkan `KeyError`. Kesalahan ini dapat dihindari dengan memeriksa key menggunakan operator `in` atau menggunakan method `get()` untuk akses yang lebih aman.
