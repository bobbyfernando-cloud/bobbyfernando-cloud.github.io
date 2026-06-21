# Bobby Fernando — Portfolio

Personal portfolio &amp; resume site for **Bobby Fernando** — Internal Audit, Finance, and aspiring Data/Finance Analyst based in Denpasar, Bali, Indonesia.

🔗 **Live site:** `https://bobbyfernando-cloud.github.io/`

## Tentang

Single-page portfolio yang menampilkan:

- Profil & ringkasan karier
- Pencapaian terukur (variance reduction, cost savings, dll.)
- Riwayat karier lengkap (2009 — sekarang)
- Proyek independen (budgeting, cost control analysis)
- Keahlian (audit, finance, SQL, Python)
- Pendidikan
- Tautan unduh CV (PDF)

## Struktur

```
.
├── index.html              # Halaman utama
├── style.css                # Styling (navy/cyan theme)
├── main.js                  # Interaktivitas (nav aktif, animasi, mobile menu)
├── profile-navy.jpg         # Foto profil
├── Bobby-Fernando-CV.pdf    # CV Bobby Fernando (PDF)
└── README.md
```

> Repo ini menggunakan struktur **flat** (semua file di root) karena nama repo `bobbyfernando-cloud.github.io` adalah repo akun GitHub Pages — situs otomatis tayang di root domain tanpa perlu konfigurasi tambahan.

## Cara deploy / update

1. Repo ini sudah aktif sebagai GitHub Pages karena namanya persis `<username>.github.io`.
2. Setiap push ke branch `main` otomatis ter-deploy ke `https://bobbyfernando-cloud.github.io/` dalam beberapa menit — tidak perlu pengaturan tambahan di **Settings → Pages**.
3. Jika ingin memastikan, cek **Settings → Pages**: source harus `Deploy from a branch`, branch `main`, folder `/ (root)`.

## Kustomisasi

- **Warna**: ubah variabel di bagian atas `style.css` (`--navy`, `--cyan`, dll).
- **Konten**: edit langsung di `index.html` — setiap section punya komentar penanda (`<!-- ABOUT -->`, `<!-- CAREER -->`, dst).
- **Foto profil**: ganti `profile-navy.jpg` (disarankan rasio potret, wajah di sepertiga atas), nama file boleh diganti asal path di `index.html` ikut disesuaikan.

## Catatan teknis

Semua path aset di `index.html` bersifat **relatif terhadap root** (`style.css`, `main.js`, `profile-navy.jpg`, `Bobby-Fernando-CV.pdf`) — jika ada file yang dipindah ke dalam folder, path di `index.html` wajib diperbarui juga, atau situs akan tampil tanpa styling/gambar/CV.
