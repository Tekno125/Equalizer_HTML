# Equalizer HTML

Sebuah file HTML sederhana yang menampilkan visualisasi equalizer/audio visualizer langsung di browser. Projek mini efek visual berbasis HTML/CSS/JS — mis. untuk dipasangkan dengan audio lokal atau stream audio di browser (tergantung implementasi index.html).

## Fitur
- Visual equalizer yang responsif terhadap audio.
- Hanya menggunakan satu file: index.html (mudah diunduh dan dijalankan).
- Mudah dikustomisasi: warna, jumlah bar, dan pengaturan visual umumnya berada di bagian CSS/JS di index.html.

## Cara pakai
1. Clone atau unduh repositori ini.
2. Buka file index.html di browser modern (Chrome, Firefox, Edge).
   - Opsi 1 (langsung): Klik dua kali index.html untuk membukanya lewat skema file://.
   - Opsi 2 (direkomendasikan jika ada fitur audio/microphone yang membutuhkan origin yang aman): Jalankan server lokal sederhana, misalnya:
     - Python 3: `python -m http.server` lalu buka http://localhost:8000
3. Jika index.html menyediakan kontrol pemutaran atau input audio:
   - Pilih/unggah file audio atau izinkan akses microphone bila diminta (jika fitur live input tersedia).
   - Tekan Play untuk melihat visual equalizer bereaksi.
