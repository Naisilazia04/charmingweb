# Membuat aplikasi web wallpaper dengan figma,netbeans,java swing,mySQL
Naisila zia ulhaq 24 oktober 2023

# Latar belakang
wallpaper, yang juga dikenal sebagai wallpaper komputer atau desktop wallpaper, adalah gambar atau desain yang digunakan sebagai latar belakang layar pada komputer, laptop, tablet, atau ponsel. Latar belakang wallpaper ini muncul di latar belakang layar ketika kita tidak sedang menggunakan aplikasi atau tugas tertentu.

# Deskripsi  
aplikasi walpaper adalah satu jenis aplikasi yang diminati oleh pengguna ponsel pintar , alasan saya kenapa aplikasi ini di buat? ? dari yang saya ketahui dengan membuat aplikasi walpaper ini  orang sering ingin  mempersonalisasi tampilan ponsel mereka dengan gambar atau latar belakang yang sesuai dengan selera mereka.contohnya aplikasi wallpaper ini dapat menyediakan wallpaper berdasarkan berbagai tema, seperti warna,karakter film atau game populer, atau juga seni.

# Analysis : Branding

Pada tahap ini kita mengeksplorasi branding dari sistem yang di buat . Branding meliputi :

• Merk : Charming

• Tagline : Ubah layar anda dengan keindahan setiap hari

• Campaign : aplikasi yang membuat penggunanya menampilkan kreativitas dengan sentuhan layarnya

• Usia 7+

• seorang yang ingin meningkatkan estetika lewat sentuhan layarnya

• seorang yang butuh inspirasi dan motivasi 

• seorang yang ingin menampilkan hal baru dalam sentuhan layar

• User experience them :

• Mudah
  
• sederhana 
  
• Menakjubkan

• Warna : Ungu purple
  
# inspirasi desain

