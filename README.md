# Riset Revitalisasi Ekonomi — Tawangmangu, Karanganyar

Riset komprehensif tentang kondisi ekonomi Tawangmangu: dari analisis kegagalan resto, kompetitor aktif, strategi menghidupkan distrik, hingga sejarah pergeseran wisatawan ke pemudik (siapa orang-orang kunci, kemana mereka pergi).

## Ringkasan Proyek

**Tujuan:** Memetakan seluruh resto/warung yang tutup di Tawangmangu untuk menemukan celah pasar bagi bisnis kuliner baru.

**Lokasi:** Tawangmangu, Kabupaten Karanganyar, Jawa Tengah (lereng Gunung Lawu)

**Masalah Utama:**
- 100+ resto/kafe di daerah kecil, banyak yang tutup
- Kunjungan wisatawan Grojogan Sewu turun drastis (300K → <100/hari)
- 72% pedagang Grojogan Sewu tutup (141 → 40 aktif)
- Wisata alam kalah bersaing dengan wisata buatan

## Struktur Proyek

```
tawangmangu-resto-research/
├── README.md                                 # File ini
├── data/
│   ├── resto_tutup.json                      # Data resto tutup (7 kasus)
│   ├── resto_aktif.json                      # Data kompetitor aktif (37 usaha)
│   └── properti_bekas.json                   # Properti bekas resto dijual/sewa (8 listing)
└── docs/
    ├── 01_PROFIL_KAWASAN.md                  # Demografi, wisata, ekonomi (UPDATE: BPS data, investor asing)
    ├── 02_DAFTAR_RESTO_TUTUP.md              # Mapping satu-satu resto tutup
    ├── 03_KOMPETITOR_AKTIF.md                # Mapping satu-satu kompetitor aktif
    ├── 04_ANALISIS_KEGAGALAN.md              # Pola kegagalan + insight
    ├── 05_PELUANG_BISNIS.md                  # Rekomendasi 3 konsep kuliner
    ├── 06_REVITALISASI_DISTRIK.md            # ⭐ Strategi menghidupkan distrik (10 jenis usaha, 4 fase, case study)
    └── 07_SEJARAH_PERGESERAN.md             # ⭐ Sejarah Tawangmangu: tokoh kunci, pergeseran wisatawan→pemudik
```

## Temuan Utama

### Resto Tutup

| Kategori | Jumlah | Contoh |
|----------|--------|--------|
| Tutup total/permanen | 100+ | ~101 lapak Grojogan Sewu, Warung Gito, Waroeng Hanif |
| Tutup sementara | 2 | Sakera Resto, Warung Mbok Yem |
| Turun omzet/terancam | 10+ | Warung Cemoro Kandang |

### Kompetitor Aktif

| Kategori | Jumlah | Harga |
|----------|--------|-------|
| Kafe viral (view) | 10 | Rp25K-50K |
| Resto | 7 | Rp15K-85K |
| Warung tradisional | 13 | Rp5K-25K |
| Jajanan GoFood | 7 | Rp4K-39K |
| **Total** | **37** | |

### Properti Bekas Resto

| Status | Jumlah | Harga |
|--------|--------|-------|
| Dijual | 5 | Rp1.6M - Rp4.5M |
| Disewakan | 3 | Rp110-200 Jt/tahun |

### Sinyal Ekonomi Baru (Juli 2026)

| Sinyal | Status | Dampak |
|--------|--------|--------|
| Terminal revitalisasi | Rencana Dishub Jateng | Zona bisnis baru |
| Investor Dubai (kereta gantung) | MoU, realistis 3-5 tahun | Akses Solo-Tawangmangu 15 menit |
| Investor Turkiye (balon udara) | Tertunda | Wahana wisata potensial |
| Wisata halal pilot project | Aktif di Tawangmangu | Magnet wisatawan Muslim |
| UMKM Karanglo | Aktif | Olahan pisang, ubi, grubi |
| Pertanian | 38% lahan (2.665 ha) | Agroturisme potensial |

## 5 Pola Kegagalan

1. **Kunjungan wisatawan anjlok** — 70%+ kasus
2. **Longsor/bencana alam** — 30% kasus
3. **Harga tiket mahal** — PNBP Rp15K, pungli parkir
4. **Kompetisi wisata buatan** — Lawu Park, Wonder Park
5. **Monyet ganggu** — downward spiral

## 10 Usaha yang Cocok di Tawangmangu

| No | Usaha | Modal | Prioritas |
|----|-------|-------|-----------|
| 1 | Mini Theme Park / Foto Spot | Rp100-300 Jt | ⭐⭐⭐ |
| 2 | Agroturisme Petik Buah | Rp50-150 Jt | ⭐⭐⭐ |
| 3 | Night Market / Street Food | Rp50-100 Jt | ⭐⭐⭐ |
| 4 | Budget Homestay | Rp50-100 Jt | ⭐⭐⭐ |
| 5 | Kopi Specialty Tawangmangu | Rp30-60 Jt | ⭐⭐ |
| 6 | Home Industry Olahan | Rp10-30 Jt | ⭐⭐ |
| 7 | Rental & Outbound Center | Rp30-80 Jt | ⭐⭐ |
| 8 | Cloud Kitchen + GoFood | Rp20-40 Jt | ⭐⭐ |
| 9 | Warung Pemudik | Rp30-50 Jt | ⭐⭐ |
| 10 | Co-working Space | Rp40-80 Jt | ⭐ |

Lihat detail lengkap di `docs/06_REVITALISASI_DISTRIK.md`

## Sumber Data

| No | Sumber | Jenis Data |
|----|--------|-----------|
| 1 | Espos.id | Berita tutup pedagang Grojogan Sewu, terminal revitalisasi |
| 2 | TribunSolo | Berita Lebaran, warung tutup, kunjungan wisata |
| 3 | KRJogja | Data kunjungan Grojogan Sewu |
| 4 | InilahJateng | Kebakaran warung Gito |
| 5 | InfoNasional | Pedagang tutup kios |
| 6 | Nusawara | Statistik kunjungan |
| 7 | KaranganyarNews | Rekomendasi kafe aktif |
| 8 | IDNTimes | Daftar resto hits |
| 9 | GoFood/MenuKuliner | Warung aktif di platform delivery |
| 10 | Pinhome/Lamudi | Properti bekas resto dijual/sewa |
| 11 | Instagram | postingan warung/cafe |
| 12 | Google Maps | Review, rating, jumlah kafe |
| 13 | HargaMenu.net | Daftar warung + harga |
| 14 | CariKulinerIndonesia | Data warung kecil |
| 15 | BPS (Scribd) | Kecamatan Tawangmangu Dalam Angka 2025 |
| 16 | Bisnis.com | Investor Dubai kereta gantung |
| 17 | Kompas.com | Investor Turkiye balon udara |
| 18 | Solopos | Wisata halal Tawangmangu, terminal revitalisasi |
| 19 | BSOET.com | Sejarah Tawangmangu Wonder Park, The Lawu Group |
| 20 | InilahJateng | Investor Dubai batal, pedagang tutup |
| 21 | HarianJogja | Wisatawan alam ke wisata buatan |
| 22 | UMS ETD | Skripsi dampak pariwisata |
| 23 | Undip ETD | Desa wisata Tawangmangu |
| 24 | thelawugroup.com | Profil The Lawu Group, unit usaha |
| 25 | smol.id | Investor Turki batal, cable car dialihkan |
| 26 | mercusuar.co | Pedagang wisata alam alih profesi |
| 27 | InfoNasional | Pedagang tutup kios Juli 2026 |

## Terakhir Diperbarui

19 Juli 2026
