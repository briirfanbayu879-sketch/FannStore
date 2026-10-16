# FannStore.id — Starter Prototype

Prototype frontend statis untuk toko top up game dengan desain biru responsif.

## Cara menjalankan
- Buka `index.html` di browser, atau unggah folder ini ke hosting statis.
- Pilihan game, nominal contoh, pencarian, dan alur pesanan demo berjalan di browser.

## Penting
Ini belum memproses transaksi nyata. Harga hanya placeholder. Sebelum diluncurkan, tambahkan:
1. Backend/API routes untuk membuat order dan memvalidasi harga.
2. Database untuk order, produk, status pembayaran, dan audit.
3. Payment gateway resmi dengan verifikasi webhook di server.
4. API distributor top up resmi dan mekanisme retry/idempotency.
5. Panel admin, autentikasi, rate limiting, validasi input, dan kebijakan privasi.
6. Konfirmasi hak jual dan dukungan tiap game dari distributor.
Jangan simpan secret API di frontend dan jangan meminta password akun game.
