# Benyek SAMP

Client SA-MP Android gratis dari **Benyek Store**.

## Download

Ambil APK terbaru di halaman **[Releases](../../releases)**.

## Kenapa aman

- Izin Android **hanya internet**: tidak ada akses kontak, SMS, mikrofon, lokasi, overlay, atau hapus aplikasi.
- Tanpa iklan dan tanpa pelacakan.
- **Tidak membawa file game.** Pakai file GTA San Andreas milikmu sendiri (lihat di bawah).
- Setiap rilis disertai `SHA256.txt`. Cocokkan hash file yang kamu unduh supaya yakin itu APK asli, bukan versi palsu dari pihak lain.

Unduh hanya dari halaman ini. APK Benyek SAMP dari sumber lain bukan rilis resmi.

## Memasang file GTA San Andreas

Benyek SAMP hanya client, file game kamu pasang sendiri secara manual. Tidak perlu aplikasi GTA SA terpasang.

1. Siapkan file GTA SA milikmu: `base.apk`, `split_config.arm64_v8a.apk`, dan file `.obb` (atau ZIP berisi `anim/ audio/ data/ models/ texdb/ text/`).
2. Buka tab **Modpack** di Benyek SAMP, lalu salah satu:
   - **Pilih file game** → pilih semua file sekaligus, atau
   - salin file ke `Android/data/id.benyekstore.sampclient/files/impor/` lewat file manager/PC, lalu tekan **Pindai folder impor**.
3. Tunggu sampai muncul *File game lengkap*.

APK launcher SA-MP lain juga bisa dipakai: Benyek SAMP hanya mengambil engine GTA SA-nya, library launcher itu (misalnya `libsamp.so`) tidak ikut dipasang.

## Status

| Fitur | Status |
|-------|--------|
| Server list, info live (pemain, mode, ping) | ✅ |
| Unduh konten server otomatis (cek SHA-256) | ✅ |
| Favorites / Official, tambah & hapus server | ✅ |
| Nickname & settings | ✅ |
| Pasang file GTA SA manual (base.apk + split_config + .obb) | ✅ |
| Buka GTA SA dari tombol Main (M1) | 🧪 uji coba |
| Masuk ke server (core client) | 🚧 dalam pengembangan |

---

Tidak berafiliasi dengan Rockstar Games, Take-Two Interactive, tim SA-MP, maupun open.mp.
GTA San Andreas adalah merek dagang Rockstar Games.
