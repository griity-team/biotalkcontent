---
name: biotalksocialmedia
description: Skill untuk membantu tim social media BioTalk membuat ide konten Instagram bulanan (post photo, carousel, reels) beserta moodboard dan tema bulanan. Harus digunakan saat tim ingin merencanakan konten Instagram sebulan penuh. Sebelum eksekusi, Claude wajib meminta input tema/moodboard bulan tersebut dan persentase distribusi produk dari user.
---

# BioTalk Social Media — Monthly Content Planner

Skill ini membantu tim social media BioTalk membuat rencana konten Instagram bulanan yang selaras dengan brand guidelines, tema bulan, dan alokasi produk yang ditentukan tim.

## Brand Reference

- Brand guidelines: [BioTalk_BrandGuidelines.md](BioTalk_BrandGuidelines.md)

## Produk BioTalk

Berikut adalah produk-produk BioTalk yang bisa dimasukkan ke dalam konten:

- Calendula Series
- Centella
- Natural Deo
- Kefir Charcoal
- Kefir Scrub
- Argan Oil
- Day Cream
- Night Cream
- Toner
- Honey Goat Milk
- Natural Wink

## Format Konten Instagram

- **Carousel** — edukasi, tips kulit, ingredient spotlight, myth vs fact
- **Photo** — product shot, lifestyle, testimonial, promo
- **Reels/Video** — how-to, behind the scenes, product demo, giveaway

## Content Pillars BioTalk

1. Product Feature
2. Skin Tips & Education
3. Myth vs Fact
4. Ingredient Spotlight
5. Testimoni
6. Giveaway / Engagement

---

## Steps

### Step 1 — Minta Input Tema & Moodboard Bulanan

Sebelum membuat konten apapun, tanyakan kepada user:

> "Halo! Sebelum aku mulai bikin content plan bulanan, aku butuh beberapa info dulu:
>
> **1. Bulan & Tahun**
> Rencana konten untuk bulan apa?
>
> **2. Tema / Moodboard Bulanan**
> Apa tema atau moodboard yang mau dipakai bulan ini? (contoh: "summer glow", "back to basics", "kulit sehat dari dalam", dll.)
> Kalau ada referensi visual atau mood tertentu, ceritain juga ya.
>
> **3. Fokus atau Momen Khusus**
> Ada momen penting bulan ini? (contoh: Lebaran, Harbolnas, ulang tahun brand, campaign tertentu, dll.)
>
> Setelah itu, aku akan tanya soal alokasi produknya."

Tunggu jawaban user sebelum lanjut ke Step 2.

### Step 2 — Minta Distribusi Produk (%)

Setelah user menjawab tema, tanyakan:

> "Oke, satu lagi! Tolong tentukan **persentase kemunculan tiap produk** untuk bulan ini. Total harus 100%.
>
> Produk BioTalk yang tersedia:
> - Calendula Series
> - Centella
> - Natural Deo
> - Kefir Charcoal
> - Kefir Scrub
> - Argan Oil
> - Day Cream
> - Night Cream
> - Toner
> - Honey Goat Milk
> - Natural Wink
>
> Contoh format:
> - Calendula Series: 30%
> - Centella: 20%
> - Toner: 20%
> - Natural Deo: 30%
>
> Produk yang tidak ingin dimunculkan bulan ini boleh dikosongkan atau ditulis 0%."

Validasi bahwa total persentase = 100% sebelum lanjut. Kalau tidak 100%, minta user untuk menyesuaikan.

### Step 3 — Baca dan Internalisasi Brand Guidelines

Baca [BioTalk_BrandGuidelines.md](BioTalk_BrandGuidelines.md) dan pastikan semua output konten selaras dengan:
- Tone: natural, clean, friendly, educational
- Bahasa: Indonesia (untuk caption & copy)
- Warna yang relevan per produk (sesuai color palette di guidelines)
- Content pillars BioTalk

### Step 4 — Buat Content Plan Bulanan

Berdasarkan semua input, buat rencana konten dengan struktur berikut:

#### Output yang Dihasilkan:

**A. Ringkasan Strategi Bulan Ini**
- Tema & moodboard
- Momen/event penting
- Distribusi produk yang disepakati

**B. Ide Konten — Target minimal 16 post per bulan (4 post/minggu)**

Untuk setiap post, sertakan:
| No | Minggu | Format | Produk | Pillar | Judul / Konsep | Caption Hook | Visual Direction |
|----|--------|--------|--------|--------|----------------|--------------|-----------------|

- **Format**: Carousel / Photo / Reels
- **Pillar**: salah satu dari 6 content pillars
- **Judul / Konsep**: ide konten singkat
- **Caption Hook**: kalimat pembuka caption yang menarik
- **Visual Direction**: arahan visual singkat (warna, mood, props, angle)

**C. Rekomendasi Hashtag Bulanan**
Sesuaikan dengan tema dan produk yang difokuskan.

**D. Catatan Produksi**
Tips eksekusi khusus bulan ini (misalnya: butuh lifestyle shoot, perlu UGC dari testimoni, dll.)

---

## Aturan Output

- Selalu gunakan Bahasa Indonesia untuk copy/caption
- Visual direction harus konsisten dengan brand colors BioTalk
- Distribusi format: usahakan mix carousel, photo, dan reels tiap minggu
- Pastikan produk muncul proporsional sesuai % yang ditetapkan user
- Jangan eksekusi sebelum Step 1 dan Step 2 selesai dijawab user
