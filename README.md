# ERP by Fornestor.com

**Kelola operasional bisnis dalam satu aplikasi.** ERP by Fornestor.com membantu pemilik usaha mengatur penjualan, persediaan, pelanggan, laporan, akuntansi, dan aktivitas toko melalui aplikasi web dan desktop Windows.

[![Latest Release](https://img.shields.io/github/v/release/Fornestor/erppro-desktop?label=versi%20terbaru)](https://github.com/Fornestor/erppro-desktop/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows-2563eb)](https://github.com/Fornestor/erppro-desktop/releases/latest)

## Unduh aplikasi

- **Aplikasi web:** [erp.fornestor.com](https://erp.fornestor.com)
- **Aplikasi desktop Windows:** [Lihat dan unduh dari GitHub Releases](https://github.com/Fornestor/erppro-desktop/releases/latest)

Masuk menggunakan akun ERP Anda. Hak akses dan ketersediaan fitur mengikuti peran pengguna serta paket tenant.

## Fitur

- **Kasir dan transaksi** — catat penjualan dan telusuri riwayat transaksi.
- **Produk dan persediaan** — kelola stok fisik toko serta stok online/Marketplace.
- **Gudang dan restok** — dukung pemantauan barang dan kebutuhan pengadaan.
- **Pelanggan dan diskon** — kelola data pelanggan dan promosi toko.
- **Laporan dan analitik** — pantau aktivitas dan kinerja operasional.
- **Akuntansi** — hubungkan aktivitas usaha dengan pencatatan keuangan.
- **Marketplace** — kelola katalog dan pesanan toko yang memenuhi persyaratan akses dan wilayah layanan.
- **Akses berbasis peran** — fitur tersedia sesuai kewenangan pengguna dalam tenant.
- **Asisten AI dan Deep Audit** — bantu menganalisis kondisi operasional toko.
- **Pengelolaan wilayah Marketplace** — Super Admin dapat mengatur wilayah layanan dan meninjau rekomendasi wilayah berdasarkan toko tenant. Rekomendasi perlu ditinjau dan diterapkan secara manual.
- **Pengumuman global** — Super Admin dapat menjeda, melanjutkan, atau menghapus pengumuman.

## Deep Audit AI

Deep Audit AI menganalisis snapshot persediaan terkini serta data transaksi, anomali, dan aktivitas dalam periode audit. Data yang dikirim ke model dibatasi di server untuk menjaga cakupan audit tetap terkontrol.

Hasil audit yang tersimpan di server dapat dibuka dari perangkat lain pada tenant yang sama. Arsip menampilkan ringkasan laporan; laporan lengkap dibuka saat diperlukan dan dapat dicetak atau disimpan sebagai PDF. Arsip menyimpan maksimal 50 laporan per tenant, dengan laporan terlama dihapus otomatis saat batas tercapai.

Deep Audit AI hanya tersedia jika akun memenuhi persyaratan paket dan saldo token yang berlaku. Proses audit menggunakan layanan AI online dan membutuhkan koneksi internet.

## Ketersediaan Marketplace

Marketplace tersedia sesuai wilayah layanan yang ditetapkan. Jika alamat belum tersedia atau wilayah pengguna belum terlayani, katalog toko dan produk tidak dimuat sampai layanan tersedia di wilayah tersebut.

## Instalasi Windows

1. Buka [GitHub Releases](https://github.com/Fornestor/erppro-desktop/releases/latest).
2. Unduh installer Windows dari bagian **Assets**.
3. Jalankan installer dan ikuti petunjuk yang muncul.
4. Buka aplikasi dan masuk dengan akun ERP Anda.

Aplikasi desktop memerlukan koneksi internet untuk mengakses layanan ERP.

> **Catatan keamanan Windows:** Installer versi 6.0.1 belum ditandatangani dengan sertifikat digital penerbit. Windows dapat menampilkan peringatan SmartScreen atau penerbit tidak dikenal. Unduh installer hanya dari halaman GitHub resmi ini. Cocokkan checksum SHA-256 yang disediakan pada release sebelum menjalankan file.

## Pembaruan versi 6.0.1

- Menyempurnakan alur Kasir: setelah transaksi selesai, ringkasan transaksi dan tombol cetak atau kirim struk tersedia pada panel pembayaran.
- Memudahkan kasir melanjutkan transaksi baru. Jika barang dipilih ketika ringkasan transaksi masih tampil, panel otomatis kembali ke tampilan total tagihan dan pembayaran.
- Menampilkan rekomendasi produk saat keranjang masih kosong pada layar desktop. Produk dapat dipilih langsung dan rekomendasi mempertimbangkan promo, penjualan, pembaruan produk, serta margin.
- Menyediakan pemeriksaan kesiapan sebelum periode akuntansi ditutup, dengan validasi di antarmuka dan backend.

Lihat [Release 6.0.1](https://github.com/Fornestor/erppro-desktop/releases/tag/V.6.0.1) untuk informasi lengkap, installer Windows, dan checksum.

## Bantuan

Untuk bantuan penggunaan atau informasi paket, hubungi [Admin ERP melalui WhatsApp](https://wa.me/628996884600).

---

**ERP by Fornestor.com**  
Solusi operasional untuk membantu bisnis bekerja lebih teratur.
