# SOFTWARE REQUIREMENTS SPECIFICATION (SRS)
## ACADORA (Academic Operations & Data Resource Application)

---

## 1. Pendahuluan

### 1.1 Latar Belakang
Perkembangan teknologi informasi mendorong digitalisasi layanan akademik di perguruan tinggi. Namun, masih banyak proses akademik seperti pengisian KRS, evaluasi dosen, dan konsultasi akademik yang belum terintegrasi dalam satu sistem. Hal ini menyebabkan inefisiensi, keterlambatan informasi, dan kurang optimalnya interaksi antara mahasiswa dan pihak akademik.

ACADORA dikembangkan sebagai solusi berbasis web untuk mengintegrasikan layanan akademik dalam satu platform yang efektif dan efisien.

---

### 1.2 Tujuan Sistem
- Menyediakan sistem layanan akademik terintegrasi
- Mempermudah pengelolaan aktivitas akademik
- Meningkatkan efisiensi dan akurasi data akademik
- Memfasilitasi interaksi antara mahasiswa, dosen, dan admin

---

### 1.3 Ruang Lingkup
Sistem ACADORA mencakup:
- Pengisian KRS
- Evaluasi dosen (EDOM)
- Konsultasi akademik
- Pengajuan revisi nilai
- Akses hasil akademik

---

## 2. Stakeholder

| Stakeholder        | Deskripsi |
|-------------------|----------|
| Mahasiswa         | Pengguna utama untuk mengakses layanan akademik |
| Dosen             | Memberikan bimbingan dan melihat evaluasi |
| Admin Akademik    | Mengelola data dan sistem |

---

## 3. Kebutuhan Fungsional

### 3.1 Mahasiswa
- Login ke sistem
- Mengisi KRS
- Melihat hasil/nilai akademik
- Mengisi evaluasi dosen (EDOM)
- Melakukan konsultasi akademik
- Mengajukan revisi nilai

### 3.2 Dosen
- Login ke sistem
- Melihat data mahasiswa bimbingan
- Memberikan konsultasi akademik
- Melihat hasil evaluasi dosen

### 3.3 Admin
- Mengelola data mahasiswa
- Mengelola data dosen
- Mengelola mata kuliah
- Mengelola data KRS
- Mengelola nilai akademik

---

## 4. Kebutuhan Non-Fungsional

- Sistem berbasis web dan dapat diakses melalui browser
- Waktu respon sistem maksimal 3 detik
- Sistem memiliki keamanan login (autentikasi user)
- Data tersimpan dengan aman dalam database
- Tampilan user-friendly dan mudah digunakan
- Sistem dapat diakses 24/7

---

## 5. Use Case (Deskripsi Singkat)

| Aktor      | Use Case |
|-----------|--------|
| Mahasiswa | Login |
| Mahasiswa | Isi KRS |
| Mahasiswa | Lihat Nilai |
| Mahasiswa | Isi EDOM |
| Mahasiswa | Ajukan Revisi Nilai |
| Dosen     | Bimbingan Akademik |
| Dosen     | Lihat Evaluasi |
| Admin     | Kelola Data Akademik |

---

## 6. Alur Sistem (Contoh: Pengisian KRS)

1. Mahasiswa login ke sistem
2. Sistem menampilkan daftar mata kuliah
3. Mahasiswa memilih mata kuliah
4. Mahasiswa menyimpan KRS
5. Sistem menyimpan data ke database
6. Dosen melakukan validasi (opsional)

---

## 7. Kebutuhan Data (Draft)

### Entitas:
- Mahasiswa (NIM, Nama, Jurusan)
- Dosen (NIDN, Nama)
- Mata Kuliah (Kode, Nama, SKS)
- KRS
- Nilai
- EDOM

---

## 8. Penutup
Dokumen ini menjadi dasar dalam pengembangan sistem ACADORA. Seluruh kebutuhan yang telah dianalisis akan digunakan sebagai acuan dalam tahap perancangan, pengembangan, dan pengujian sistem.
