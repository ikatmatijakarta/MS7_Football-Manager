# MS7 Football Manager RC5 — Always-On Live Match

RC5 dibuat di atas frontend RC4 Lineup/Admin Fix.

Paket ini fokus pada live match yang terus berjalan:
- backend lifecycle otomatis via pg_cron setiap 1 menit;
- target match sekitar 8 menit real-time;
- visual clock Match Centre bergerak otomatis;
- score/stats/events auto-sync dari server;
- browser boleh ditutup, match server tetap berjalan.

Urutan: jalankan SQL backend terlebih dahulu, verifikasi cron aktif, lalu deploy `index.html`.
