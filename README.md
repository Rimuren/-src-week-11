# Master_plan

### Nama : M.ismatullah.s.s
### Nim : 362358302099
#
### Praktikum 1 :
#
1. Selesaikan langkah-langkah praktikum tersebut, lalu dokumentasikan berupa GIF hasil akhir praktikum beserta penjelasannya di file README.md! Jika Anda menemukan ada yang error atau tidak berjalan dengan baik, silakan diperbaiki.
#
2. Jelaskan maksud dari langkah 4 pada praktikum tersebut! Mengapa dilakukan demikian?

- - A. Mempermudah Impor: Dengan adanya data_layer.dart, kita bisa mengimpor kedua model tersebut hanya dengan satu baris kode di file lain. Ini membuat kode lebih bersih dan mengurangi kemungkinan kesalahan atau kelupaan mengimpor salah satu model.

- - B. Sentralisasi: Ini menciptakan titik sentral untuk semua impor terkait data. Jika di masa depan ada perubahan atau penambahan model baru, kita hanya perlu memperbarui data_layer.dart dan tidak perlu mencari dan mengubah semua file yang mengimpor model-model tersebut.
#
3. Mengapa perlu variabel plan di langkah 6 pada praktikum tersebut? Mengapa dibuat konstanta ?

- - diperlukan untuk menyimpan data terkait daftar tugas yang akan ditampilkan dan dikelola di dalam aplikasi. plan adalah sebuah instance dari kelas Plan yang menyimpan informasi tentang rencana dan daftar tugas yang terkait dengan rencana tersebut. Dengan adanya variabel plan, kita dapat mengelola state aplikasi dan memperbarui UI berdasarkan perubahan data di dalam variabel tersebut.
- - Dengan menjadikannya konstanta, kita memastikan bahwa nilai awal dari plan tidak akan berubah secara tidak sengaja setelah inisialisasi. membantu menjaga konsistensi data dan menghindari bug yang mungkin muncul karena perubahan data yang tidak disengaja.
#
4. Lakukan capture hasil dari Langkah 9 berupa GIF, kemudian jelaskan apa yang telah Anda buat!
#
5. Apa kegunaan method pada Langkah 11 dan 13 dalam lifecyle state ?

- - A. Inisialisasi: Method initState() dipanggil sekali ketika objek State pertama kali dibuat. Ini digunakan untuk melakukan inisialisasi yang hanya perlu dilakukan sekali.

- - B. ScrollController: Diinisialisasi di sini untuk mengontrol perilaku scroll dari ListView. Listener ditambahkan untuk menghapus fokus dari semua TextField ketika event scroll terjadi.
#
- Kegunaan dispose():
- - A. Pembersihan: Method dispose() dipanggil ketika objek State dihapus secara permanen. Ini digunakan untuk membersihkan resource yang digunakan oleh State, seperti controller yang tidak lagi diperlukan.

- - B. ScrollController: Di-dispose di sini untuk melepaskan resource yang digunakan oleh ScrollController, mencegah kebocoran memori.
#



- Tugas_4
- - ![Screenshot](lib/assets/hasilPrak1.png)

- Hasil :
- - ![Screenshot](lib/assets/hasilPrak1.png)
#

### Praktikum 2 :
- - ![Screenshot](lib/assets/Prak2.1.png)
- - ![Screenshot](lib/assets/Prak2.2.png)
#

### Praktikum 3 :
- - ![Screenshot](lib/assets/Prak3.1.png)
- - ![Screenshot](lib/assets/Prak3.2.png)
#
