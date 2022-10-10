## Rangkuman Materi Minggu Ke 3
## Day 11
### Javascript : Array & Multidimensional Array
### A. Array
### 1. Apa itu Array ?
Array adalah tipe data list order yang dapat menyimpan tipe data apapun di dalamnya. Array dapat menyimpan tipe data String, Number, Boolean, dan lainnya.
Contoh array :

### 2. Membuat Array
### 3. Array Properties
Properties adalah fitur yang sudah disediakan oleh Javascript untuk memudahkan developer.
Array memiliki 5 properti yang sering digunakan yaitu constructor, length, index, input, dan prototype.

### 4. Array Method
Array memiliki method atau biasa disebut built-in methods. Artinya Javascript sudah memudahkan kita dengan menyediakan function/method umum yang bisa kita gunakan.
contoh:
- .push() adalah method untuk menambahkan item  array pada urutan yang paling akhir.
- .pop() adalah method yang menghapus item array index terakhir.
- .shift() adalah method untuk menghapus item Array pada index pertama
- .unshift() adalah method untuk menambahkan item Array pada index pertama
- .sort() adalah method untuk mengurutkan secara Ascending atau Descending Alphanumeric

### 5. Looping pada Array
Array memiliki built in methods untuk melakukan looping yaitu .map() dan .forEach()
-.forEach() adalah method untuk melakukan looping pada setiap elemen array.
-.map() melakukan perulangan/looping dengan membuat array baru.

### B. Multidimensional Array
### Pengertian Multidimensional Array
Multidimensional Array bisa dianalogikan dengan array of array. Ada array didalam array.
contoh : 
- Multidimensional array

- Operation using map in multidimensional array

- looping for multidimensional array

## Day 12
### JavaScript: Object
### 1. Apa itu Object ?
pada programming, object adalah sebuah tipe data pada variabel yang menyimpan properti dan fungsi (method).Properti adalah data lengkap dari sebuah object.
Method adalah action dari sebuah object. Apa saja yang dapat dilakukan dari suatu object.
### 2. Membuat dan Mengakses Object
Kita juga bisa menggunakan bracket notation saat memanggil properti dari sebuah object.
### 3. Mengupdate Objek
Kita dapat melakukan update pada variabel dengan tipe data Object.
- Object dapat mengupdate value dari key yang sudah tersedia
- Object dapat menambahkan key dan value baru

### 4. Menghapus Object Property
Kita dapat menghapus properti dari object menggunakan delete operator.

### 5. Method
Method adalah value yang dimasukkan pada property berupa function.

### 6. Looping Object
### 7. Array of Object
Kita dapat menggunakan array of object untuk data yang lebih dari satu.

## Day 13
### Javascript: Recursive
### 1. Pengertian Recursive
Recursive adalah function yang memanggil dirinya sendiri sampai kondisi tertentu. Recursive kebanyakan digunakan untuk case matematika, fisika, kimia, dan yang berhubungan dengan calculation.

### 2. Ciri-Ciri Recursive
- Fungsi rekursif selalu memiliki kondisi yang menyatakan kapan fungsi tersebut berhenti. Kondisi ini harus dapat dibuktikan akan tercapai, karena jika tidak tercapai maka kita tidak dapat membuktikan bahwa fungsi akan berhenti, yang berarti algoritma kita tidak benar.
- Fungsi rekursif selalu memanggil dirinya sendiri sambil mengurangi atau memecahkan data masukan setiap panggilannya. Hal ini penting diingat, karena tujuan utama dari rekursif ialah memecahkan masalah dengan mengurangi masalah tersebut menjadi masalah-masalah kecil.

### 3. Contoh kasus rekursif

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

  
  








