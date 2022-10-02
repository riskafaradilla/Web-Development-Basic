## Rangkuman Materi Minggu Ke-1
### Day -1
### Unix Command Line dan Git & Github
### A. Unix Command Line
- command Line Interface yitu jenis shell yang berbasis teks.
- Shell yaitu program yang digunakan untuk berkomunikasi atau memerintah sistem.
- Syntax Command Line :
  - Pwd : command untuk melihat current working directory.
  - ls : command untuk melihat isi file yang ada di sebuah direktori.
  - cd : command untuk command untuk berpindah direktori.
  - touch : command untuk membuat sebuah file.
  - mkdir : command untuk membuat sebuah direktori.
  - cat : command untuk melihat isi sebuah file.
  - head : command untuk beberapa line awal dari sebuah file text.
  - tail : command untuk beberapa line akhir dari sebuah file text.
  - cp : command untuk mengcopy files atau directory.
  - mv : command untuk memindahkan files atau directory. Bisa digunakan untuk rename.
  - rm : command untuk menghapus file atau directory.
  
### B. Git & Github
### 1. Pengertian Git 
 - GIT adalah Tools untuk programmer.
 - GIT adalah aplikasi yang dapat melacak setiap peruahan yang terjadi pada suatu folder atau file.
 - GIt biasanya digunakan oleh para programmer sebagai tempat penyimpanan file pemrograman mereka karena lebih efektif. 
 - GIT sebagai version Tugasnya adalah mencatat setiap perubahan pada File (termasuk code yang kita buat) pada suatu proyek baik dikerjakan secara individu maupun tim.
  
### 2. Pengertian Gihub
Github adalah sebuah website dan layanan berbasis cloud bagi para developer untuk menyimpan dan mengelola kode, serta mendokumentasikan dan mengontrol perubahannya.
  
### 3. Perintah Dasar Git
 - Git init : digunakan untuk membuat repository di file lokal.
 - Git status : digunakan untuk mengetahui sebuah status dari sebuah repository lokal.
 - Git add : adalah perintah yang digunakan untuk menambahkan file baru di repository yang dipilih.
 - Git commit : digunakan untuk menyimpan perubahan yang sudah dilakukan, namun tidak ada perubahan yang terjadi pada remote repository.
 - Git push : digunakan dalam mengirimkan perubahan file yang dilakukan setelah di commit ke remote repository.
  
  
 ### Day -2
 ### HTML
 ### 1. Pengertian HTML
  - HTML adalah singkatan dari Hypertext Markup Language.
  - HTML adalah bahasa komputer yang digunakan untuk membuat kerangka atau struktur untu Web pages (halaman website) di internet.
  - HTML bukanlah sebuah bahasa pemrograman, artinya HTML tidak bisa dinamis mengolah data.
  
### 2. Kerangka HTML
  
### 3. Tag HTML
Tag adalah sebuah penanda awalan dan akhiran dari sebuah elemen di HTML. Tag dibuat dengan kurung siku (<...>), lalu didalamnya berisi nama tag.
  
### 4. HTML Attribute
Di dalam Opening Tag dapat berisi attribute, yang berfungsi untuk membedakan informasi tambahan kepada sebuah element.
  
### 5. HTML Element
Element merupakan sebuah komponen dalam halaman web, bisa berupa paragraf, judul, atau gambar.
  
Pada umumnya, HTML Element terdiri dari :
 - Opening Tag (tag pembuka),
 - Closing Tag (tag penutup),
 - Attribute.
 - Content (konten) yang ingin ditampilkan di browser.
  
### Day -3
### CSS
### 1. Pengertian CSS
 - CSS digunakan untuk mendesain halaman website.
 - Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya.
 
