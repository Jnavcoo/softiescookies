# Softie's Cookie — Official Website

Website resmi Softie's Cookie, toko soft cookies & brownie bites dari Kediri.

## 🌐 Live URL
https://softiescookie.com

## 📋 Tentang Project
- **Jenis**: Static website (HTML/CSS/JS)
- **Hosting**: Vercel
- **Domain**: softiescookie.com

## 🍪 Fitur
- Halaman menu lengkap (Soft Cookies & Brownie Bites)
- Galeri foto produk
- Section ulasan pelanggan
- Form order (terintegrasi WhatsApp)
- Responsive mobile-friendly

## 🚀 Cara Update Website

### Update konten (teks/harga)
1. Buka file `index.html`
2. Edit bagian yang ingin diubah
3. Simpan file

### Upload ke website
```bash
git add .
git commit -m "update: [tulis perubahan apa]"
git push
```
Vercel otomatis deploy dalam ~30 detik setelah push.

## 📞 Kontak
- Instagram: @softies.cookie  
- WhatsApp: 0856-0668-5163
- Lokasi: Kediri, East Java
```

---

## Step 6 — Testing checklist sebelum launch

Sebelum share URL ke pelanggan, cek semua ini:

**Fungsionalitas:**
- [ ] Semua foto produk tampil dengan benar
- [ ] Tab "Soft Cookies" dan "Brownie Bites" bisa diklik
- [ ] Tombol "Order Now" membuka WhatsApp dengan pesan benar
- [ ] Form order terisi dan kirim ke WA dengan data lengkap

**Tampilan:**
- [ ] Cek di HP (buka di Chrome mobile)
- [ ] Cek di laptop/desktop
- [ ] Semua teks terbaca, tidak ada yang terpotong

**Teknis:**
- [ ] URL HTTPS aktif (ada gembok di browser)
- [ ] Tidak ada error merah di browser console (`F12 → Console`)
- [ ] Halaman load dalam < 3 detik

---

## Workflow setelah launch

Setiap kali mau update website (ganti harga, tambah produk, dll.):
```
Edit index.html  →  git add .  →  git commit -m "pesan"  →  git push
                                                    ↓
                                        Vercel auto deploy (~30 detik)
                                                    ↓
                                          Website langsung update ✅
