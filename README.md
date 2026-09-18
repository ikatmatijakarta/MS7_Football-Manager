# MS7 Football Manager Mini Online — PURE FINAL

Build production tanpa data manager/player dummy.

## Yang dihapus
- Agung Pinoz / Raka Demo hardcoded
- MockDB
- MockGameService
- Frontend Simulation Preview
- Admin Panel dummy di dalam gameplay
- tombol/action yang hanya mengubah data RAM browser

## Source of truth
- Supabase Auth
- public.profiles
- public.clubs
- public.players
- public.player_state
- contracts / tactics / training / transfer / league / finance tables
- production RPCs

## Owner/Admin
Owner/Admin tetap masuk melalui tab Owner / Admin.
Manager approval, daftar human club, player master, dan Founding Draw dibaca dari Supabase production.

## Manager
Register → Approval → Create Club → Waiting Founding Draw → Game.

## PWA
Logo MS7 baru tetap dipakai untuk favicon, Android/iOS Home Screen, PWA, sidebar dan login.

Upload SEMUA isi folder ini ke root repository GitHub Pages dan replace file lama.
