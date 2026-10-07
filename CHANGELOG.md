# Changelog

## 0.3.1 — 2026-10-07
- Perbaikan: klik dua kali pada komponen untuk mengedit nilainya sekarang benar-benar berfungsi (sebelumnya tidak pernah terpicu). Di HP, ketuk dua kali membuka panel properti.
- Perbaikan: menutup panel Komponen dengan tombol ✕ sekarang diingat setelah halaman dibuka ulang.
- HP landscape memakai tata letak HP. Sebelumnya rail terpotong dan rangkaian tampil sangat kecil.
- HP: nama proyek tidak lagi terpotong, koordinat kursor disembunyikan, dan rangkaian dimuat lebih besar.
- Tablet: bar simulasi tidak lagi menutupi panel Inspektor.
- Lebih cepat dibuka: font dimuat tanpa menahan tampilan pertama, dan cukup satu file per keluarga font.
- Tambah favicon, `theme-color`, doctype, dan meta viewport. Statistik pengunjung lewat GoatCounter.

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
