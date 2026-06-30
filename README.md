# Dapoy BOS Releases
<div align="center">
  <img src="logo.png" alt="DAPOY BOS Logo" width="150" />
  
  # 🚀 DAPOY BOS
  **Asisten Virtual Terbaik untuk Bendahara Sekolah!**  
  *Sistem Informasi Rekapitulasi & Pelaporan Database ARKAS Berbasis Web Portable.*
  
  [![Version](https://img.shields.io/badge/version-2.0.8-blue.svg)](#)
  [![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](#)
</div>

---

## 📌 Apa itu DAPOY BOS?

**DAPOY BOS** adalah aplikasi *portable* tanpa instalasi rumit yang dirancang khusus untuk mempermudah pekerjaan Bendahara BOS. Aplikasi ini secara otomatis membaca dan mendekripsi database ARKAS kemudian menyajikannya dalam dashboard yang rapi, lengkap dengan fitur klasifikasi belanja, pencetakan dokumen (BAST, SPJ), dan ekspor data ke Excel/PDF.

Ucapkan selamat tinggal pada rekapitulasi BKU manual yang melelahkan! 👋📊

---

## ✨ Fitur Unggulan

Dapoy BOS dilengkapi dengan berbagai fitur otomatisasi pelaporan yang akan menghemat waktu Anda berjam-jam:

### 📊 1. Dashboard Real-Time
Pantau kondisi keuangan sekolah dalam satu layar interaktif:
- Ringkasan Pagu Anggaran, Realisasi Belanja, dan Sisa Saldo (Bank & Tunai).
- Persentase serapan anggaran.
- Grafik belanja bulanan dan grafik serapan per kategori.
- Grafik pengeluaran operasional (Listrik, Air, Internet, dll).

### 🗂️ 2. Klasifikasi BKU Otomatis (Auto-Rekap)
Data Buku Kas Umum (BKU) dari ARKAS otomatis dipilah menjadi kategori spesifik:
- 📦 **Barang Persediaan:** Rekap mutasi barang habis pakai (ATK, Kebersihan, Konsumsi).
- 🏢 **Barang Modal & Aset:** Filter otomatis untuk Peralatan/Mesin & Aset Tetap Lainnya.
- 🔧 **Biaya Pemeliharaan:** Rekap servis AC, pengecatan, perbaikan gedung, dan pemeliharaan inventaris lainnya.
- 🎓 **Pengembangan Profesi:** Analisis biaya Diklat, Workshop, dan Bimtek guru.
- 💸 **Honorarium:** Rekap pembayaran honor GTT/PTT, staf, atau pelatih ekskul.
- 🏆 **Biaya Lomba:** Rekap pengeluaran untuk pembinaan dan kompetisi kesiswaan.
- ⚡ **Daya & Jasa:** Rekapitulasi khusus untuk tagihan Listrik, PDAM, Internet, dan Telepon.

### 🖨️ 3. Fitur Cetak & Pelaporan Terlengkap
Urusan mencetak dokumen pendukung kini semudah klik tombol:
- **Cetak BAST Instan:** Hasilkan Berita Acara Serah Terima langsung dari rincian transaksi belanja persediaan/modal.
- **Cetak SPJ Honorarium:** Buat kuitansi dan SPJ honor secara otomatis dari data BKU.
- **Cetak Administrasi Lainnya:** Cetak Buku Mutasi Persediaan, Kartu Pemeliharaan, Absensi Ekskul, dan Surat Tugas langsung dari transaksi terkait.

### 📥 4. Pusat Download (Bulk Print Massal)
Fitur *magic* andalan Dapoy BOS! Butuh cetak BAST atau SPJ Honor untuk **satu bulan penuh**? Tidak perlu mencetak satu per satu. Gunakan menu Pusat Download, pilih bulan, dan sistem akan meng-generate seluruh dokumen secara massal dalam hitungan detik!

### ⚙️ 5. Dokumen Resmi Kustom (Pengaturan BAST)
Setiap dokumen yang dicetak dijamin resmi dan siap diarsipkan karena *template*-nya dapat Anda sesuaikan sendiri:
- Upload Logo Pemerintah Daerah & Logo Sekolah.
- Sesuaikan teks Kop Surat, Alamat, Kecamatan, Email, dan Telepon.
- Atur Nama & NIP Kepala Sekolah serta Pengurus Barang (Jabatan dapat disembunyikan / *Hide Officials* jika diperlukan untuk dashboard).

### 💾 6. Ekspor Data Fleksibel
Semua tabel rekapitulasi dilengkapi dengan fitur pencarian cepat, filter rentang bulan, pengaturan format tanggal, dan tombol **Export** ke:
- **Excel (.xlsx)** untuk diolah kembali (format tabel rapi).
- **PDF** untuk dokumen yang siap diprint.
- **CSV** untuk kebutuhan migrasi atau integrasi data sistem lain.

---

## 🚀 Quick Start Guide (Cara Penggunaan)

Aplikasi ini **100% Portable**. Tidak perlu instalasi XAMPP, database server, atau konfigurasi rumit lainnya.

1. **Jalankan Aplikasi:** 
   Buka folder aplikasi, lalu klik dua kali (Double-Click) pada file `DapoyBOS.exe`. 
   *(Catatan: Pastikan PC terhubung ke internet saat pertama kali login untuk proses verifikasi lisensi).*
2. **Akses Aplikasi:** 
   Aplikasi (jendela Dapoy BOS) akan otomatis terbuka. Jika ingin membuka juga di browser luar, Anda dapat mengakses `http://localhost:8005`.
3. **Login & Sinkronisasi:** 
   Gunakan **Email** dan **Password** akun ARKAS sekolah Anda.
4. **Selesai:** 
   Dapoy BOS akan memvalidasi akun, mendekripsi database ARKAS, dan menampilkan seluruh rekapitulasi sekolah Anda secara instan.

> **⚠️ Penting:** Pastikan aplikasi **ARKAS Desktop resmi sudah pernah terpasang dan login** di komputer yang sama, sehingga database ARKAS tersedia untuk dibaca oleh Dapoy BOS.

---

## 📂 Struktur Menu Dapoy BOS

- 🏠 **Dashboard**: Ringkasan visual performa keuangan sekolah.
- 📘 **Buku Kas Umum (BKU)**: Pusat data seluruh transaksi keuangan dengan filter tanggal, pencarian, dan opsi *toggle* pajak (PPN/PPh).
- 📊 **Rekapitulasi**: Menu pemecah transaksi ke berbagai pos (Persediaan, Modal, Pemeliharaan, Profesi, Lomba, Daya & Jasa, dan Honor).
- 🗓️ **Perencanaan**: Rencana Anggaran (RKAS) sesuai persetujuan di ARKAS dan Referensi Harga standar daerah.
- 👥 **Data Master**: 
  - **Guru & Tenaga (PTK)**: Menampilkan guru dari ARKAS, dengan kemampuan menambah PTK manual (*Custom*) dan mengatur visibilitas saat dicetak.
  - **Detail Toko**: Kelola database vendor, toko, atau rekanan belanja sekolah.
- ⚙️ **Pengaturan BAST**: Personalisasi Kop Surat, Logo, dan Pejabat penandatangan dokumen sekolah.
- 📥 **Pusat Download**: Menu sakti untuk unduh dan cetak dokumen administratif (BAST & SPJ Honor) secara massal (*Bulk Print*).

---

## 🛠️ Persyaratan Sistem & Troubleshooting

**Persyaratan:**
- OS: Windows (direkomendasikan Windows 10/11)
- ARKAS Desktop telah terinstal
- Koneksi Internet aktif (dibutuhkan saat login pertama kali untuk verifikasi kredensial lisensi aplikasi).

**Troubleshooting Singkat:**
- **Aplikasi tidak jalan:** Pastikan tidak ada antivirus yang memblokir, atau klik kanan pada file `DapoyBOS.exe` lalu pilih *Run as administrator*.
- **Login Gagal:** Pastikan penulisan Email & Password sudah sama persis dengan yang digunakan di ARKAS.
- **Data Tidak Tampil:** Pastikan login sukses. Jika data masih kosong, pastikan aplikasi ARKAS Desktop bisa dibuka normal dan databasenya belum dipindah/terhapus.
- **Browser Tidak Terbuka Otomatis:** Buka browser secara manual (Chrome/Edge/Firefox) dan ketikkan alamat: `http://localhost:8005`.

---

## 📝 Catatan Penting
- 🔒 **Keamanan Data Lokal:** Semua data diproses secara lokal di komputer Anda. Demi keamanan, jangan memindahkan, menghapus, atau mengubah file `dapoy.db`, maupun `license_cache.json` secara sembarangan.
- 💼 **Mode Trial:** Jika lisensi sekolah belum terdaftar penuh atau sudah kedaluwarsa, aplikasi dapat masuk ke *Mode Trial* di mana beberapa fitur pencetakan/unduhan (*download*) bisa dibatasi.
- 🛡️ **Cache Lisensi:** Aplikasi menyimpan cache lisensi lokal agar Anda tetap bisa login secara offline (jika sudah pernah login online sebelumnya). Namun, login online pertama kali adalah wajib.

---

<div align="center">
  <br>
  <b>Dikembangkan dengan ❤️ oleh Rizky - SMR Activity</b>
</div>
