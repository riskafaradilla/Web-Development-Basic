## Rangkuman Minggu Ke-2
## Day -6
### Javascript : "Scope & Function" 
### A. Scope
### 1. Pengertian Scope
Scope dalam Javascript adalah konsep yang digunakan untuk membatasi pengaksesan suatu variabel. Ada dua tipe scope yaitu :
- Global scope
Global scope berarti variabel yang kita buat dapat diakses dimanapun dalam suatu file.

  <img width="215" alt="global-scope" src="https://user-images.githubusercontent.com/114325558/193438801-dac21fe7-e334-4781-8650-69c429ad20f8.png">

- Local Scope
Agar menjadi Global Scope, suatu variabel harus dideklarasikan diluar Blocks.

  <img width="440" alt="local-scope" src="https://user-images.githubusercontent.com/114325558/193438796-2f8e8ef6-c337-4be5-83f8-f110f97137cb.png">

### B. Function
### 1. Pengertian Function
Function adalah sebuah blok kode dalam sebuah grup untuk menyelesaikan 1 task/1 fitur.
contoh function :
- Membuat function :

  <img width="425" alt="buat-function" src="https://user-images.githubusercontent.com/114325558/193439105-bd15c270-7334-41e6-bd24-a40b3c5b915f.png">
  
- Memanggil function :

  <img width="427" alt="panggil-function" src="https://user-images.githubusercontent.com/114325558/193439108-31a613c0-01ed-466b-813d-431963c1f594.png">

### 2. Parameter Dan Argumen
### a. Parameter

