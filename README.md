---

# 📚 Sistem Peminjaman Buku — Project Basis Data

Repositori ini berisi kumpulan file SQL untuk menyelesaikan tugas mata kuliah **Basis Data**.
Proyek ini mencakup pembuatan database, pembuatan tabel, pengisian data, serta latihan mengeksekusi query menggunakan **MySQL/MariaDB** melalui **CMD**.

---

## 📁 Struktur Folder

| Folder           | Keterangan                                                  |
| ---------------- | ----------------------------------------------------------- |
| `pembuatan-db/`  | Berisi script `CREATE DATABASE` dan tabel                   |
| `insert-data/`   | Berisi query `INSERT` untuk mengisi data awal               |
| `latihan-query/` | Berisi latihan query seperti `WHERE`, `BETWEEN`, dan `JOIN` |

---

## 🧾 Detail Database

**Nama database:** `tugas`
**Tabel yang digunakan:**

* `buku` → data buku (judul, pengarang, tahun, penerbit)
* `mahasiswa` → data peminjam (nama, NIM, alamat, jurusan)
* `peminjaman` → proses peminjaman buku oleh mahasiswa

Semua tabel saling terhubung melalui **foreign key**.

---

## 🔍 Materi yang Diimplementasikan

* Membuat database manual lewat CMD
* Membuat tabel dengan primary key & foreign key
* Memasukkan 15 data ke tiap tabel
* Menjalankan query:

  * `WHERE` (filter data)
  * `BETWEEN` (rentang tanggal/angka)
  * `JOIN` (menghubungkan tabel)

---

## 🎓 Tujuan

Proyek ini dibuat untuk:

* Memahami konsep dasar basis data relasional
* Membangun relasi antar tabel
* Melatih penulisan dan eksekusi query SQL
* Menerapkan langsung teori dalam praktikum

---

## 🛠️ Tools yang Digunakan

* **MySQL / MariaDB**
* **CMD (Command Prompt)**
* **XAMPP / Laragon** (opsional)
* **Notepad / VSCode** untuk menulis query

---

## 👤 Pembuat

**Alan Alvito Fahrurozy**
NIM **D0224525**
Mahasiswa **Universitas Sulawesi Barat**
Program Studi **Teknik Informatika**
*Proyek ini dibuat untuk memenuhi tugas mata kuliah Basis Data*
