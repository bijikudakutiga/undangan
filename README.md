# Undangan Pernikahan — Yan Peter & Margaretha

## Struktur
- `index.html` — halaman utama undangan
- `assets/foto-pasangan.png` — foto yang tampil di bagian awal
- `assets/musik-pengiring.mp3` — musik latar

## Sebelum online
Buka `index.html`, cari bagian ini di dekat atas file, isi dengan kredensial dari project Supabase Anda:

```html
window.SUPABASE_URL = 'GANTI_DENGAN_SUPABASE_URL';
window.SUPABASE_ANON_KEY = 'GANTI_DENGAN_SUPABASE_ANON_KEY';
```

Selama belum diisi, situs otomatis berjalan di mode demo (data tersimpan sementara, tidak permanen).

## Link personalisasi tamu
Tambahkan parameter di belakang URL:

```
https://nama-situs-anda.pages.dev/?to=Nama+Tamu&max=2
```

`to` = nama tamu yang tampil di undangan, `max` = jatah kursi (dipakai kalau tabel `guests` di Supabase belum ada / belum cocok).
