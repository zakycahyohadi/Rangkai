# Changelog

## 0.3.0 — 2026-10-07
- Deteksi kesalahan dan tombol **Perbaiki**. Menangani LED kelebihan arus, resistor basis, rating daya, komponen terbalik, kabel menembus pin, sambungan yang hampir nyambung, ground hilang, `1m` vs `1M`, nama dobel, dan komponen bertumpuk.
- Mode **Perbaiki otomatis** dan **Perbaiki semua**.
- Komponen yang dijatuhkan di atas kabel otomatis disisipkan.
- Notifikasi langsung saat muncul kesalahan berat.
- Model LED dan dioda dengan hambatan dalam.

## 0.2.0
- UI baru yang responsif untuk HP, tablet, dan desktop.
- Simulasi DC live (MNA + Newton-Raphson).
- Ekspor SPICE, BOM, SVG, dan JSON. Proyek tersimpan di browser.
- Pencarian perintah `Ctrl K`, bahasa ID/EN, tema gelap/terang.
- Gestur sentuh: dua jari untuk zoom dan geser, tahan lama untuk menu.

## 0.1.0
- Editor skematik dasar: library komponen, kabel, label net, netlist.
