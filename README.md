Tolong buatkan aplikasi web satu halaman (single-page application) menggunakan HTML, CSS, dan JavaScript untuk game tebak warna kartu. Berikut adalah spesifikasi lengkapnya:

1. Pengaturan Awal (State Management)
- Modal Awal: Saat website pertama kali dimuat, tampilkan popup yang meminta pemain memilih modal awal dengan rentang antara Rp10.000 hingga Rp100.000.
- Saldo Tersedia: Tampilkan jumlah saldo di bagian atas layar secara real-time.
- Jumlah Taruhan: Sediakan kolom input untuk memasukkan uang taruhan. Taruhan tidak boleh melebihi saldo.

2. Mekanisme Permainan
- Pilihan Warna: Sediakan 4 tombol tebakan warna untuk pemain: Hijau, Kuning, Biru, dan Merah.
- Proses Pengundian: Tampilkan sebuah visual kartu tertutup di layar. Saat pemain mengklik salah satu tombol warna, sistem akan mengundi warna kartu secara acak dari 4 pilihan tersebut.
- Animasi Buka Kartu: Buat efek animasi kartu berputar atau terbalik (flip) yang sedikit dilambatkan untuk memberi efek tegang sebelum warnanya terungkap.

3. Logika Menang dan Kalah
- Kondisi Menang: Jika warna tebakan cocok dengan warna kartu, pemain mendapatkan keuntungan dengan persentase acak antara 10% hingga 1000% dari uang yang dipertaruhkan. Tambahkan keuntungan ini ke saldo utama.
- Kondisi Kalah: Jika tebakan warnanya berbeda, uang taruhan hangus 100%. Kurangi saldo utama sejumlah uang taruhan tersebut.
- Game Over: Jika saldo mencapai Rp0, munculkan pesan bermain lagi yang ceria dan tombol Restart untuk mengulang permainan.

4. Efek Interaktif dan Kejutan (Surprise Element)
- Animasi Kejutan: Tambahkan elemen kejut (jumpscare ringan yang lucu) berupa animasi karakter bergaya anime yang tiba-tiba muncul membesar di layar sesaat setelah kartu terbuka. 
- Reaksi Menang/Kalah: Jika kalah, karakter tersebut muncul dengan ekspresi konyol, terjatuh, atau tertawa lucu agar pemain terkejut tapi malah ikut tertawa. Jika menang, karakternya muncul dengan ledakan kembang api dan ekspresi sangat girang.
- Efek Untung Acak: Saat menang, buat angka persentase keuntungan (misal: "SELAMAT! UNTUNG 850%!") muncul melompat ke layar dengan huruf yang sangat besar secara tiba-tiba agar pemain kaget dan antusias.

5. Desain Visual (UI/UX)
- Tema Desain: Warna-warni seperti pelangi, super ceria, menyenangkan, dan penuh energi.
- Latar Belakang: Gunakan gradasi warna pelangi cerah yang warnanya bisa bergeser atau bergerak perlahan.
- Tata Letak: Saldo di atas, kartu yang diundi di tengah, 4 tombol warna-warni berderet rapi di bawah kartu, dan input taruhan di bagian bawah. Pastikan semuanya responsif di desktop maupun mobile.
