# COSMIC CHAOS Starter

Ini adalah starter antarmuka lokal untuk proyek game social deduction COSMIC CHAOS.

## Cara mencoba
1. Unduh dan ekstrak ZIP.
2. Buka `index.html` di browser.
3. Buat room demo, tambahkan pemain demo, lalu mulai ronde.

## Penting
Versi ini BELUM merupakan multiplayer real-time. Room, pemain, peran, misi, dan voting hanya disimulasikan di satu browser. Jangan memublikasikannya sebagai game multiplayer yang sudah selesai.

## Tahap berikutnya
- Buat backend tepercaya untuk room, role assignment, timer, voting, dan win conditions.
- Gunakan Supabase Realtime untuk menyebarkan state/event ke pemain lain.
- Terapkan Row Level Security dan jangan pernah mengekspos service-role key di browser.
- Deploy frontend setelah tes lintas perangkat berhasil.
