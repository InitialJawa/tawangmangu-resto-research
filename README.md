<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=220&section=header&text=SafeHaven&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Financial%20%26%20Stock%20Analytics%20Platform%20(IDX%20%2F%20IHSG)&descAlignY=58&descSize=18" width="100%"/>

<a href="#">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=2500&pause=800&color=2C5364&center=true&vCenter=true&width=650&lines=Real-time+Stock+%26+Market+Intelligence;6-Dimensi+Factor+Scoring+Engine;AI-Powered+Portfolio+Advisor+(Gemini);Dibangun+untuk+Investor+Retail+Indonesia" alt="Typing SVG" />
</a>

Platform analisis saham dan intelijen pasar keuangan modern yang menggabungkan data real-time, analisis teknikal & fundamental, visualisasi musiman, perbandingan sektor, serta analisis berbasis kecerdasan buatan (Gemini AI).

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-6-646CFF?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?logo=node.js&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite&logoColor=white)
![License](https://img.shields.io/badge/status-in%20development-yellow)

</div>

---

## 📋 Daftar Isi

- [Fitur Utama](#-fitur-utama)
- [Tech Stack](#️-tech-stack)
- [Panduan Instalasi](#-panduan-instalasi)
- [Struktur Data](#-struktur-data)
- [Migrasi ke Firebase](#-migrasi-ke-firebase-opsional)
- [Roadmap](#-roadmap)

---

## 🚀 Fitur Utama

### 📊 Analisis Ticker & Scoring Komprehensif
| Fitur | Deskripsi |
|---|---|
| **6 Dimensi Faktor** | Breakdown Quality, Growth, Value, Momentum, Volume, dan Dividend |
| **Perbandingan Sektor** | Kinerja ticker vs. sektor industri dan IHSG |
| **Gauge Teknikal** | Analisis teknikal real-time & konsensus target harga analis (Yahoo Finance) |

### 📈 Visualisasi & Intelijen Pasar Terpadu
- **Laporan Keuangan** — laba bersih, pendapatan, dan margin usaha tahunan
- **Alokasi Dividen TTM** — payout ratio, dividend yield, ex-date, dan tanggal bayar
- **Analisis Musiman** — historis pergerakan bulanan saham (%)
- **Kinerja Historis** — 1M, 1B, 3B, 6B, YTD, 1T

### 🤖 AI Stock & Portfolio Advisor
Ditenagai **Google Gemini AI** untuk memberikan wawasan kuantitatif, analisis risiko, dan rekomendasi portofolio secara kontekstual.

### 💼 Manajemen Portofolio & Watchlist
Catat posisi saham, estimasi profit/loss, alokasi aset, serta kalkulasi dividen otomatis.

---

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Frontend**
- React 19 + Vite 6
- Tailwind CSS v4
- Recharts
- Lightweight Charts
- Lucide Icons

</td>
<td valign="top" width="50%">

**Backend**
- Node.js + Express (`server.ts`)
- SQLite (`safehaven.db`)

</td>
</tr>
<tr>
<td valign="top">

**AI & Data Feed**
- `@google/genai` (Gemini API)
- `yahoo-finance2`

</td>
<td valign="top">

**Status**
- 🚧 In active development

</td>
</tr>
</table>

---

## 📦 Panduan Instalasi

**1. Install dependencies**
```bash
npm install
```

**2. Jalankan development server**
```bash
npm run dev
```
> Aplikasi akan berjalan di `http://localhost:3000`

**3. Build untuk produksi**
```bash
npm run build
npm start
```

---

## 🗄️ Struktur Data

Data disimpan secara lokal menggunakan SQLite dengan dua entitas utama:

| Tabel | Keterangan |
|---|---|
| `watchlist` | Daftar saham yang dipantau pengguna |
| `portfolio` | Posisi saham aktif, alokasi, dan histori transaksi |

---

## 🔄 Migrasi ke Firebase (Opsional)

Jika ingin memindahkan storage dari SQLite lokal ke Google Firebase (Firestore & Auth):

1. **Export Data SQLite** — ekspor tabel `watchlist` dan `portfolio` menjadi format JSON
2. **Setup Firebase Project** — buat proyek di [Firebase Console](https://console.firebase.google.com/), aktifkan **Firestore Database** dan **Firebase Authentication**
3. **Impor Data ke Firestore** — jalankan script penyerapan data JSON ke koleksi:
   ```
   users/{userId}/portfolio
   users/{userId}/watchlist
   ```

---

## 🗺️ Roadmap

- [ ] Multi-Tier Rotation (Saham / Emas / Cash IDR / USD)
- [ ] Strategy templates (Buffett, Lynch, Renaissance, Dividend Aristocrats, All Weather)
- [ ] AI provider fallback chain (GPT-4o-mini → Claude 3.5 Haiku → Gemini 2.0 Flash)

---

<div align="center">

Built for Indonesian retail investors 🇮🇩

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=150&section=footer" width="100%"/>

</div>
