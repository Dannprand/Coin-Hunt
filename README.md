Coin Hunt — Human vs AI

Persyaratan untuk menjalankan Coin Hunt
  - Python (minimal versi 3.10 atau lebih baru)  
  - Microsoft Visual Studio Code (minimal versi 1.105.1)  
  - Code Runner (ekstensi tambahan di Visual Studio Code)  
  - Komputer/laptop (Windows, macOS, Linux) atau **Virtual Machine**

IDE yang digunakan
- Microsoft Visual Studio Code** (minimal versi 1.105.1)

Library yang digunakan dalam aplikasi
- `pygame` untuk tampilan GUI, animasi, dan interaksi pengguna  
- `random` untuk menentukan posisi acak koin  
- `math` untuk perhitungan posisi dan jarak  
- `typing` untuk anotasi tipe data agar kode lebih rapi dan mudah dibaca  

Cara mengunduh aplikasi Coin Hunt
1. Buka halaman GitHub proyek kamu (misalnya):  
   [https://github.com/username/coin-hunt](https://github.com/Dannprand/Coin-Hunt)
2. Klik tombol hijau “<> Code”
3. Klik “Download ZIP"
4. Ekstrak (unzip) file ZIP yang sudah diunduh.

Cara menjalankan aplikasi
1. Buka Microsoft Visual Studio Code
2. Klik menu “File” di kiri atas → pilih “Open File…”
3. Cari dan buka file utama game, misalnya:  
   `coin_hunt.ipynb`
4. Setelah file terbuka, klik tombol Play (▶) di pojok kanan atas.  
   > Klik sekali saja agar tidak menjalankan program ganda.
5. Tunggu beberapa detik hingga jendela pop-up bertuliskan  
   “COIN HUNT — Human vs AI” muncul di layar.

Cara bermain Coin Hunt
Tujuan
Kumpulkan koin emas sebanyak mungkin sebelum AI mengalahkanmu!  
Kamu bermain sebagai manusia (biru) dan AI berwarna merah.

Aturan Dasar
- Gunakan tombol panah (↑ ↓ ← →) untuk bergerak di papan.  
- Setiap kali kamu menyentuh koin, kamu akan mendapatkan 1 poin.  
- AI juga akan bergerak otomatis untuk mencari dan mengambil koin.  
- Jika semua koin sudah diambil, permainan akan berakhir.

Kondisi Menang & Kalah
- Jika skor kamu lebih tinggi -> You Win!
- Jika AI mengumpulkan lebih banyak -> You Lose
- Jika sama -> Draw

Restart Game
Tekan tombol R di keyboard untuk mengulang permainan dari awal.

Mode Permainan
- Saat memulai, kamu akan melihat beberapa pilihan tingkat kesulitan:
  - Easy (5x5) — jumlah koin: 13  
  - Normal (7x7) — jumlah koin: 13  
  - Hard (9x9) — jumlah koin: 13  
- Pilih level yang kamu inginkan untuk memulai.

AI Behavior
  - AI bergerak otomatis menuju koin terdekat menggunakan algoritma Greedy Algorithm.  
  - AI tidak dapat melewati posisi kamu, jadi kamu bisa memblokir jalannya untuk keuntungan strategis.  
  -  Setiap giliran bergantian antara pemain dan AI dengan animasi yang halus.

Fitur Tambahan
  - Animasi Gerakan — Karakter bergerak dengan efek transisi (lerp).  
  - Skor Panel — Menampilkan skor kamu dan AI secara real-time.    
  - Level dan Ronde — Bisa memilih jumlah ronde dan tingkat kesulitan.  
  - Desain Responsif — Ukuran jendela dapat diubah tanpa mengacaukan layout.

Tampilan Utama
  - Menu Awal: Tombol "Click to Begin"
  - Select Level: Pilihan Easy, Normal, atau Hard
  - Gameplay: Papan grid berisi koin dan dua karakter
  - Panel Bawah: Menampilkan giliran dan skor pemain
  - Top Bar: Menunjukkan ronde dan nama level