![function-parameter](https://user-images.githubusercontent.com/114325558/193439461-94cbc520-f7e8-4f97-aa4b-7e4f01ec35a9.png)

- Dengan parameter, function dapat menerima sebuah inputan data dan menggunakannya untuk melakukan task/tugas.
- Saat membuat function/fitur, kita harus tahu data-data yang dibutuhkan. Misalnya saat membuat function penambahan 2 buah nilai. Data yang dibutuhkan adalah 2 buah nilai tersebut.

### b. Argumen

![function-argumen](https://user-images.githubusercontent.com/114325558/193439467-4ca5c3ea-a603-4602-9b78-377933029804.png)

- Argumen adalah nilai yang digunakan saat memanggil function.
- Jumlah argumen harus sama dengan jumlah parameternya
- Jadi jika di function penambahan ada 2 parameter nilai saat membuat function. Saat memanggil function kita gunakan 2 buah nilai argumen.

### 3. Membuat Function
### a. Function helper
Kita bisa menggunakan function yang sudah dibuat pada function lain. Contoh :

<img width="370" alt="function-helper" src="https://user-images.githubusercontent.com/114325558/193439692-0b38d78f-5285-4c98-b673-faeb340da5cf.png">

### b. Arrow Function
Arrow function adalah cara lain menuliskan function. Ini adalah fitur terbaru yang ada pada ES6 (Javascript Version).

<img width="359" alt="arrow function" src="https://user-images.githubusercontent.com/114325558/193439702-4110a95c-fae1-49d6-89d3-7c4c07ef7ef5.png">

## Day -7
### Javascript "Data Type Built in Prototype & Method" 
### 1. Pengertian Data Type
Tipe data adalah jenis data yang dapat disimpan, dimanipulasi, dan digunakan untuk memberi tahu komputer bagaimana menfasirkan nilai atau datanya.
Tipe data menentukan jenis data yang dimiliki variabel dan tipe operasi, seperti operasi matematika, logika dan sebagainya.

### Macam-Macam Data Type
- ### primitive 
Data primitif hanya dapat menyimpan satu nilai pada satu waktu dan tidak dapat diubah menggunakan cara yang sama seperti tipe data non-primitif. Tipe data Primitif akan dianggap sama jika nilainya sama.
  - ### String
    String pada Javascript adalah tipe data yang berhubungan dengan karakter. 
    
    <img width="334" alt="string" src="https://user-images.githubusercontent.com/114325558/193448485-5771067d-b4ba-4707-8785-de7efe96ce9b.png">
    
  - ### Number
    Number adalah tipe data yang mewakili seluruh tipe data angka, seperti integer (bilangan bulat) dan floating point atau desimal. Contoh:
    
    <img width="241" alt="number" src="https://user-images.githubusercontent.com/114325558/193448500-c487d42c-18ca-43f0-8b95-902ef3e661da.png">
    
  - ### Boolean
    Boolean adalah tipe data yang hanya memiliki dua nilai, true dan false.
    
    <img width="206" alt="boolean" src="https://user-images.githubusercontent.com/114325558/193448505-e537ee78-f570-4a7a-9f59-b578c4ff48c8.png">
    
  - ### Undefined
    Undefined adalah nilai yang diberikan ketika variabel dideklarasikan tanpa inisialisasi atau tidak diberi nilai.
    
    <img width="260" alt="undefined" src="https://user-images.githubusercontent.com/114325558/193448511-25b90337-7651-4c42-8b15-da314e2e05a8.png">
    
  - ### Null
    Null dapat digunakan untuk mewakili ketidakhadiran yang disengaja dari nilai objek.
    
    <img width="257" alt="null" src="https://user-images.githubusercontent.com/114325558/193448721-bb5b0223-185f-4f04-8ac4-6eb6a6ffd082.png">
    
- ### Non Primitive
Tipe data non-primitif dapat menyimpan lebih dari satu nilai pada satu waktu dan dapat diubah. Tipe data non-primitif akan dianggap berbeda meskipun nilainya sama dan dalam urutan yang sama.
  - ### Object
    object adalah tipe data yang kompleks yang memungkinkan kita menyimpan kumpulan nilai dengan tipe data yang berbeda. Objek berisi properti yang didefinisikan       sebagai pasangan kunci dan nilai (key dan value).
    - membuat objek
    
      <img width="191" alt="objek-1" src="https://user-images.githubusercontent.com/114325558/193449132-b1d1032c-e5e5-4225-9353-5c2bdfa47b2a.png">

    - mengakses value tertentu pada objek
    
      <img width="241" alt="objek1" src="https://user-images.githubusercontent.com/114325558/193449398-536bd82d-5c20-442d-a320-977d0f3d1bf2.png">
      
    - mengubah nilai key pada objek

      <img width="251" alt="objek2" src="https://user-images.githubusercontent.com/114325558/193449143-34ef1dba-cf26-495b-979d-e03b1e35c89f.png">
      
    - mengubah key dan value baru
      
      <img width="523" alt="objek3" src="https://user-images.githubusercontent.com/114325558/193449149-6bff156a-73e0-42fb-96c8-6355653c6511.png">
      
  - ### Array
    Array adalah jenis objek yang dapat digunakan untuk menyimpan beberapa nilai, tanpa properti seperti objek.
    Array memiliki indeks yang dimulai dari nol dengan kata lain elemen atau nilai pertama di dalam array memiliki indeks 0, elemen berikutnya memiliki indeks 1 dan     seterusnya. kita bisa menggunakan indeks untuk memanipulasi nilainya. Nilai pada array literal harus diapit dengan kurung siku [], jika memiliki lebih dari satu     nilai dipisahkan dengan koma.
    - membuat array
      
      <img width="227" alt="array1" src="https://user-images.githubusercontent.com/114325558/193449534-adc8310e-0405-47d9-9697-cbbed0e01942.png">
      
    - Mengakses elemen array
      
      <img width="238" alt="array2" src="https://user-images.githubusercontent.com/114325558/193449540-87b579bc-337d-4f94-b5bb-75556d867281.png">
      
    - Mengubah elemen array
      
      <img width="269" alt="array3" src="https://user-images.githubusercontent.com/114325558/193449545-b774088e-c0a0-4246-adb4-64148a5bfaa5.png">

### 2. Pengertian Method
Method adalah serangkaian instruksi yang berkaitan dengan sebuah object. Pada materi ini banyak membahas method pada aritmatika.
- ### Math
  - Math.abs(), fungsinya yaitu mengembalikan nilai absolut dari sebuah angka.
    
    <img width="225" alt="abs" src="https://user-images.githubusercontent.com/114325558/193450444-e5ee4488-84ba-4d9f-97d4-37d79c7f80c8.png">
    
  - Math.ceil(), fungsinya yaitu digunakan untuk pembulatan ke atas.
    
    <img width="227" alt="ceil" src="https://user-images.githubusercontent.com/114325558/193450438-167a9613-3db6-49f1-928e-35896a990b8c.png">
    
  - Math.floor(), fungsinya untuk pembulatan ke bawah.
    
    <img width="226" alt="floor" src="https://user-images.githubusercontent.com/114325558/193450434-ce4b7f13-34a6-4e07-9082-b98a57e7b396.png">
    
  - Math.round(), untuk pembulatan kebawah jika kurang dari 0,5 dan pembulatan ke atas jika lebih dari 0,5 (termasuk 0,5).
    
    <img width="164" alt="round" src="https://user-images.githubusercontent.com/114325558/193450975-70b5dcf5-47da-4ce8-87b4-e420e504d068.png"> 
    
  - Math.max(), digunakan untuk mencari nilai paling besar dari angka-angka yang diinput ke dalam argumen.
    
    <img width="305" alt="max" src="https://user-images.githubusercontent.com/114325558/193450617-4d4b3a90-90cd-41db-80b8-5297b39abdb8.png">
    
  - Math.min(), digunakan untuk mencari nilai paling kecil dari angka-angka yang diinput ke dalam argumennya.
    
    <img width="293" alt="min" src="https://user-images.githubusercontent.com/114325558/193450612-350bc254-f099-4261-8fc1-57336263455c.png">
    
  - Math.pow(), digunakan untuk pemangkatan suatu angka.
  
    <img width="265" alt="pow" src="https://user-images.githubusercontent.com/114325558/193450822-d92cf94e-3e04-4c40-8693-8c4e69868f03.png">
    
  - Math.sqrt(), digunakan untuk melakukan akar kuadrat.
    
    <img width="185" alt="sqrt" src="https://user-images.githubusercontent.com/114325558/193450809-dbc299dd-3e3b-4dd6-9d67-a7a750963b26.png">

## Day -8
### DOM "Memanipulasi Tampilan Web Menggunakan Bahasa Pemrograman"
### 1. Pengertian DOM
DOM adalah singkatan dari Document Object Model. Jadi, ketika halaman website kita diload, browser kita akan membuat Document Object Model dari halaman website kita.Dengan adanya DOM ini, JavaScript diberi akses untuk membuat HTML menjadi dinamis, seperti:
- Mengubah element HTML pada halaman website.
- Mengubah attribute HTML pada halaman website.
- Mengubah CSS style pada halaman website.
- Menambah dan/atau menghapus element maupun attribute HTML.
- Menambah HTML event (contoh: efek klik pada mouse, hover pada mouse, dan lain-lain) pada halaman website.
- Berinteraksi dengan semua HTML event di website.
- Penting untuk diingat, ???DOM bukan bagian dari JavaScript, melainkan browser (Web API)???

### 2. Mempraktikan DOM
- Mencari/mengakses element HTML
  
  <img width="458" alt="dom1" src="https://user-images.githubusercontent.com/114325558/193452283-5084494d-b7d6-4575-a772-311b60b2f1f3.png">
  
- Mengubah konten element
  - Element.textContent, dapat kita gunakan untuk mengubah teks di dalam sebuah element.
    
    <img width="260" alt="dom2" src="https://user-images.githubusercontent.com/114325558/193452300-ba0761d7-bf3e-42d0-ad54-d072a31dd752.png">
    
  - Element.innerHTML, dapat kita gunakan untuk mengubah konten HTML di dalam sebuah element.
    
    <img width="281" alt="dom3" src="https://user-images.githubusercontent.com/114325558/193452308-be1185bd-6c0d-4781-8965-9b0c0aee245b.png">
    
- Membuat element HTML

  <img width="256" alt="dom4" src="https://user-images.githubusercontent.com/114325558/193452313-e58c3607-3881-48e0-bef1-cc4545cedd43.png">
  
- Menangkap interaksi user menggunakan Element.addEventListener(???event???)
  - EventListener - Click
    
    <img width="338" alt="dom5" src="https://user-images.githubusercontent.com/114325558/193452316-580a236a-00d2-45a6-8a10-c84ca3111659.png">
    
  - EventListener - Blur

    <img width="413" alt="dom6" src="https://user-images.githubusercontent.com/114325558/193452327-70186f86-043b-499f-a810-9271afd53346.png">
    
  - EventListener - Form Submission

    <img width="410" alt="dom7" src="https://user-images.githubusercontent.com/114325558/193452333-9d67dc29-6ac3-41bf-91bd-f287f624ba0d.png">
 
 ### 3. Latihan Membuat DOM (DOM Intro)
 
 - ### File HTML :

    <img width="575" alt="html1" src="https://user-images.githubusercontent.com/114325558/193454570-d86aee39-107c-4911-9512-ddeabf071158.png">
    <img width="579" alt="html2" src="https://user-images.githubusercontent.com/114325558/193454562-3389815f-8ee6-45c9-88b8-3e0520702a75.png">
    
 - ### File Javascript
 
    <img width="579" alt="js1" src="https://user-images.githubusercontent.com/114325558/193454612-8a06d3d8-5a7b-47cd-8b5d-74f36a8e9d0b.png">
    <img width="579" alt="js2" src="https://user-images.githubusercontent.com/114325558/193454626-06ff3714-ca86-4afa-a155-f78945e9cae1.png">

## Day -9
### DOM (Document Object Model)
Pada Pertemuan ini masih membahas tentang DOM dengan menggunakan materi yang sama pada hari sebelumnya (day-8).

### Latihan Membuat DOM (DOM Manipulation)

- File HTML

  <img width="578" alt="html-dom_manipulation1" src="https://user-images.githubusercontent.com/114325558/193454978-57ca96ae-8d0f-4634-b098-3f51a6ca53ba.png">
  <img width="577" alt="html-dom_manipulation2" src="https://user-images.githubusercontent.com/114325558/193454988-91bd61fe-5014-4f34-93d9-77cfa6a55e46.png">

- File Javascript
  
  <img width="579" alt="javascript-dom_manipulation1" src="https://user-images.githubusercontent.com/114325558/193455038-f3423b04-0c9a-4e22-9983-421256ea9ee9.png">
  <img width="578" alt="javascript-dom_manipulation2" src="https://user-images.githubusercontent.com/114325558/193455082-54307711-10ab-4ded-82b5-2af7cb38f63a.png">
  
## Day -10
### DOM (Document Object Model)
Pada Pertemuan ini masih membahas tentang DOM dengan menggunakan materi yang sama pada hari sebelumnya (day -8).

### Latihan Membuat DOM (DOM Event)
### Latihan 1 (incrrement dan decrement)
- File HTML

  <img width="580" alt="html-pert5-1" src="https://user-images.githubusercontent.com/114325558/193455444-44225c07-28e7-4f18-ab2e-9ac37d626b97.png">
  
- File Javascript

  <img width="578" alt="javascript-pert5-1" src="https://user-images.githubusercontent.com/114325558/193455449-4869960e-6cb6-4021-9dbb-3433b9603828.png">
  
### Latihan 2 (Klik)
- File HTML
  
  <img width="578" alt="html-pert5-2" src="https://user-images.githubusercontent.com/114325558/193455648-1ddae6da-4ae1-4a5b-bbf2-818e3e084665.png">
  
- File Javascript
  
  <img width="580" alt="javascript-pert5-2" src="https://user-images.githubusercontent.com/114325558/193455655-0e5a0d71-909a-499b-a708-88a8ec404c68.png">
  
### Latihan 3 (Login)
- file HTML

  <img width="578" alt="html-pert5-3-1" src="https://user-images.githubusercontent.com/114325558/193455839-49e698d3-e38a-455e-a0c5-57cd2b3dcbdd.png">
  <img width="577" alt="html-pert5-3-2" src="https://user-images.githubusercontent.com/114325558/193455850-410a122b-ae5f-489c-99fa-4f72cf09ec31.png">
  
- File Javascript
  
  <img width="578" alt="javascript-pert5-3-1" src="https://user-images.githubusercontent.com/114325558/193456099-43782f3d-3806-47a2-b103-e8f69e50d2d8.png">
  <img width="580" alt="javascript-pert5-3-2" src="https://user-images.githubusercontent.com/114325558/193456105-8e602ddc-54bf-46c7-bad6-ee01426f21f2.png">
