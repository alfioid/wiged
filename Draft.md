# Draft Spesifikasi Kebutuhan Perangkat Lunak (SRS)
**Nama Proyek:** Sistem Manajemen Inventaris  
**Tanggal:** 9 Oktober 2026  

---

## 1. Pendahuluan
Dokumen ini memuat draf awal kebutuhan sistem untuk mengelola data barang dan pencatatan transaksi toko/inventaris.

---

## 2. Kebutuhan Fungsional (Functional Requirements)

| ID Kebutuhan | Deskripsi Kebutuhan | Hak Akses (Aktor) |
| :--- | :--- | :--- |
| **FR-001** | Sistem dapat melakukan otentikasi login pengguna (Admin/Kasir). | Admin, Kasir |
| **FR-002** | Admin dapat menambah, mengubah, melihat, dan menghapus data barang (CRUD). | Admin |
| **FR-003** | Sistem dapat menampilkan stok barang secara *real-time*. | Admin, Kasir |
| **FR-004** | Kasir dapat mencatat transaksi penjualan barang. | Kasir |
| **FR-005** | Sistem dapat merekam riwayat transaksi dan mencetak bukti penjualan/struk. | Kasir |

---

## 3. Kebutuhan Non-Fungsional (Non-Functional Requirements)

| ID Kebutuhan | Kategori | Deskripsi Kebutuhan |
| :--- | :--- | :--- |
| **NFR-001** | *Usability* | Antarmuka sistem responsif dan mudah digunakan oleh pengguna awam. |
| **NFR-002** | *Performance* | Waktu pemrosesan transaksi tidak melebihi 2 detik. |
| **NFR-003** | *Security* | Password pengguna tersimpan dalam bentuk *hash* terenkripsi (misal: bcrypt). |