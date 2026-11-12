# Dataset Putusan Pengadilan Pidana Khusus Narkotika & Psikotropika (PN Palopo)

![Domain](https://img.shields.io/badge/Domain-Legal%20Information%20Retrieval-1f4e78?style=for-the-badge)
![Court](https://img.shields.io/badge/Lembaga_Peradilan-PN_Palopo-2e7d32?style=for-the-badge)
![Documents](https://img.shields.io/badge/Jumlah_Dokumen-50_Putusan_PDF-d32f2f?style=for-the-badge)
![License](https://img.shields.io/badge/Sifat_Dokumen-Terbuka_(Public_Domain)-f57c00?style=for-the-badge)

Repositori ini berisi dataset akuisisi, ringkasan metadata, dan ekstraksi informasi dari **50 dokumen Putusan Pengadilan Negeri Palopo (`PN Plp`)** pada direktori **Pidana Khusus** dengan klasifikasi **Narkotika dan Psikotropika** yang bersumber dari [Direktori Putusan Mahkamah Agung Republik Indonesia](https://putusan3.mahkamahagung.go.id/direktori.html).

Dataset ini disusun untuk memenuhi **Penugasan Ujian Tengah Semester (UTS) Mata Kuliah Temu Kembali Informasi (Information Retrieval)** Semester Ganjil 2026/2027, Fakultas Teknik, Universitas Muhammadiyah Malang.

---

## 👥 Tim Penyusun
| No | Nama Mahasiswa | NIM |
| :-: | :--- | :--- |
| 1 | **Muhammad Nabil Farras Sulthan** | `202310370311259` |
| 2 | **Aglifah Alfarabi Basri** | `202310370311255` |

---

## 📂 Struktur Direktori Repositori
Sesuai dengan spesifikasi pengelolaan dataset Temu Kembali Informasi, repositori ini memiliki susunan direktori sebagai berikut:

```text
Dataset-Narkotika_259_255/
├── Dataset/
│   └── Narkotika.zip        # Arsip ZIP berisi 50 dokumen putusan pengadilan (*.pdf)
├── Overview/
│   └── Overview.xlsx        # Ringkasan terstruktur 50 data putusan (Barang Bukti & Amar Putusan)
└── README.md                # Dokumentasi lengkap dataset
```

---

## 📊 Karakteristik & Statistik Dataset
- **Sumber Akuisisi:** Direktori Putusan Mahkamah Agung RI (`https://putusan3.mahkamahagung.go.id`)
- **Klasifikasi Perkara:** Pidana Khusus — Narkotika dan Psikotropika
- **Lembaga Peradilan:** Pengadilan Negeri Palopo (`PN Plp`)
- **Total Dokumen:** 50 Dokumen Putusan (`*.pdf`)
- **Rata-rata Panjang Dokumen:** 22.0 halaman per putusan (Total 1099 halaman)
- **Status Putusan:** Non-BHT (Tidak menggunakan putusan berstatus Berkekuatan Hukum Tetap sesuai ketentuan penugasan)

---

## 📑 Struktur Kolom pada `Overview/Overview.xlsx`
File `Overview.xlsx` memuat ekstraksi informasi setiap dokumen putusan dengan struktur atribut berikut:

| Nama Kolom | Deskripsi |
| :--- | :--- |
| **`No`** | Nomor urut dokumen putusan (`1` s/d `50`). |
| **`No Putusan`** | Nomor registrasi perkara resmi pada Pengadilan Negeri Palopo (contoh: `100/Pid.Sus/2025/PN Plp`). |
| **`Lembaga Peradilan`** | Nama satuan kerja pengadilan tingkat pertama yang memeriksa dan memutus perkara (`PN Palopo`). |
| **`Barang Bukti`** | Rincian barang bukti narkotika (sabu/metamfetamina, berat netto/kotor, alat hisap/bong, handphone, timbangan digital, dll.) yang disita dalam perkara. |
| **`Amar Putusan`** | Isi lengkap diktum `MENGADILI:` yang dijatuhkan oleh Majelis Hakim (pernyataan terbukti bersalah, kualifikasi tindak pidana, lama pidana penjara, pidana denda & subsider, status barang bukti, dan biaya perkara). |

> **Catatan Tambahan:** Pada *sheet* kedua di dalam `Overview.xlsx` (`Detail Lengkap (Bonus)`), disertakan pula hasil ekstraksi mendalam meliputi **Nama Terdakwa**, **Identitas Lengkap Terdakwa**, **Tuntutan Jaksa Penuntut Umum (JPU)**, **Pasal yang Terbukti**, **Lama Pidana Penjara**, **Besaran Denda**, **Tanggal Putusan**, serta **Nama Hakim Ketua**.

---

## 🔍 Contoh Sampel Data Putusan
| No | No Putusan | Lembaga Peradilan | Nama Terdakwa | Vonis Penjara |
| :-: | :--- | :--- | :--- | :--- |
| 1 | `100/Pid.Sus/2025/PN Plp` | PN Palopo | SUDIRMAN Alias IMMANG Bin PUJI | 8 (delapan) tahun dikurangkan masa penangkapan dan masa penahanan terdakwa dengan perintah terdakwa tetap ditahan |
| 2 | `107/Pid.Sus/2025/PN Plp` | PN Palopo | Hartono Alias Tono Alias Bapak Tia Bin Muh. | 11 (Sebelas) tahun dikurangkan selama terdakwa berada dalam tahanan |
| 3 | `108/Pid.Sus/2025/PN Plp` | PN Palopo | Dewi Sartika Alias Dewi Binti Muslimin Abu | 10 (Sepuluh) Tahun dikurangkan selama terdakwa ditahan dengan perintah agar terdakwa tetap ditahan |
| 4 | `109/Pid.Sus/2025/PN Plp` | PN Palopo | Satriawan Alias Wawan Bin Hamzah | 10 (Sepuluh) Tahun dikurangkan selama terdakwa ditahan dengan perintah agar terdakwa tetap ditahan |
| 5 | `110/Pid.Sus/2025/PN Plp` | PN Palopo | Rafli Darwin Alias Appi Bin Darwin | 10 (Sepuluh) Tahun dikurangkan selama terdakwa ditahan dengan perintah agar terdakwa tetap ditahan |

---
## 📜 Lisensi & Keterbukaan Informasi
Berdasarkan Undang-Undang Nomor 14 Tahun 2008 tentang Keterbukaan Informasi Publik dan SK Ketua Mahkamah Agung RI Nomor 1-144/KMA/SK/I/2011, dokumen putusan pengadilan bersifat terbuka dan tidak terikat Hak atas Kekayaan Intelektual (HaKI), sehingga dapat dimanfaatkan untuk kepentingan penelitian dan pengembangan sistem **Temu Kembali Informasi Hukum (Legal Information Retrieval)**.