![image](https://github.com/Naisilazia04/charmingweb/assets/144526940/1af6d539-efc8-47dc-aada-1d206abcdb84)

# Analysis : User Story

Pada tahap ini kita mengeksplorasi kebutuhan prioritas dari para pengguna untuk kita wujudkan sebagai fitur pada sistem atau aplikasi yang akan dibuat. User story memudahkan kita membuat prioritas fitur-fitur untuk dikerjakan untuk jangka waktu tertentu.

| sebagai | saya ingin bisa | sehingga | prioritas |
|-----|-----|-----|--------|
|pengguna|dapat mencari wallpaper berdasarkan kategori atau tema tertentu|bisa dengan mudah menemukan gambar latar belakang yang sesuai dengan selera saya|⭐⭐⭐⭐⭐|
|pengguna|mendapatkan pemberitahuan ketika wallpaper baru di tambahkan ke aplikasi|saya tidak melewatkan wallpaper yang menarik |⭐⭐⭐|
|pengguna|ingin mendapatkan rekomendasi wallpaper berdasarkan preferensi|saya tidak bosan dengan  tampilan wallpaper saya  |⭐⭐⭐⭐|
|pengguna|dapat mengunduh wallpaper dengan cepat dan mudah|tidak perlu menghabiskan banyak waktu dalam proses unduh|⭐⭐⭐⭐⭐|
|pengguna|dapat mengatur wallpaper berdasarkan kategori musik favorit saya|saya bisa merayakan kecintaan saya pada musik melalui latar belakang wallpaper|⭐⭐⭐⭐|
|pengguna|menyinkronkan koleksi berbagai wallpaper saya di perangkat|sehingga saya memiliki wallpaper favorit saya|⭐⭐⭐|
|pengguna|memiliki opsi untuk menyimpan wallpaper favorit saya dalam daftar koleksi|saya bisa mengaksesnya dengan mudah|⭐⭐⭐⭐|
|pengguna|dapat mengatur wallpaper sebagai latar belakang ponsel saya|perangkat saya terlihat lebih menarik|⭐⭐⭐⭐⭐|
|pengguna|dapat melihat daftar wallpaper yang sudah saya unduh sebelumnya|bisa mengakses gambar wallpaper yang pernah saya sukai|⭐⭐⭐⭐|
|pengguna|memiliki opsi untuk mencari wallpaper berdasarkan warna tertentu|bisa menyesuaikannya dengan selera warna saya|⭐⭐⭐⭐⭐|
|pengguna|memiliki opsi untuk mengatur wallpaper berdasarkan karakter kartun atau tokoh terkenal| ponsel saya lebih menarik|⭐⭐⭐⭐⭐|
|pengguna|dapat memotong dan mengubah ukuran wallpaper sebelum mengatur sebagai latar belakang |saya dapat menyesuaikannya dengan tampilan wallpaper saya|⭐⭐⭐⭐⭐|
|pengguna|dapat melihat daftar wallpaper yang paling populer saat ini|saya bisa tahu tren terkini|⭐⭐⭐⭐⭐|

# Analysis: Structure data

<img width="761" alt="image" src="https://github.com/Naisilazia04/charmingweb/assets/144526940/3f0a89aa-1896-4c5e-9b15-86b2f118f075">


• Pada tahap ini kita mengeksplorasi dan menganalisis bentuk struktur data yang mampu memfasilitasi user story yang ada, maupun yang kemungkinan besar dibutuhkan di kemudian hari
• Kita akan merepresentasikan Entitas pada aplikasi dalam bentuk tabel Entitas dan atribut


# Design: Arsitektur berbasis client-server

![image](https://github.com/Naisilazia04/charmingweb/assets/144526940/14ed94df-6384-47a6-b45a-833805f5bd12)

• pada tahap ini kita merancang arsitektur berikut teknologi yang terdapat pada setiap komponen pembentuk aplikasi.

flowchart BT 


    B[Web Server: JavaScript - Express.js]
    <-->
    C[Aplikasi Web Backend: JavaScript - Express.js] 
    C <--> 
    D[Database: PostgreSQL] 
    
    end
    A[Aplikasi Android & iPhone: JavaScript - React Native] <--> B


# Deskripsikan teknologi, library, dan framework apa saja yang kamu gunakan dalam membangun produk ini
Dalam pembuatan aplikasi wallpaper, menggunakan Figma, NetBeans Java Swing, dan database MySQL, 
 Pertama, saya  merancang tampilan antarmuka pengguna (UI) aplikasi saya dengan Figma. dan desain untuk halaman unggah wallpaper, halaman utama. setelah itu menentukan tata letak, warna, dan komponen seperti tombol dan label sesuai dengan desain saya.
 Setelah desain UI selesai, ekspor elemen UI yang kita butuhkan dalam format gambar.Lalu,
Buat proyek baru di NetBeans dengan jenis Java Swing.karena akan menjadi kerangka kerja pengembangan aplikasi ini.setelah itu,
 Tambahkan komponen-komponen Swing seperti JFrame, JPanel, JLabel, dan sebagainya sesuai dengan desain Figma yang kita buat. Sesuaikan komponen-komponen tersebut agar mencocokkan desain yang telah  di  buat di figma, termasuk latar belakang, tombol, panel, dan elemen lainnya.
 lalu memulai mengimplementasikan logika aplikasi, termasuk fitur untuk mengunggah gambar wallpaper ke aplikasi. dengan menggunakan komponen seperti JFileChooser untuk memungkinkan pengguna memilih gambar dari ponsel mereka.
 Setelah itu mengonfigurasi koneksi ke database MySQL dalam aplikasi dengan menggunakan JDBC. Pastikan kita memiliki database MySQL yang telah dibuat sebelumnya untuk menyimpan data tentang wallpaper.
 Saat gambar wallpaper diunggah, Lakukan pengujian menyeluruh untuk memastikan bahwa aplikasi berfungsi dengan baik. Jangan lupa untuk menguji kemampuan untuk mengunggah, menampilkan, dan mengatur wallpaper sesuai dengan kebutuhan.

# Design: User Experience (UX) Design

<img width="367" alt="image" src="https://github.com/Naisilazia04/charmingweb/assets/144526940/04161e18-96fe-45e9-bca9-1fe2c5cea004">

• pada tahap ini kita merancang arsitektur berikut teknologi yang terdapat pada setiap komponen pembentuk aplikasi.Pada tahap ini kita mengeksplorasi alur interaksi pengguna yang paling praktis dan efektif untuk setiap fitur.

• Ada banyak tools yang bisa digunakan mulai dari yang open source seperti Inkscape, Penpot, lalu yang gratis hingga berbayar seperti Figma.

• Desain yang dibuat di atas adalah low fidelity design dimana kualitas desainnya paling sederhana tapi cepat untuk dibuat.











   
