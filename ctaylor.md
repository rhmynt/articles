# Design History

Desain ini dibuat karena termotivasi tugas kuliah

## Version 1.00 

Karena ini baru pertama kali membuat desain ini, jadi ini merupakan desain pertama.

# Game overview

## Filosofi

Game ini adalah game slide-scrolling platformers (single-player). Pemain akan memainkan game ini dengan berlari dari titik mula hingga titik akhir. Selama bermain, pemain akan menemui rintangan dan juga akan ada level yang dapat dicapai. Sepanjang perjalanan pemain, game ini akan menyuguhkan berbagai macam budaya dan ciri khas internasional yang dapat menambah pengetahuan pemain berdasarkan level. Meskipun ini game platform, game ini memiliki cerita yang mendasari kenapa pemain harus berlari sepanjang perjalan dan pemain juga memiliki tujuan akhir yang dapat ditemui bila menyelesaikan game ini. Pemain akan diberi clue pada perjalanan yang membuat pemain penasaran kenapa dia harus menemui titik akhir game. 

Game ini akan beroperasi pada OS Android karena banyaknya sarana, source yang mudah, dan gratis yang dapat ditemukan di internet untuk pembuatan game ini. Di sisi lain, gadget yang paling sering digunakan dan paling dekat dengan pemain adalah handphone, jadi kami mengincar target pasar yang massive penggunanya.  

## Common Question

### Game apa?
Game ini berjudul Run Pass World. Sesuai dengan namanya, pemain dituntut berlari hingga akhir permainan. Pemain tidak bisa mundur ataupun berhenti. Bila menemui rintangan, pemain bisa mengambil aksi untuk menghindarinya. Game platform ini memiliki cerita dasar yang memotivasi pemain untuk menyelesaikannya. Level disajikan untuk pemain dengan tampilan berbagai background dari beberapa negara internasional.

### Kenapa membuat game ini?
Kami banyak menjumpai game-game dengan tipe platform. Meskipun game ini sederhana, tapi banyak membuat pemainnya kecanduan. Game ini bisa dibuat banyak sekali variasinya, walaupun hal sederhana, terkadang hal itulah yang membuat pemain kecanduan akan game tersebut.

### Latar tempat dan waktu  game?
Game ini mengambil latar tempat berbagai negara. Start awal berada di hutan Amazon dan finish di Indonesia. Latar waktu adalah waktu kekinian. Suasana berubah berdasar level. Tiap level berupa sebuah negara yang harus dilalui

###  Kontrol pemain?
Pemain dapat lompat atau sliding dan melempar sesuatu untuk menghancurkan rintangan tertentu.

### Jumlah karakter yang dapat dikendalikan?
Karena ini game platform, otomatis hanya 1 karakter.

### Fokus utama game?
Yakni menyelesaikan level dan sampai di finish. Setelah itu mendapatkan jawaban mengenai mengapa si pemain harus kembali.
Perbedaan dengan game lain? 
Game platform ini memiliki alur cerita yang membuatnya menarik. Selain itu, dalam game ini disajikan pengetahuan mengenai budaya dan ciri khas budaya negara internasional

# Feature Set

## General Feature
1.	2D view player (32 bit color)
2.	Moving background
3.	Build up by various country that set for every level
4.	Rintangan unik dan bervariasi
## Single player
1.	Memiliki base story
## Editor
1.	Naik level berdasarkan waktu dan poin yang diperoleh
## Gameplay
1.	Pemain bisa lompat, sliding, melempar object untuk menghancurkan rintagan
2.	Pemain diberi waktu hitung untuk bermain
3.	Collect poin
4.	Mengikuti alur cerita

# The Game World

## Overview
Setting latar tempat dan tempat adalah dunia nyata yang sesungguhnya dan waktu sekarang. 

## World Feature 1
Setting tempat berdasar pada negara tertentu berdasarkan dengan level. Pada level tersebut, ditunjukkan keunikan dari negara tersebut.

