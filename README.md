# KartuAnggotaPotret
Modifikasi Kartu Anggota SLiMS 9 Bulian Classic menjadi Potret

Modifikasi Plugin SLIMS: Rotasi Kartu Anggota dari Landscape ke Potret
Pada modifikasi kali ini, saya melakukan perubahan pada plugin SLIMS terkait tampilan kartu anggota. Perubahan utama yang dilakukan adalah mengubah orientasi kartu anggota dari yang sebelumnya landscape (horizontal) menjadi potret (vertikal).

Modifikasi ini bertujuan untuk meningkatkan kemudahan dalam pencetakan dan penggunaan kartu anggota, serta menyesuaikan dengan kebutuhan pengguna yang lebih sering menggunakan format potret dalam kegiatan sehari-hari.

Detail Perubahan:
- Mengubah orientasi kartu anggota dari landscape ke potret.
- Menyesuaikan layout dan desain kartu agar tetap rapi dan informatif dalam format vertikal.
- Memastikan kompatibilitas dengan printer dan perangkat yang digunakan.

Silakan dicoba dan berikan masukan jika ada kendala atau saran untuk perbaikan lebih lanjut. Terima kasih!

Cara:
1. edit printed.settings.inc  di folder admin/admin_template 
pada line box width dan box height, ubah menjadi seperti dibawah:
.
// Cardbox Settings
$sysconf['print']['membercard']['box_width'] = 5.4;
$sysconf['print']['membercard']['box_height'] = 8.6;
.
2. backup membercard.php yang ada di folder files/membercard/classic .. bisa dicopy atau rename (misal menjadi membercard_lanscape.php)
3. copy membercard.php yg diunduh, kemudian paste di folder files/membercard/classic

Silahkan dicoba!
