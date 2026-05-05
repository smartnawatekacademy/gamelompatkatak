🐸 Lompat Katak: Petualangan Matematika Seru

Lompat Katak adalah sebuah web-based educational game interaktif yang dirancang khusus untuk membantu siswa Sekolah Dasar (SD) kelas 1 dalam melatih kemampuan matematika dasar mereka dengan cara yang menyenangkan dan kompetitif.

Game ini mengajak pemain untuk mengendalikan seekor katak melompati daun teratai dengan menjawab soal penjumlahan, pengurangan, perkalian, dan pembagian. Semakin cepat dan tepat mereka menjawab, semakin tinggi skor dan level yang mereka capai!

Dikembangkan murni menggunakan HTML5, CSS3, dan Vanilla JavaScript (Canvas API) tanpa framework eksternal, menjadikannya sangat ringan, responsif, dan siap dimainkan di perangkat apa pun secara langsung melalui browser.

✨ Fitur Utama

🎮 3 Mode Permainan:

👤 Solo Mode: Bermain sendiri untuk mencetak rekor tertinggi.

⚔️ Duel Mode: Bersaing langsung dengan teman (Split-screen).

🛡️ Squad Mode: Pertarungan seru hingga 4 pemain sekaligus dalam satu layar.

🧠 Auto-Leveling Dinamis: Tingkat kesulitan soal akan menyesuaikan secara otomatis seiring bertambahnya skor pemain (mulai dari penjumlahan/pengurangan dasar, hingga perkalian & pembagian).

💡 Umpan Balik Edukatif: Sistem memberikan informasi jawaban yang benar jika pemain salah melompat, membantu proses belajar secara langsung.

🔥 Sistem Combo & Power-Up: Pemain yang menjawab cepat secara beruntun akan mendapatkan efek visual Api Combo dan bonus poin. Terdapat juga Daun Emas (Poin Ekstra) dan Daun Hati (Nyawa Tambahan).

🎨 Kustomisasi & Transisi Tema: Pemain dapat memilih warna katak mereka. Tema latar belakang akan berubah (Siang ☀️ ➔ Sore 🌇 ➔ Malam 🌙) seiring pencapaian skor.

🏆 Papan Skor Global (Leaderboard): Terintegrasi dengan Google Spreadsheet sebagai database real-time untuk menyimpan nama, asal sekolah, dan skor pemain.

📊 Rapor Belajar (Post-Game Report): Menampilkan statistik jawaban benar, salah, dan predikat kemampuan siswa di akhir permainan.

🎵 Audio Sintetik Mandiri: Menggunakan Web Audio API untuk menghasilkan efek suara (lompat, jawaban benar, cipratan air) tanpa memerlukan aset file .mp3 eksternal.

🚀 Cara Memainkan (Demo)

Game ini dapat dimainkan secara langsung tanpa instalasi!
👉 Mainkan Lompat Katak Sekarang! (Ubah link ini dengan URL GitHub Pages Anda)

Instruksi Bermain:

Pilih Mode Permainan di menu utama.

Masukkan Nama, Asal Sekolah, dan pilih Warna Katak.

Sistem akan memunculkan soal matematika.

Klik/Ketuk daun teratai yang memiliki jawaban yang benar.

Waspada dengan Timer (waktu 15 detik per soal).

Kumpulkan skor sebanyak-banyaknya dan catat nama Anda di Papan Skor!

🛠️ Teknologi yang Digunakan

Frontend: HTML5, CSS3 (CSS Grid/Flexbox), Vanilla JavaScript (ES6+).

Rendering: HTML5 Canvas API (menggunakan requestAnimationFrame untuk game loop yang smooth).

Audio: Web Audio API (Sintesis suara real-time).

Database (Leaderboard): Google Apps Script & Google Spreadsheet API (fetch / POST & GET request).

Penyimpanan Lokal: localStorage (sebagai cadangan/offline mode).

📂 Struktur File

Proyek ini sengaja dirancang dalam Satu File Tunggal (Single-File App) untuk kemudahan distribusi dan implementasi.

index.html: Berisi seluruh markah HTML, gaya CSS, logika JavaScript permainan, sistem rendering, dan koneksi API.

🤝 Berkontribusi

Proyek ini terbuka untuk kontribusi! Jika Anda memiliki ide untuk fitur baru, perbaikan bug, atau peningkatan performa:

Lakukan Fork pada repository ini.

Buat branch fitur Anda (git checkout -b fitur-baru-keren).

Lakukan Commit perubahan Anda (git commit -m 'Menambahkan fitur keren').

Lakukan Push ke branch (git push origin fitur-baru-keren).

Buka Pull Request.

👨‍💻 Pengembang

Dikembangkan oleh Ramlan Marbun

🌐 Website: www.ramlanmarbun.my.id

📱 Instagram: @ramlanmarbunlg

🎓 Dipersembahkan oleh: SMART NawaTek Academy

📜 Lisensi

Hak Cipta © 2026 Ramlan Marbun. Seluruh hak cipta dilindungi.
Proyek ini dibuat untuk tujuan edukasi.
