# Glints Filter

Ekstensi Chrome simpel buat nge-filter lowongan kerja atau nama perusahaan yang nggak pengen dilihat di Glints. 

Kadang kan capek lihat lowongan dari perusahaan bodong, outsourcing yang itu-itu aja, atau posisi yang sama sekali nggak nyambung. Nah, ekstensi ini gunanya buat nyembunyiin itu semua secara otomatis biar feed lowongan lebih bersih.

## Fitur

- **Blokir by Keyword**: Bisa masukin nama perusahaan atau keyword posisi tertentu (misal: "PT Mencari Cinta Sejati" atau "Sales").
- **Bersih & Nggak Meninggalkan Celah**: Ekstensi ini mencegat data langsung dari API Glints sebelum dirender ke halaman. Jadi nggak ada sisa ruang kosong (gap) bekas lowongan yang di-hide.
- **DOM Fallback**: Kalau ada lowongan yang entah gimana lolos dari filter API, script tetap akan nyari dan nge-hide elemen lowongannya beserta wrappernya dari halaman.
- **Update Realtime**: Begitu masukin keyword baru di popup, lowongan di halaman yang lagi kebuka bakal langsung hilang saat itu juga tanpa perlu direfresh.

## Cara Install

1. Download atau clone repository ini ke komputer.
2. Buka browser Chrome, lalu pergi ke `chrome://extensions/`.
3. Aktifin toggle **Developer mode** di pojok kanan atas.
4. Klik tombol **Load unpacked** di pojok kiri atas.
5. Pilih folder ekstensi ini.
6. Selesai! Ekstensi sudah terpasang dan siap dipakai.

## Cara Pakai

1. Buka web Glints.
2. Klik icon ekstensi Glints Filter di browser.
3. Masukin nama perusahaan atau kata kunci posisi yang mau diblokir, terus klik **Blokir**.
4. Lowongan yang mengandung kata tersebut bakal langsung amblas dari pandangan.
5. Kalau berubah pikiran, tinggal klik icon hapus di sebelah kata kunci yang udah diblokir.

## Catatan

Hati-hati kalau masukin kata kunci yang terlalu pendek atau terlalu umum (misalnya cuma masukin "IT" atau "PT"). Filter ini juga mengecek semua teks di dalam kartu lowongan, jadi kalau keywordnya terlalu umum, bisa-bisa lowongan incaranmu malah ikut keblokir.
