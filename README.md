# Pemetaan-Area-Sawah-Padi-di-Kedungpring-Lamongan

# Tentang Proyek
Proyek ini bertujuan untuk melakukan pemetaan area persawahan, dengan fokus utama pada lahan sawah padi di Kecamatan Kedungpring, Kabupaten Lamongan. Melalui penggunaan perangkat lunak QGIS, proyek ini mencakup tahapan pemetaan spasial dan digitasi poligon area persawahan. Setelah tahapan pemetaan dan digitasi tersebut diselesaikan, alur kerja dirancang agar dapat dilanjutkan ke tahap ekstraksi dataset. Proses pembuatan dataset ini memanfaatkan plugin Deepness pada QGIS guna menghasilkan data latih berbasis citra spasial.

# Panduan Instalasi
Untuk dapat menjalankan proyek ini dan melakukan pembuatan dataset, Anda perlu menginstal QGIS dan mengonfigurasi plugin Deepness. Berikut adalah langkah-langkahnya:

1. Instalasi QGIS
- Kunjungi situs web resmi QGIS di https://qgis.org/.
- Unduh installer QGIS versi terbaru atau versi LTR (Long Term Release) yang lebih stabil (disarankan versi 3.22 atau lebih baru agar kompatibel dengan Deepness).
- Jalankan file installer yang sudah diunduh.
- Ikuti instruksi instalasi pada layar (klik Next, setujui License Agreement, dan pilih lokasi instalasi).
- Tunggu hingga proses instalasi selesai, lalu buka aplikasi QGIS Desktop.

2. Instalasi Plugin Deepness di QGIS
- Buka aplikasi QGIS yang telah terinstal.
- Pada menu bar di bagian atas, klik menu Plugins > Manage and Install Plugins...
- Tunggu beberapa saat hingga QGIS memuat daftar repositori plugin.
- Pada jendela Plugins, pilih tab All di panel sebelah kiri.
- Di kolom pencarian (Search), ketikkan "Deepness".
- Klik pada plugin Deepness yang muncul di hasil pencarian.
- Klik tombol Install Plugin di pojok kanan bawah.
- Tunggu hingga proses instalasi selesai. Jika muncul peringatan untuk menginstal dependensi tambahan (seperti Python packages tambahan), setujui atau ikuti instruksi yang diberikan oleh QGIS.
- Setelah berhasil diinstal, plugin Deepness akan muncul di tab Installed atau Anda bisa mengaksesnya melalui menu bar di QGIS (biasanya muncul ikon Deepness pada toolbar).
- Setelah tahapan di atas selesai, Sudah siap untuk memulai ekstraksi dataset menggunakan Deepness.

3. Menjalankan Proyek
- Download proyek pada repository ini.
- Ekstrak file zip-nya lalu buka folder hasil ekstraksi.
- Jalankan file yang bernama Kedungpring.qgz.
- Jika sudah dibuka, maka akan muncul secara otomatis peta untuk pemetaan lahan sawahnya.
- Jika ingin melanjutkan untuk membuat dataset, lakukan ekstraksi menggunakan plugin Deepness yang telah diinstal.
