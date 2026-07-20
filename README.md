# Tugas 3 — Mini Landing Page Project

Tugas praktik untuk mata pelajaran PPLG, kelas XII PPLG SMT 2.

## Nama
Akmal Fahreza

## Deskripsi
Landing page sederhana yang menampilkan navbar, hero section, tombol modern,
3 card fitur, dan footer. Halaman dibuat responsive untuk tampilan mobile.

## Bagian Halaman
- **Navbar** — logo + menu navigasi, sticky di atas halaman
- **Hero section** — judul, deskripsi singkat, dan tombol ajakan (CTA)
- **Tombol modern** — bentuk pil (`border-radius: 50px`), ada shadow dan
  efek hover terangkat
- **3 Card feature** — Cepat, Responsive, Modern — masing-masing dengan
  ikon, judul, dan deskripsi
- **Footer** — informasi identitas dan copyright

## Teknik CSS yang Digunakan
- **Flexbox** — dipakai di navbar, hero, feature cards (grid card yang
  fleksibel dengan `flex-wrap`), dan footer
- **Media query** — `@media (max-width: 640px)` untuk menyembunyikan menu
  navbar di HP dan mengecilkan ukuran judul hero
- **Hover effect** — tombol, link navbar, dan card feature semuanya
  memiliki reaksi visual saat disentuh/diarahkan kursor
- **Transition** — perubahan warna, posisi (translateY), dan shadow
  berjalan halus, tidak instan

## Cara Menjalankan
1. Buka file `mini-landing-page.html` di browser.
2. Coba perkecil lebar browser atau buka di HP untuk melihat tampilan
   responsive-nya.
3. Arahkan kursor ke tombol, link navbar, dan card untuk melihat efek
   hover dan transition.

## Struktur File
```
mini-landing-page.html   -> Halaman HTML dan CSS (satu file)
README-tugas3.md         -> Dokumentasi tugas ini
```

## Teknologi yang Digunakan
- HTML5
- CSS3 (Flexbox, Media Query, Transition, Hover Effect)
