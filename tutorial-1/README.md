# Tutorial 1 - Game Design Workshop

Selamat datang di tutorial pertama kuliah Game Development! Pada tutorial
perdana ini, kamu akan mulai diajak membiasakan diri dengan _platform_
pelaksanaan tutorial selama satu semester ini, yaitu menggunakan [GitLab](https://gitlab.com) dan [Discord](https://discord.com).
Selanjutnya, kamu akan diajak untuk menyimulasikan proses perancangan game
dalam waktu singkat bermodalkan sebuah tema abstrak, kertas, dan alat tulis.
Di akhir tutorial ini, kamu diharapkan sudah siap mengikuti kegiatan
tutorial-tutorial berikutnya dan mendapatkan gambaran proses perancangan game
secara sederhana.

> Catatan: Jika kamu sudah ingin _programming_ dan menggunakan _game engine_,
> harap bersabar. Tutorial menggunakan _game engine_ secara resmi baru akan
> dimulai pekan depan. Namun karena materi tutorial sudah tersedia sejak awal
> (kecuali beberapa materi tutorial baru tahun ini), maka kamu boleh mengerjakan
> tutorial lebih awal. Pastikan saja kamu mengumpulkan hasil pekerjaan tutorial
> di pekan tutorial terkait dengan tepat waktu.

## Daftar Isi

- [Tutorial 1 - Game Design Workshop](#tutorial-1---game-design-workshop)
  - [Logistik Tutorial](#logistik-tutorial)
  - [Game Design Sederhana](#game-design-sederhana)
  - [Pengumpulan](#pengumpulan)

## Logistik Tutorial

Seperti yang telah disebutkan sebelumnya, tutorial kuliah Game Development
akan menggunakan GitLab dan Discord. GitLab akan digunakan sebagai repositori
kode hasil pengerjaan tutorial. Sedangkan Discord akan digunakan sebagai
sarana komunikasi dan penyampaian materi secara sinkronus oleh tim asisten
ketika sesi tutorial berlangsung.

Jika kamu belum memiliki akun GitLab, maka silakan gunakan waktu di awal
tutorial ini untuk mendaftarkan diri terlebih dahulu di GitLab. GitLab yang
digunakan dalam kuliah ini adalah [GitLab.com](https://gitlab.com). Setelah
mendaftarkan akun, harap tuliskan nama akun kamu di slot pengumpulan tutorial
pekan ini di Scele.

> Catatan: Kamu belum pernah pakai Git? Atau lupa cara pakainya? Silakan
> ikuti tutorial penggunaan Git di [situs Atlassian](https://www.atlassian.com/git).

Selanjutnya, jika kamu belum memiliki akun Discord, maka buatlah akun Discord.
Bagi yang belum tahu atau belum pakai Discord, Discord adalah sarana untuk
_instant messaging_, _voice chat_, dan _streaming_. Anggaplah seperti WhatsApp
atau LINE, namun lebih berorientasi ke kalangan _gamer_. Tutorial GameDev akan
diadakan melalui _streaming_ oleh asisten kuliah di Discord. Selain itu,
Discord juga dapat digunakan sebagai tempat obrol bebas dan diskusi terkait
perkuliahan.

Pranala untuk masuk ke server Discord kuliah Game Development dapat dilihat di
Scele. Silakan masuk ke server, lalu pahami tata tertib di server dan minta
_role_ `Mahasiswa` melalui _bot_ yang _standby_ di server Discord.

Sudah buat akun GitLab dan masuk ke server Discord kuliah? _Good!_
Saatnya langsung masuk ke sesi materi sesungguhnya.

## Game Design Sederhana

> Harap persiapkan hal-hal berikut sebelum memulai kegiatan:
>
> - Dokumen Microsoft Word/Google Docs kosong untuk menuliskan jawaban
> - Satu lembar kertas kosong berukuran maksimal A4
> - Alat tulis
> - Kamera/_scanner_ untuk mengambil foto corat-coret (tulisan, gambar) di
>   kertas

Pada kuliah Game Development ini, kamu akan dilatih untuk berpikir dan menyelesaikan masalah dengan pendekatan yang bisa dibilang agak
_out-of-the_box_. Kuliah ini bukan seperti kuliah pemrograman-pemrograman
dasar yang mengharuskan peserta kuliah membuat program untuk mengolah masukan
dan mencetak keluaran sama persis seperti yang tercantum di dokumen spesifikasi
tugas. Kebenaran dan kesesuaian dengan spesifikasi memang penting, namun kuliah
ini juga mengharapkan solusi yang unik dan kreatif.

Salah satu kegiatan kreatif yang akan disimulasikan hari ini adalah proses
pencarian ide dalam merancang game. Mungkin beberapa dari peserta kuliah sudah
memiliki ide game yang ingin dikembangkan pada kuliah ini. Mungkin ada juga
peserta kuliah yang masih mencari-cari ide. Terlepas apakah sudah ada ide atau
belum, mari kita coba bersama latihan berikut untuk merancang sebuah game!

Pertama, coba kita saling _sharing_ terlebih dahulu. Coba jawab
pertanyaan-pertanyaan berikut dan berbagi jawabannya dengan rekan-rekan
sekelas:

> - Pertanyaan 1: Apakah kamu punya game favorit? Coba deskripsikan secara
>   singkat!
> - Pertanyaan 2: Apakah game tersebut masih dimainkan? Mengapa?
> - Pertanyaan 3: Apa hal berkesan ketika memainkan game tersebut?
>
> - _Instruksi kepada **asisten**: Silakan fasilitasi diskusi selama 15 menit. Tunjuk 1 - 3 mahasiswa secara acak untuk sharing._
> - _Instruksi kepada **peserta kuliah**: Silakan tulis jawaban di Microsoft Word/Google Docs. Jawaban boleh dituliskan dalam format bullet points._

Apapun game yang pernah rekan-rekan mainkan, setiap game memiliki _player experience goal_ yang ingin disampaikan oleh perancang game (_game designer_)
kepada para pemain. Sebagai contoh:

- Ada game yang dirancang untuk membuat pemain bekerjasama untuk memenangkan
  tantangan, namun pada saat yang bersamaan harus tetap waspada terhadap sesama
  pemain lainnya (misal: Project Winter, Among Us, Werewolf).
- Ada game yang ingin memberikan sensasi kebebasan untuk menyelesaikan
  tujuan-tujuan di dalam game tanpa terkekang oleh urutan penyelesaiannya
  (misal: game-game _open-world_, seperti The Legend of Zelda: Breath of
  the Wild).

> _Instruksi kepada **asisten**: Silakan jika mau menambahkan contoh lain._
> Mungkin bisa dari contoh game populer yang terakhir kali kalian mainkan.

Untuk mencapai _experience_ yang diinginkan, maka _game designer_ akan
merancang elemen-elemen pada game yang akan saling bersinergi untuk membuat
pemain mencapai _experience_ tersebut. Elemen-elemen dasar pada permainan
dapat mengacu ke buku Fullerton "Game Design Workshop: A Playcentric Approach" (i.e., elemen formal, elemen dramatis, dinamika sistem)
dan/atau buku Schell "The Art of Game Design" (i.e., estetika, teknologi, cerita, mekanik).

Di tutorial ini, kita coba mulai sederhana dulu, yaitu dari segi cerita dan
mekanik permainan. Misalnya, kamu diminta untuk merancang sebuah game dengan
ide abstrak sebagai berikut: _**"Balapan dari sebuah tempat asal ke tempat tujuan."**_

> - Pertanyaan 4: Coba kamu pikirkan sebuah _experience_ yang ingin kamu
>   tanamkan kepada pemain ketika pemain tersebut memainkan game "balapan" ini.
> - Pertanyaan 5: Saatnya kamu pakai kertas kosong. Gambarkan dua buah titik
>   di kertas, misalnya titik A dan titik B. Posisi kedua titik ini diharapkan
>   cukup jauh di atas kertas.
> - Pertanyaan 6: Gambarlah sebuah garis yang menghubungkan titik A dan titik B.
>   Garisnya boleh lurus, berlika-liku, putus-putus, dan lain-lain. Silakan
>   berkreasi.
> - Pertanyaan 7: Bayangkan sebuah cerita yang dapat terjadi ketika ada balapan
>   dari sebuah tempat asal ke tempat tujuan. Usahakan cerita masih ada kaitan 
>   dengan _experience_ yang telah dituliskan sebelumnya. Beberapa pertanyaan 
>   pemicu yang dapat membantu menuliskan ide cerita:
>   - Siapa tokoh utama (protagonis) dalam cerita balapan?
>   - Siapa tokoh lawan (antagonis) dalam cerita balapan?
>   - Mengapa mereka balapan? Apakah untuk mendapatkan hadiah? Menyelamatkan
>     putri yang diculik? Atau sekedar iseng? _Silakan berkreasi!_
>   - Dimana dan kapan balapan ini terjadi? Apakah di dunia pertengahan abad 15?
>     Di luar angkasa? Di dalam tubuh? Atau di tempat dan waktu lainnya? _Silakan berkreasi!_
>   - Apa alat yang akan digunakan oleh tokoh-tokoh di dunia cerita ini ketika >     balapan? Apakah menggunakan pesawat terbang? Kapal? Lari? Monster? 
>     _Silakan berkreasi!_
> - Pertanyaan 8: Gambarkan, dalam bentuk sketsa gambar atau _bullet points_ tulisan, gambaran visual dari dunia cerita pada kertas. Jangan lupa untuk dikaitkan dengan _experience_ yang diinginkan. Misal: bila balapan
>   terjadi di dunia abad pertengahan, mungkin kamu bisa menggambarkan kastil
>   di titik A dan B, lalu ada gambar hutan dan sungai di sepanjang garis yang
>   menghubungkan titik A dan B. _Gunakan imajinasimu!_
> - Pertanyaan 9: Deskripsikan bagaimana apa saja aksi dan aturan permainan yang
>   perlu diketahui oleh pemain ketika bermain game balapan ini. Apakah nanti
>   pemain akan bergiliran untuk menggerakkan kendaraannya? Atau bergerak
>   secara _real-time_? Apakah akan ada kondisi tertentu yang membuat pemain
>   atau lawannya memiliki keuntungan selama bermain? Apakah akan ada semacam
>   objek atau kekuatan spesial yang bisa dipakai pemain/lawan?
>   _Silakan berkreasi!_
>
> - _Instruksi kepada **asisten**: Silakan fasilitasi diskusi dan pengerjaan selama 45 menit. Tunjuk 1 - 3 mahasiswa secara acak untuk sharing._
> - _Instruksi kepada **peserta kuliah**: Silakan tulis dan ilustrasikan jawaban-jawaban dari pertanyaan 4 - 8 di selembar kertas. Boleh bolak-balik atau menambah kertas apabila ruang kosong di kertas tidak cukup untuk menampung ide kamu._

Di akhir tutorial ini, kurang lebih kamu telah menempuh proses kilat dalam
merancang sebuah game. Tentu saja proses yang lebih rinci akan kamu tempuh
ketika mengerjakan proyek kelompok di kuliah ini. Masih ada beberapa hal
yang belum sempat didiskusikan melalui sesi tutorial ini, seperti:

- _Platform_ dan teknologi yang akan digunakan dalam membuat dan memainkan game ini, seperti PC, _smartphone_, _console_.
- Kebutuhan akan aset-aset digital seperti gambar, suara, musik, model 3D, dan sebagainya.
- Target pasar dan demografi pemain yang akan memainkan game.
- Perencanaan proyek dan fase-fase pengerjaan game.
- Dan lain-lain.

Jika masih penasaran, silakan finalisasi pengisian IRS di SIAK dan selamat
bergabung di kuliah Game Development!

## Pengumpulan

Harap kumpulkan:

- Nama akun [GitLab.com](https://gitlab.com) kamu di slot pengumpulan **khusus akun GitLab** di Scele.
- Dokumen PDF berisi jawaban tertulis latihan-latihan selama tutorial dan foto
  corat-coret kertas di slot pengumpulan **khusus hasil tutorial** di Scele.

Tenggat waktu pengumpulan adalah **Jumat, 18 September 2020, pukul 21:00**.
