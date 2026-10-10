# Membandingkan Tata Tulis Aksara Jawa

Aplikasi web untuk membandingkan hasil transliterasi Latin → Aksara Jawa dari 3 paugeran secara real-time: **KBJ, Sriwedari, dan Cara Kawi (Mardi Kawi)**.

Aplikasi ini ringan, 100% client-side.

[HTML](https://img.shields.io/badge/HTML-Vanilla-orange)
[Aksara](https://img.shields.io/badge/Aksara-Jawa-8B0000)
[GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue)

---

### ✨ Fitur

- **Input 1x, Output 3x:** Ketik Latin sekali, langsung tampil di KBJ, Sriwedari, dan Cara Kawi
- **Real-time:** Transliterasi otomatis saat mengetik
- **Kontrol Tampilan:**
  - Slider **Ukuran Aksara** 
  - Slider **Spasi Vertikal** 
- **Panel Panduan Lengkap** di bagian atas halaman
- **Desain Modern:** Gradasi warna, grid responsif, tanpa dependensi

### 📜 3 Paugeran yang Dibandingkan

| Paugeran | Ciri Khas |
| :--- | :--- |
| **KBJ** | Kongres Bahasa Jawa - standar yang paling umum dipakai sekarang |
| **Sriwedari** | Hasil Kongres Sriwedari, mempertahankan tradisi klasik |
| **Cara Kawi (Mardi Kawi)** | Untuk Jawa Kuno. **Tidak mengenal Murda & Rekan** |

### ⚠️ PENTING: Cara Penulisan Latin

Agar hasil transliterasi akurat, ikuti aturan ini (sesuai panel di aplikasi):

1.  **E Pepet & E Taling:**
    - `e` untuk pepet → `segar`, `ketan`
    - `é`, `è`, atau `e'` untuk taling → `saté`, `bèbèk`, `sate'`
2.  **Panambang / Akhiran:** Gunakan strip `-` → `pangan-an`, `buku-ne`
3.  **Aksara Swara:** Vokal Kapital murni → `A`, `I`, `U`, `E`, `O`
4.  **Aksara Murda:** Konsonan Kapital → `N, K, T, S, P, G, B, J, NY`
5.  **Aksara Rekan:** Untuk huruf asing → `f, v, z, kh, dz, gh`

**Catatan Cara Kawi:** Karena tidak mengenal Murda & Rekan, huruf tersebut akan tetap tampil Latin di output Cara Kawi. Ini by design.

### 💡 Contoh Uji Coba

```
Eko mangan saté
pangan-an
Aku tuku Foto
Negara Indonesia
```

### 📄 Lisensi

MIT License. Bebas dipakai untuk edukasi & pelestarian budaya.
