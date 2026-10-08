# 🛒 Katalog Mobile

Katalog produk mobile-first untuk sales/outlet: pencarian instan, filter kategori, tombol **Pesan via WhatsApp** per produk (format pesanan otomatis).

![Status](https://img.shields.io/badge/mobile_first-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

## Fitur

- 🔍 Search live + chips kategori
- 💬 Order WA per item (nama, harga, template nama & alamat)
- 📱 Grid responsif 2→3 kolom, touch-friendly
- 📴 Static — bisa dibuka dari HP tanpa install

## Teknologi

Astro static + vanilla JS. Data di array `products` atas file `src/pages/index.astro`.

## Kustomisasi

- Nomor WA: konstanta `WA_NUMBER`
- Produk: tambah object `{ n, h, k, e }` (nama, harga, kategori, emoji)

## Run

```bash
npm install
npm run dev
```

Live: https://dulkemot.github.io/katalog-mobile/

MIT — dulkemot 2026
