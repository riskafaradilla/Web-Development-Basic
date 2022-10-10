## Rangkuman Materi Minggu Ke 3
## Day 11
### Javascript : Array & Multidimensional Array
### A. Array
### 1. Apa itu Array ?
Array adalah tipe data list order yang dapat menyimpan tipe data apapun di dalamnya. Array dapat menyimpan tipe data String, Number, Boolean, dan lainnya.
Contoh array :

### 2. Membuat Array

![array-contoh](https://user-images.githubusercontent.com/114325558/194846449-373d3776-9fc1-4118-91b4-1290d4636c51.JPG)

### 3. Array Properties
Properties adalah fitur yang sudah disediakan oleh Javascript untuk memudahkan developer.
Array memiliki 5 properti yang sering digunakan yaitu constructor, length, index, input, dan prototype.

### 4. Array Method
Array memiliki method atau biasa disebut built-in methods. Artinya Javascript sudah memudahkan kita dengan menyediakan function/method umum yang bisa kita gunakan.
contoh:
- .push() adalah method untuk menambahkan item  array pada urutan yang paling akhir.

![push](https://user-images.githubusercontent.com/114325558/194847701-e2592df2-6157-41b4-815c-a972d44837e3.JPG)

- .pop() adalah method yang menghapus item array index terakhir.

![pop](https://user-images.githubusercontent.com/114325558/194847792-37e2b6de-9f1b-4aab-8a8f-15714ce7513b.JPG)

- .shift() adalah method untuk menghapus item Array pada index pertama

![shift](https://user-images.githubusercontent.com/114325558/194847063-9db6ee12-60c6-4240-8caa-fadb985f7868.JPG)

- .unshift() adalah method untuk menambahkan item Array pada index pertama

![unshift](https://user-images.githubusercontent.com/114325558/194847291-41151333-7f47-41df-bcde-8fd02e65472f.JPG)

- .sort() adalah method untuk mengurutkan secara Ascending atau Descending Alphanumeric

![sort](https://user-images.githubusercontent.com/114325558/194847439-7baf5896-1554-4a61-89d4-3f8afdcdd084.JPG)



### 5. Looping pada Array
Array memiliki built in methods untuk melakukan looping yaitu .map() dan .forEach()
- .forEach() adalah method untuk melakukan looping pada setiap elemen array.

![foreach](https://user-images.githubusercontent.com/114325558/194847938-3a089ce0-ac79-438b-ace6-d0d92808a3a5.JPG)

- .map() melakukan perulangan/looping dengan membuat array baru.

![map](https://user-images.githubusercontent.com/114325558/194847983-1fb512b3-7e86-466a-b53d-b901857b7891.JPG)


### B. Multidimensional Array
### Pengertian Multidimensional Array
Multidimensional Array bisa dianalogikan dengan array of array. Ada array didalam array.
contoh : 
- Multidimensional array

![array-multi](https://user-images.githubusercontent.com/114325558/194848089-dfb6c3dc-bb8f-448b-ba43-aa3847672020.JPG)

- Operation using map in multidimensional array

![map_in_multi-array](https://user-images.githubusercontent.com/114325558/194848195-df64707e-8067-42fb-b574-6c14d2fa559a.JPG)

- looping for multidimensional array

![looping-multi-array](https://user-images.githubusercontent.com/114325558/194848243-f9b52e7d-d266-475f-aec3-b585f650e782.JPG)

## Day 12
### JavaScript: Object
### 1. Apa itu Object ?
pada programming, object adalah sebuah tipe data pada variabel yang menyimpan properti dan fungsi (method).Properti adalah data lengkap dari sebuah object.
Method adalah action dari sebuah object. Apa saja yang dapat dilakukan dari suatu object.
### 2. Membuat dan Mengakses Object

![akses-object](https://user-images.githubusercontent.com/114325558/194849003-27a22382-a75e-49b0-984e-3724f8f2ec48.JPG)

Kita juga bisa menggunakan bracket notation saat memanggil properti dari sebuah object.

![bracket-notation](https://user-images.githubusercontent.com/114325558/194848724-022a0fb6-5cfa-4976-9711-745db73c669d.JPG)

### 3. Mengupdate Objek

![update-objek](https://user-images.githubusercontent.com/114325558/194848784-a5b91dab-239b-48b4-9269-cdf56bcd8ee1.JPG)

Kita dapat melakukan update pada variabel dengan tipe data Object.
- Object dapat mengupdate value dari key yang sudah tersedia
- Object dapat menambahkan key dan value baru

### 4. Menghapus Object Property
Kita dapat menghapus properti dari object menggunakan delete operator.



### 5. Method
Method adalah value yang dimasukkan pada property berupa function.

![method-object](https://user-images.githubusercontent.com/114325558/194849221-74eaa190-4672-4642-86cb-8f66ed33790d.JPG)

### 6. Looping Object

![looping-object](https://user-images.githubusercontent.com/114325558/194849373-c3bf5cea-8c7c-41b1-9116-d3871d7a4b02.JPG)


### 7. Array of Object
Kita dapat menggunakan array of object untuk data yang lebih dari satu.

![arrayofobject](https://user-images.githubusercontent.com/114325558/194849309-1054d327-b7f9-4364-a9fb-2d6834f3c9e4.JPG)

## Day 13
### Javascript: Recursive
### 1. Pengertian Recursive
Recursive adalah function yang memanggil dirinya sendiri sampai kondisi tertentu. Recursive kebanyakan digunakan untuk case matematika, fisika, kimia, dan yang berhubungan dengan calculation.

### 2. Ciri-Ciri Recursive
- Fungsi rekursif selalu memiliki kondisi yang menyatakan kapan fungsi tersebut berhenti. Kondisi ini harus dapat dibuktikan akan tercapai, karena jika tidak tercapai maka kita tidak dapat membuktikan bahwa fungsi akan berhenti, yang berarti algoritma kita tidak benar.
- Fungsi rekursif selalu memanggil dirinya sendiri sambil mengurangi atau memecahkan data masukan setiap panggilannya. Hal ini penting diingat, karena tujuan utama dari rekursif ialah memecahkan masalah dengan mengurangi masalah tersebut menjadi masalah-masalah kecil.

### 3. Contoh kasus rekursif

![contoh-recursive](https://user-images.githubusercontent.com/114325558/194849743-2883ff4d-ec56-4cc3-b1cf-aa0b6a42bda2.JPG)

## Day 14
### Javascript Asynchronous : "Introducing & Promise"
### 1. Apa itu Asyncronous ?
Asynchronous hasil eksekusi atau output tidak selalu berdasarkan urutan kode, tetapi berdasarkan waktu proses. Eksekusi dengan asynchronous tidak akan membloking atau menunggu suatu perintah sampai selesai. Daripada menunggu, asynchronous akan mengeksekusi perintah selanjutnya.

### 2. Asyncronous Promise
Promise bisa dikatakan sebagai object yang menyimpan hasil dari sebuah operasi asynchronous baik itu hasil yang diinginkan (resolved value) atau alasan kenapa operasi itu gagal (failure reason).

Sebuah Promise berada di salah satu diantara 3 kondisi(state):
- pending, operasi sedang berlangsung
- fulfilled, operasi selesai dan berhasil
- rejected, operasi selesai namun gagal


## Day 15
### Web Storage
### 1. Pengertian Web Storage
Web storage adalah salah satu Web API yang dapat menyimpan data secara lokal pada sisi client. Berbeda dengan objek atau array, data yang disimpan pada objek atau array JavaScript bersifat sementara, dan akan hilang jika terjadi reload atau pergantian URL pada browser.

### 2. Tipe Web Storage
- Local Storage
  Local storage memiliki karakteristik sebagai berikut:
  - Menyimpan data tanpa tanggal kadaluarsa.
  - Data tidak akan dihapus ketika web browser ditutup dan akan tersedia seterusnya selama kita tidak menghapus data local storage pada web browser.
  - Dapat menyimpan data hingga 5MB.
  - Hanya dapat menyimpan data string.

Untuk menyimpan data pada local storage, kita menggunakan method setItem() yang membutuhkan 2 parameter. Parameter pertama adalah key yang ingin kita simpan dan parameter kedua adalah data (value) dari key yang akan disimpan.
Untuk mengambil data yang telah tersimpan pada local storage, kita dapat menggunakan method getItem() yang membutuhkan 1 parameter. Parameter tersebut adalah key dari data yang kita inginkan.
Untuk menghapus data yang telah tersimpan pada local storage, kita dapat menggunakan method removeItem() yang membutuhkan 1 parameter. Parameter tersebut adalah key dari data yang ingin kita hapus.

- Session Storage
Session storage mempunyai beberapa karakteristik, yaitu:
  - Data yang disimpan pada session storage akan terus tersimpan selama browser terbuka dan tidak hilang jika laman di-reload.
  - Membuka banyak tab/window dengan URL yang sama, akan menciptakan session storage yang berbeda di masing-masing tab/window.
  - Menutup tab/window akan mengakhiri session dan menghapus data yang tersimpan di session storage pada tab/window tersebut.
  - Data yang tersimpan dalam session storage harus berbentuk string.
  - Hanya dapat menyimpan data sebanyak 5MB.

Sama dengan local storage, sintaks untuk menyimpan data pada session storage adalah sebagai berikut:
Sama seperti local storage, cara mendapatkan data dari session storage juga menggunakan getItem(), seperti berikut ini:
Syntax untuk menghapus data dari session storage ada 2, yaitu:

### 3. Membuat Projek dengan Mempraktikkan Web Storage

  
  








