# FUTURA SPACE — POS & Pembukuan

Sistem kasir (POS) sederhana + pembukuan untuk coffee shop **Futura Space**.

Berjalan 100% di browser. Data tersimpan di `localStorage` perangkat kasir.

## Fitur

- **Kasir**: pilih menu, keranjang, diskon, bayar Tunai / QRIS / Transfer / Kartu, hitung kembalian, cetak struk
- **Produk**: nama, kategori, harga jual, HPP, stok, aktif/nonaktif
- **Transaksi**: riwayat, filter tanggal & metode, reprint struk, void (stok kembali)
- **Pembukuan**: pemasukan otomatis dari penjualan + pengeluaran manual (bahan, gaji, sewa, dll.)
- **Laporan laba rugi**: omzet, HPP, laba kotor, pengeluaran, laba bersih, rincian metode bayar
- **Dashboard**: omzet hari ini, laba, stok menipis, menu terlaris
- **PIN kunci layar**, backup/impor JSON

## Cara pakai

1. Buka `index.html` di Chrome / Edge.
2. Mulai dari menu **Kasir**.
3. Isi HPP di setiap produk agar laba terhitung benar.
4. Catat pengeluaran di **Pembukuan**.
5. Unduh backup JSON secara berkala di pojok kanan atas.

## Catatan

- Data hanya ada di browser yang dipakai. Gunakan perangkat kasir yang sama, atau impor backup jika pindah perangkat.
- Ini sistem 1 gerai, offline-first. Bukan pengganti software akuntansi lengkap.
- Harga menu demo bisa diubah sesuai daftar harga asli Futura Space.
