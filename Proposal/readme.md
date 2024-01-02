**Intro**

Artikel ini membahas mengenai pengembangan teknologi UbiCom berupa translator bahasa isyarat. Nantinya teknologi berbasis WebApp ini akan dapat menangkap pose tangan menggunakan kamera dan memberitahu kita melalui layar perangkat yang kita gunakan arti dari setiap pose tangan menjadi alfabet, sehingga dapan membantu kita agar dapat berbincang dengan seorang tunawicara.

**Latar Belakang**

Dalam masyarakat yang semakin maju dan terkoneksi secara global, inklusivitas dan aksesibilitas menjadi hal yang sangat penting untuk semua individu, tanpa terkecuali bagi mereka yang memiliki tantangan dalam hal pendengaran dan bicara. Tunawicara, sebagai bagian integral dari masyarakat, sering menghadapi kesulitan dalam berkomunikasi dengan orang-orang di sekitarnya, terutama dalam situasi di mana bahasa lisan tidak dapat digunakan.

Dalam konteks ini, perkembangan teknologi UbiCom (Ubiquitous Computing) menawarkan potensi besar untuk meningkatkan kualitas hidup tunawicara. Salah satu aplikasi menarik dari UbiCom adalah pengembangan Sign Translator, sebuah teknologi berbasis WebApp yang dirancang untuk menerjemahkan bahasa isyarat ke dalam bahasa lisan, khususnya Bahasa Indonesia. Teknologi ini bertujuan untuk membuka pintu komunikasi bagi tunawicara dengan cara yang lebih efektif, mengurangi hambatan-hambatan komunikasi yang mungkin mereka hadapi sehari-hari.

Sign Translator menggunakan kemampuan kamera sebagai alat utama dalam menangkap gerakan bahasa isyarat. Dengan mengintegrasikan teknologi pengenalan gerakan canggih, sistem ini dapat mengidentifikasi setiap gerakan bahasa isyarat yang ditampilkan oleh pengguna. Informasi ini kemudian diolah dan diterjemahkan secara instan melalui WebApp, memberikan arti dari setiap pose tangan ke dalam alfabet. Dengan cara ini, tunawicara dapat dengan mudah berkomunikasi dengan orang-orang di sekitarnya, membuka peluang untuk terlibat dalam berbagai aktivitas sosial dan profesional tanpa kendala komunikasi.

Pengembangan teknologi ini diharapkan dapat memberikan kontribusi signifikan dalam menciptakan masyarakat yang lebih inklusif dan mendukung penuh partisipasi tunawicara dalam berbagai aspek kehidupan sehari-hari. Melalui Sign Translator, kami bertujuan untuk mengatasi tantangan komunikasi yang dihadapi oleh tunawicara, membantu mereka merasa lebih terlibat, dihargai, dan dapat berkontribusi secara maksimal dalam berbagai lingkup kehidupan masyarakat. Dengan adanya teknologi ini, kami meyakini bahwa kita dapat melangkah lebih dekat menuju masyarakat yang lebih ramah bagi semua, tanpa memandang perbedaan kemampuan komunikasi.

**Branding**

Dalam mengembangkan merek dan citra produk UbiCom untuk sign translator (penerjemah isyarat), kami memilih:
- **Merk** : Silent App

**Target Pengguna**

Aplikasi ini ditujukan untuk:

- **Seluruh kalangan usia**: Produk ini dirancang agar dapat digunakan oleh seluruh kalangan usia, terutama mereka yang sering berinteraksi dengan seorang tunawicara.
- **Segala device**: Produk ini dirancang agar dapat digunakan disemua device seperti smartphone, laptop, tablet dan lain sebagainya.

**User Experience Theme**

Time line nantinya akan memberikan pengalaman bagi pengguna yang:
- **Mudah digunakan**: Pengguna harus dapat dengan mudah menggunakan Silent App.
- **Mudah dipahami**: pengguna harus dapat dengan mudah memahami cara penggunaan Silent App.

**User Story**

Berikut beberapa user story yang menggambarkan kebutuhan utama dari pengguna aplikasi Time Line:
|**Sebagai**|**Saya ingin bisa**|**Sehingga**|**Prioritas**|
|-----|-----|-----|-----|
|Sistem|Ingin bisa mendeteksi gerakan|Sehingga bisa menyesuaikan gerakan dengan bahasa isyarat|⭐⭐⭐⭐⭐|
|Sistem|Ingin bisa melabeli gerakan|Sehingga bisa memberikan label pada setiap gerakan bahasa isyarat|⭐⭐⭐⭐⭐|

**Metode dan Algoritma**

Untuk mencapai tujuan diatas kami akan menggunakan beberapa metode dan algoritma:

- **Metode**
  
  - Metode Agile : Pengembangan aplikasi Silent App menggunakan metode agile dikarenakan kompleksitas aplikasi dalam membangun model Machine Learning dan pembangunan WebApp. Selain itu, pengembangan Web App ini juga berfokus pada 1 fitur pada mulanya dan dapat dikembangkan kembali jika ada penambahan fitur lainnya.
  - Web Development : Pengembangan Silent App ini akan menggunakan html dan API flask karena aplikasi ini bertujuan agar mudah diakses di segala device.

- **Sensor**
  
  - Computer Vision : Hand Recognition, Random Forest Classifier.

- **Responder**
  
  - Kamera : Untuk mendeteksi pose tangan.
  - Tampilan Visual : Menggunakan pengolahan gambar untuk menampilkan tampilan visual pada layar.

Algoritma pada aplikasi ini menggunakan random forest classifier yang dimana nantinya digunakan untuk mendeteksi pose tangan, yang langsung di proses untuk kemudian menerjemahkannya kedalam bentuk alfabet yang mewakili bentuk pose tangan tersebut secara real-time.

**Protorype**: https://www.canva.com/design/DAF4vW7vBx0/jTCdK9GHtfHqnpxdeCyyuw/view?utm_content=DAF4vW7vBx0&utm_campaign=designshare&utm_medium=link&utm_source=editor

**Deskripsi Teknologi**

Pada tahap ini kami akan menjelaskan setiap teknologi hardware dan software yang digunakan dalam pembangunan sistem yang nantinya akan mendeteksi pose tangan dengan kamera secara real-time dan menampilkan alfabet yang diwakilkan oleh pose tangan tersebut.

Hardware Development:

- Mesin Komputasi: Laptop (ASUS Vivobook Max X441M) dan Smartphone (Vivo Y23). Penggunaan 2 perangkat ini dikarenakan keduanya sudah memiliki banyak sensor, yang salah satunya adalah kamera yang nantinya akan digunakan untuk mendeteksi pose tangan.

Software Development:

- HTML: merupakan bahasa markah standar untuk membuat struktur dan konten halaman web yang nantinya digunakan pada Silent App.
- CSS: merupakan bahasa pemrograman yang digunakan untuk mengatur struktur dan konten pada halaman web yang sudah dibuat menggunakan html.
- Javascript: merupakan bahasa pemrograman yang digunakan untuk membuat tampilan menjadi interaktif dan dinamis. Tetapi, pada Silent App, javascript digunakan untuk memvalidasi data yang masuk.
- Python: merupakan bahasa pemrograman yang serbaguna dan salah satu kegunaannya ialah machine learning dan pengembangan website yang sangat penting untuk membangun Silent App.

**Arsitekture Sistem**
**Flowchart**