## World feature 2 
Setting tempat memiliki lajur cerita tertentu bagi pemain yang mengacu pada ending game.

## World Feature 3
Object dan rintangan yang disediakan berkaitan dengan negara pada level tersebut

## Physical World

### Overview
Negara yang ditempuh pemain untuk mencapai tujuan akhir yakni rumah. Mulai dari bagian Amerika sampai ke Asia
### Key Location
Bagian wilayah dari negara yang menjadi kunci tiap level :
1.	Hutan Amazon (Starting point)
2.	Grand Canyon (US)
3.	Greenland (Snow Land)
4.	Inggris
5.	Prancis
6.	Itali
7.	Turki
8.	Siria
9.	Saudi Arabia
10.	India
11.	Thailand
12.	Indonesia (Finish)

### Travel 
Pemain berlari sepanjang perjalanan. Mungkin juga untuk mendapat tumpangan dengan sebuah kendaraan.

### Scale
Meskipun game ini menyuguhkan setting berbagai negara, kami hanya akan menunjukkan beberapa spot unik dari negara tersebut. Misalnya untuk Perancis, kita akan membuat setting negara Eiffel.

### Objects
Object yang ditampilkan di game ini adalah object yang lumrah yang ada pada negara tersebut. Contohnya di India akan terlihat bajaj.

### Weather 
Cuaca yang ada pada game ini bergantung pada iklim yang ada pada negara tersebut. Contohnya di Greenland adalah negara yang dominan ditutupi salju. Kemungkinan akan dibuat setting cuaca badai salju pada level tersebut.

### Day and Night 
Pada game ini, pemain hanya akan melewati suatu negara pada 1 hari. Jadi akan ada siang dan malam di masing-masing level (negara).

### Time 
Perhitungan waktu berdasar pada ketentuan di atas. Karena kami menyediakan 12 negara, dan tiap negara memiliki waktu day and night masing-masing dan itu diwakilkan dalam hitungan menit yang dipercepat.

## Rendering

### Overview
Rendering pada game ini dibuat berdasarkan software pembuat (?)

### 2D Rendering

## Camera
Kamera dibuat statis. Kamera dibuat pada posisi disamping kanan pemain. 

## Game Engine 
Libgdx (?)
XXXXXXXXXXXXXXXXXXX

## Lighting models 
Lighting berdasar pada gambar yang akan digunakan.

# The World Layout
Tampilan dunia pada game ini sama seperti game slide scrolling pada umumnya. Akan ditampilkan pijakan dan rintangan yang bisa saja berada pada udara atau di atas pijakan atau pun muncul tiba-tiba. Background akan dibuat statis atau hanya akan looping (untuk jarak benda yang berada sangat jauh, contoh background langit atau pemandangan kota)

# Game Characters
Game karakter adalah seorang pria paruh baya.

## Creating character
Pria yang menjadi karakter utama dalam game ini adalah seorang yang berpenampilan seperti pengusaha. Karena game ini adalah Platformers, karakter dibuat tidak terlalu kuat. Meskipun begitu, berdasar pada ceritanya, pria ini adalah orang yang berdedikasi dan peduli.

# User Interface 
XXXXXXXXXX (?)

# Weapon
Batu yang dilempar pemain.

# Single-Player Game


# Music Scores and Sound Effect

## Overview
Tujuan ada musik pada game adalah untuk dapat menciptakan suasana yang sesuai dengan keadaan yang sesungguhnya. Terdapat beberapa soundtrack. Soundtrack sesuai dengan negara yang dikunjungi. 

## Sound FX
Terdapat sound untuk Interaksi GUI dengan user seperti pada saat menyentuh tombol Menu, pengaturan dan lain lain. Permainan ini memiliki efek khusus untuk membangun suasana yang lebih terasa oleh pemain. Apa yang terjadi pada game ini ditunjukan dengan efek suara. Misalkan pada saat sedang berlari atau terjatuh.  