### 2. Menyisipkan CSS di HTML 
Ada tiga cara untuk menyisipkan CSS di HTML yaitu :
- Inline CSS, yaitu menggunakan attribute untuk menyisipkan kode CSS langsung di dalam HTML element.
- Internal CSS, yaitu menggunakan element style untuk menyisipkan kode CSS. Element style tersebut diletakkan didalam element head.
- External CSS, yaitu sebuah file tepisah yang disambungkan dengan file HTML dengan menggunakan element link.
 
### 3. Syntax CSS
CSS Syntax adalah syntax yang digunakan untuk menunjuk atau memilih HTML element mana yang ingin diberi style (dihias). CSS syntax terdiri dari selector, property, dan value.
 
### Day -4
### Algoritma & Intro to Javascript
### A. Algoritma
### 1. Pengertian Algoritma
Algoritma adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah. Kualitas wajib dari algoritma :
- Input dan output harus didefinisikan terlebih dahulu dengan tepat.
- Setiap step harus benar-benar clear dan tidak ambigu.
- Algoritma seharusnya tidak mengandung suatu kode pada bahasa pemrograman tertentu.
- Algoritma harus dibuat agar dapat digunakan dalam bahasa pemrograman apapun.

### 2. Kenapa harus belajar Algoritma?
- Programming itu adalah algoritma dan struktur data.
- Data struktur digunakan untuk mengelola/manajemen sebuah data dan algoritma yang akan menyelesaikan suatu permasalahan menggunakan data tersebut.

### 3. Jenis-Jenis Algoritma
### a. Algoritma Deskriptif
### b. Flowchart
### c. Pseudocode
Pseudocode adalah menuliskan algoritma dengan umumnya bahasa inggris sebelum kita implementasikan ke bahasa pemrograman tertentu. 

### Intro to Javascript
### 1. Pengertian Javascript
Javascript adalah bahasa pemrograman yang sangat powerful yang digunakan untuk logic pada sebuah website. Javascript juga dapat membuat website menjadi interaktif dan dinamis.

### 2. Type Data 
Tipe data adalah klasifikasi yang kita berikan untuk berbagai macam data yang digunakan dalam programming. Ada 6 tipe data fundamental pada Javascript yaitu :
- number
- string
- boolean
- null
- undefined
- object

### 3. Variabel
Disemua bahasa pemrograman, veriable adalah container/tempat untuk menyimpan sebuah nilai.
- 3 hal yang dapat dilakukan pada variabel :
  - membuat variabel dengan nama yang jelas dan menggambarkan tentang data tersebut.
  - menyimpan dan mengupdate informasi/data yang disimpan.
  - mendapatkan/menampilkan data yang tersimpan.
- Ada 3 cara mendefinisikan sebuah variabel 
  - var
  - let
  - const
- Aturan penamaan variabel :
  - Harus mendeskripsikan tentang data yang disimpan.
  - tidak bisa menggunakan number pada awal nama variabel.
  - Gunakan camelcase untuk penamaan yang lebih dari 1 kata. contoh:myName, myAge.
  
### Day -5
### JAVASCRIPT DASAR - "CONDITIONAL & LOOPING"
### 1. Conditional
- Apa itu Conditional
  - Conditional merupakan statement percabangan yang menggambarkan suatu kondisi.
  - Conditional statement akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut.
- Jenis-Jenis Conditional
  - IF Statement
  - IF-ELSE
  - IF-ELSE-IF
  - Switch Case Conditional
  
### 2. Looping
  - Apa itu Looping? Looping adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi stop/berhenti tercapai.
  - Jenis Looping
    - For Loop
      - Inisialisasi: Sebagai inisialisasi awal dari mana mulainya sebuah pengulangan. Kita memberikan nilai awal/default pada parameter ini.
      - Condition: For loop akan terus berjalan selama kondisi ini terpenuhi. Selama kondisi bernilai TRUE.
      - Post-expression (Increment/Decrement): Iterasi statement yang digunakan untuk mengupdate variabel yang menjadi kontrol pada pengulangan.
    - While Loop
    - Do While Loop
      

