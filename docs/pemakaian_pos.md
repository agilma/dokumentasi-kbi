# Panduan Pemakaian POS

Panduan ini merupakan cara untuk mengatur dan memakai aplikasi POS yang disediakan oleh Thunderlab. panduan bagian pemakaian POS terdiri dari beberapa bagian:
- [Pengaturan POS](pemakaian_pos.md#pengaturan-aplikasi)
- [Memilih Jenis Layanan](pemakaian_pos.md#pengaturan-aplikasi)
- [Produk dan Voucher](pemakaian_pos.md#pengaturan-aplikasi)
- [Keranjang (Cart)](pemakaian_pos.md#pengaturan-aplikasi)
- [Simpan Keranjang (Save Bill)](pemakaian_pos.md#pengaturan-aplikasi)
- [Pembayaran](pemakaian_pos.md#pengaturan-aplikasi)
- [Daftar Riwayat Transaksi](pemakaian_pos.md#pengaturan-aplikasi)



### Pengaturan POS
Pertama hal yang perlu diperhatikan adalah pengaturan POS, terdapat 2 (dua) jenis pengaturan:
- [Pengaturan Aplikasi](pemakaian_pos.md#pengaturan-aplikasi)
- [Pengaturan Printer](pemakaian_pos.md#pengaturan-printer)

#### Pengaturan Aplikasi
Pengaturan Aplikasi ini terkait dengan pengaturan POS per outlet yang memerlukan penambahan license key yang akan diberikan oleh Admin. Berikut adalah daftar data yang diperlukan untuk pengaturan aplikasi:
- `Outlet`: Pilih outlet di mana aplikasi POS akan diinstal.
- `License Key`: License Key atau Kode yang akan disimpan saat melakukan pengaturan POS, mengikuti Outlet yang dipilih. Setelah itu, tekan tombol "**CHECK**" untuk memeriksa apakah License Key sudah sesuai dengan Outlet yang dipilih. Jika sesuai, akan muncul informasi "**License Key dan Outlet terdaftar**".
- `Nama POS`: Nama ini akan diisi secara otomatis setelah tombol "**CHECK**" ditekan dan berhasil, mengikuti nama yang sesuai dengan License Key yang dimasukkan.
- `Simpan Pengaturan`: Gunakan untuk menyimpan pengaturan tersebut.

#### Pengaturan Printer
Pengaturan Printer digunakan untuk mengatur printer yang akan digunakan untuk mencetak Invoice dan Checker.
- `Jenis Sambungan`: Pilih USB untuk menghubungkan printer yang akan digunakan (Desktop App).
- `Alamat IP Printer`:  Alternatif jika komputer tidak terhubung langsung dengan printer, dapat menggunakan Alamat IP Printer yang terhubung dalam WiFi yang sama.
- `Tambah Printer`: Tekan tombol "**Tambah Printer**" untuk menambahkan printer yang akan dihubungkan.
- `Jenis Printer`: Pilih dari daftar printer yang sudah terpasang driver di komputer. Jika daftar tidak muncul, tekan tombol "**Refresh**" untuk memperbarui daftar printer.
- `Ukuran Kertas`: Sesuaikan dengan tipe printer thermal yang digunakan: `57`, `58`, atau `80`.
- `Nama Printer`: Masukkan label nama untuk mengidentifikasi printer.
- `Tipe Dokumen`: Jika printer untuk `invoice`, pilih **invoice**; jika untuk `checker`, pilih **checker**.
- `Kategori Item`: Kategori item muncul ketika printer bertipe `checker` dan digunakan untuk mengelompokkan kategori menu yang akan dicetak dalam checker. Kategori item bisa lebih dari satu. Untuk menambahkan, pilih jenisnya dan tekan tombol tambah. Untuk menambahkan kategori item lain, pilih kategori item dan tekan tombol tambah.
- `Footer`:  Tambahkan informasi tambahan di akhir halaman.
- `Coba Print`: Untuk menguji koneksi printer. Jika terkoneksi dengan benar, printer akan mencetak.

**Catatan:** Sebelum dapat mengatur printer, pastikan aplikasi ThunderPrint telah terinstal dan dijalankan.

### Memilih Jenis Layanan
Jenis layanan mencakup opsi layanan yang tersedia, seperti `Dine In`, `Take Away`, `Gojek`, `Grab`, dan `Shopee`.

Pilihan-pilihan ini akan muncul secara otomatis setelah pengguna login pada halaman utama (halaman menu). Untuk mengubahnya, cukup tekan jenis layanan di bagian kanan, dan daftar jenis layanan akan muncul.

### Produk dan Voucher
##### Produk
Halaman produk adalah halaman utama yang menampilkan daftar produk yang dijual. Di halaman ini, Anda dapat mencari produk berdasarkan `nama produk` atau `kode produk`, serta mengelompokkan produk berdasarkan `kategori produk`.

Untuk melihat detail produk, termasuk `varian`, `opsi produk`, dan `tambahan`, cukup klik produk tersebut. Halaman detail produk akan muncul, yang memungkinkan Anda untuk menambahkannya ke keranjang dengan menekan tombol "**Tambah**".

Jika Anda ingin menambahkan produk dengan kuantitas lebih dari 1, tekan tombol "**+**" untuk menambahkan jumlahnya atau tombol "**-**" untuk mengurangi jumlahnya sebelum menekan tombol "**Tambah**" untuk memasukkannya ke dalam keranjang.

##### Voucher
Daftar ini berisi transaksi yang akan digunakan dengan aturan yang sesuai dengan persyaratan voucher tersebut. Jika Anda ingin menggunakannya, tekan voucher tersebut untuk melihat informasi detailnya, lalu pindah ke bagian "**Pakai**" dan tekan tombol "**Gunakan Voucher**". Jika penggunaan berhasil, akan ada perubahan dalam daftar keranjang dan pengurangan total sesuai dengan persyaratan voucher tersebut.

### Keranjang (Cart)
Daftar ini berisi produk yang telah dipesan. Jika produk yang diterima tidak sesuai dengan pesanan, tekan tombol "**Ubah**" untuk melihat detail produk, kemudian tekan tombol "**Hapus**" untuk menghapus produk tersebut.

Jika Anda ingin mengubah kuantitas, varian, atau tambahan dari produk, tekan tombol "**Perbarui Produk**".

Jika Anda ingin menambahkan produk yang serupa dengan produk yang sudah ada di dalam keranjang, tetapi dengan penambahan atau perbedaan sedikit, tekan tombol "**Buat Baru**". Ini akan secara otomatis menambahkan produk yang serupa dengan perbedaan tersebut ke dalam keranjang.

### Simpan Keranjang (Save Bill)

### Pembayaran

### Daftar Riwayat Transaksi



**Catatan:** Pengaturan produk, voucher, dan outlet semuanya dapat ditemukan di **ERP Dashboard**.