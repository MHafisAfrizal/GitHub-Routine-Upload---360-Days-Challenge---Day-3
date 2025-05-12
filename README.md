# GitHub-Routine-Upload---360-Days-Challenge---Day-3

## 📅 Day 3 — 12 Mei 2025  
### 🔥 Fokus: Hero Section — Bagian Pertama yang Harus Langsung Nendang

---

### 🎯 Tujuan Hari Ini
Hari ini aku fokus membangun **Hero Section** — bagian yang bakal jadi kesan pertama pengunjung ketika membuka landing page ini. Bukan cuma soal tampilan, tapi juga soal bagaimana bagian ini menyampaikan pesan utama dengan cara yang visual, informatif, dan *eye-catching*.  

---

### 🔧 Apa yang Aku Kerjakan Hari Ini?

#### ✅ 1. Menyusun Struktur HTML
Aku mulai dari kerangka HTML yang bersih. Di dalam `<main>`, aku buat satu section dengan class `hero`. Di dalamnya, ada dua elemen utama:
- **Konten Utama** (headline, subheadline, CTA button)
- **Ilustrasi atau Gambar** (untuk daya tarik visual)

```html
<section class="hero">
  <div class="hero-content">
    <h1>Buat Web yang Bukan Sekadar Ada.</h1>
    <p>Kami bantu kamu membangun landing page yang bukan cuma tampil menarik, tapi juga bisa jualan.</p>
    <a href="#contact" class="cta-button">Konsultasi Gratis</a>
  </div>
  <div class="hero-image">
    <img src="assets/images/hero-banner.svg" alt="Ilustrasi Profesional">
  </div>
</section>
```

### 2. Styling CSS — Biar Cantik dan Responsif
Aku pakai Flexbox supaya bagian konten dan gambar bisa berdampingan di layar besar, dan otomatis stack ke bawah di mobile.

```css
.hero {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  padding: 60px 20px;
  background-color: #ffffff;
}

.hero-content {
  flex: 1 1 50%;
  max-width: 600px;
}

.hero-content h1 {
  font-size: 3rem;
  color: #212121;
  margin-bottom: 16px;
}

.hero-content p {
  font-size: 1.25rem;
  color: #555;
  margin-bottom: 24px;
}

.cta-button {
  background-color: #0077ff;
  color: #fff;
  padding: 12px 24px;
  text-decoration: none;
  border-radius: 8px;
  transition: all 0.3s ease-in-out;
}

.cta-button:hover {
  background-color: #005ec2;
}

.hero-image {
  flex: 1 1 40%;
  text-align: center;
}

.hero-image img {
  width: 100%;
  max-width: 400px;
  height: auto;
}
```

### 3. Uji Responsivitas
Aku pakai DevTools Chrome dan Firefox buat cek tampilan di berbagai ukuran layar. Hasilnya:

1. Tampilan di HP aman.

2. Gambar tetap proporsional.

3. CTA tetap kelihatan.

4. Tidak ada teks yang kepotong atau kependekan.


