**Yang baru di 0.8.0 — M1 percobaan pertama**

- **Tombol Main membuka GTA San Andreas** (singleplayer) dari file game milikmu: engine, base.apk, dan data di folder `gta/`. Belum terhubung ke server.
- Game berjalan di proses terpisah, jadi kalau engine crash, launcher tetap terbuka.
- **Kirim log game** (tab Modpack): kalau game crash atau layar hitam, tekan tombol ini dan kirim lognya untuk diperbaiki.

**Dari 0.7.2**

- **base.apk dari launcher lain diterima** (misalnya SAMP Unity), asalkan berisi kode Java GTA SA. Status "base.apk" di tab Modpack akan jadi "ada".

**Dari 0.7.1**

- **APK launcher SA-MP lain diterima.** Dari APK seperti itu hanya engine GTA SA (libGTASA dkk.) yang diambil; `libsamp.so` dan library launcher lain tidak dipasang.

**Dari 0.7.0**

- **Pasang file GTA SA manual.** `base.apk` dan `split_config.arm64_v8a.apk` (plus `.obb` / ZIP data game) bisa dipilih sekaligus lewat tombol **Pilih file game** di tab Modpack.
- **Folder impor.** Salin file ke `Android/data/id.benyekstore.sampclient/files/impor/`, lalu tekan **Pindai folder impor**. File yang berhasil dipasang dipindah/dihapus dari folder itu, yang gagal dibiarkan.
- Status engine dan base.apk tampil di kartu File GTA San Andreas, plus ringkasan hasil per file.
- Tidak perlu aplikasi GTA San Andreas terpasang.

**Update dari 0.6.0 / 0.7.x:** langsung pasang menimpa, file game dan modpack tidak hilang.

**Belum bisa:** masuk ke server. M1 masih uji coba; berikutnya M2 (overlay di dalam game) dan M3 (koneksi ke server).

Benyek SAMP tidak menyediakan file game GTA San Andreas. Pakai file milikmu sendiri.
Izin aplikasi: hanya internet. Android 8.0 ke atas.
Cocokkan hash file dengan `SHA256.txt`.
