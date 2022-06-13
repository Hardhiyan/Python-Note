PYTHON NOTE
#Begin Here

Python adalah bahasa pemrograman yang ditujukan untuk general-purpose programming dan termasuk dalam kategori high-level programming language.

Sebagai general-purpose programming language, Python digunakan untuk berbagai macam permasalahan seperti: pengembangan aplikasi web ataupun mobile, data science, dll.
Python masuk ke dalam kategori high-level programming language dikarenakan bahasa pemrograman Python yang mudah untuk dibaca dan dituliskan oleh manusia.
Bahasa  pemrograman  Python  diciptakan  oleh  Guido  van Rossum dan pertama kali diperkenalkan pada tahun 1991 sebagai sebuah proyek open-source. 
Lisensi dari Python bersifat open-source dari Python, atau dengan kata lain setiap orang dapat mengembangkan program komputer dengan menggunakan bahasa pemrograman Python baik untuk tujuan komersil/non-komersil.

Bahasa pemrograman Python adalah bahasa yang dieksekusi oleh sebuah interpreter. Interpreter tersebut bertugas untuk memparsing sintaks python, 
dan kemudian mengkonversinya menjadi sebuah instruksi mesin satu persatu (maksudnya adalah mengeksekusi dari baris pertama ke baris selanjutnya 1 per 1)

Apa kaitan Python dan Data Science?
Python adalah bahasa yang ditujukan untuk general-purpose programming, jenis high-level programming language dan berlisensi open source”
Karena tiga karakteristik itulah, banyak pengembang membuat library python ditujukan untuk data science dan tentunya memudahkan pengguna dalam melakukan analisis dan membuat model prediktif dalam data science.
List library Python ini dapat kamu gunakan untuk data science

THE RULE OF PYTHON

1. Case Sensitive
Syntax Python bersifat case sensitive, Ia akan membedakan antara huruf kecil dan huruf besar walaupun sebuah kata itu terlihat sama.
Antara 'teksini' dan 'TeksIni' itu berbeda sma halnya 'judul' dengan 'Judul'.

2. Case Style
## Snake Case digunakan pada:
module_name, package_name, method_name, function_name, , global_var_name, 
instance_var_name, function_parameter_name, local_var_name.


## CamelCase digunakan Pada:
ClassName, ExceptionName

## ALL CAPS digunakan Pada: 
GLOBAL_CONSTANT_NAME

3. Indentasi Sebagai Pembentuk Struktur yang sangat penting
• Blok program adalah kumpulan dari beberapa statement yang digabungkan dalam satu blok.
• Penulisan blok program harus ditambahkan indentasi (tab atau spasi 2x/4x).
indentasi pada Python itu sangat krusial, sangat penting dan sangat-sangat harus dibiasakan memperhatikannya
mengingat hal ini dapat mempengaruhi berjalannya syntax atau bahkan menghasilkan ERROR dan sulit dideteksi bagi yang belum terbiasa.
• Jika 1 baris statement telah selesai maka proses 'Enter' atau ganti baris akan otomatis memberikan indentasi 
Examples:

for key in d2:
    if key in d1:
        d2[key] = d2[key] + d1[key]

c = {**d1, **d2}
print(c)

LAGI, indentasi dalan Python statusnya MUTLAK dan tidak bisa salah seperti case sensitive.

Error seperti ini biasanya akan terjadi jika:

Kita melakukan copy-paste kode program dari internet
Dan kita tidak menggunakan teks editor atau IDE yang kekinian

4. Tipe Data String pada Python memiliki aturan tertentu juga
Tipe Data String (Teks), harus diapit dengan tanda petik. Bisa menggunakan petik tunggal
('...'), ganda ("..."), dan tiga ('''...''' atau """...""")

5. Peng 'Indeks' an dalam Python dimulai dari 0
Misalnya ada 5 tipe data

P Y T H O N
0 1 2 3 4 5#Urutan Indeks

maka urutan dari indeks tersebut adalah 0 1 2 3 4 

6. Penulisan Antar statement/baris tidak diakhiri dengan 'titik koma' melainkan ganti baris '\n'/ENTER 
lalu apa itu Statement pada Python? Statemen adalah sebuah pernyataan atau instruksi yang akan dieksekusi oleh mesin. 
Interpreter python akan bertugas untuk menginterpretasikan setiap statemen menjadi perintah mesin yang sesuai

Lalu, bagaimana cara interpreter python membedakan antar satu statemen dengan statemen lainnya? 
yaitu dengan adanya proses ganti baris '\n'/ENTER. 

Setiap pergantian baris, interpreter akan menganggap bahwa sebuah statemen telah sempurna.

lalu kapan 'titik koma' bisa digunakan? ketika terdapat lebih dari 1 statement dalam 1 baris.

Ex : a = 5; b = 8; c = a + b;

Statement yang terlalu panjang dalam 1 barus akan sulit untuk dibaca, didebug dan dipahami oleh mesin.
namun jika kita buat baris baru maka statement tsb akan error karena terputus dan tidak bisa dijalankan oleh interpreter.

Ex : kondisi = 10 < 5  and 10 > 9 or 11 == 6 + 5 and 0 == 100 * 5 / (25 - 15)

solusinya adalah menggunakan backslash (\)

Sebagai contohnya adalah:

kondisi = 10 < 5 \
  and 10 > 9 \
  or 11 == 6 + 5 \
  and 0 == 100 * 5 / (25 - 15)

Meskipun kode program di atas memiliki total 4 baris, tapi interpreter tetap menganggapnya sebagai satu statemen utuh.


7. Tidak Ketat Terhadap Tipe Data
Kita bisa memberi dan mengubah nilai apa pun dari tipe data apa pun ke dalam sebuah variabel.
# nilai awal berupa integer
a = 5
# kita ubah menjadi string dan tidak error
a = 'Jathy Hardhiyan'

print(a)

8. Tanda Petik dan Tanda Petik Dua
Dalam bahasa pemrograman python, kita bisa mendefinisikan string dengan tanda petik satu ('') maupun tanda petik dua ("").

nama = 'jathy'
asal = "Indonesia"

9. Penulisan Komentar
Komentar satu baris ditulis dengan tanda (#) 
Sedangkan komentar lebih dari satu baris ditulis dengan triple doublequote (""""...""")(tanda petik dua sebanyak 3x).

NOTE: 
Menambahkan '\n' sebelum Tipe data 'String' akan memberikan 'Enter' atau baris baru
Immutable, artinya isi yang tidak bisa di ubah dan di hapus
Replicate, data yang bersifat duplicate
Unordered, artinya tidak terurut atau acak



VARIABEL 
Variabel di python merupakan tempat menyimpan data, Di python, kita bisa memasukkan tipe data apa saja ke dalam sebuah variabel, tanpa harus 
mendefinisikan tipe datanya terlebih dahulu. hal ini berbeda dengan beberapa bahasa pemrograman lain yang mengharuskan kita 
mendefinisikan tipe data terlebih dahulu sebelum menentukan sebuah variabel.

Tipe data –sesuai namanya– ia adalah jenis dari suatu data. Setiap data memiliki nilai, dan setiap nilai memiliki jenis. 
Ada data-data yang bertipe angka, ada pula yang bertipe huruf/karakter, ada juga yang bertipe benar/salah dan sebagainya.

Berikut ini aturan-aturannya secara sederhana:

1.Nama variabel hanya boleh diawali oleh huruf atau underscore.
2.Nama variabel tidak boleh diawali oleh angka.
3.Nama variabel hanya bisa terdiri dari karakter alpha-numeric dan underscore (A-z, 0-9, and _ ).
4.Nama variabel bersifat case sensitive. Artinya variabel nama berbeda dengan Nama atau naMA.
5.Nama Variabel tidak boleh ada character yang digunakan dalam programan Python seperti modulus (%), Operator Logika dsb.

Aturan Assignment
Aturan assignment atau aturan pemberian nilai terhadap variabel di dalam Python bisa selesai secara multiple mau pun secara single.

Cara single adalah dengan memberikan satu nilai terhadap satu variabel dalam satu baris, 
sedangkan cara multiple adalah dengan memberikan multiple nilai terhadap multiple variables dalam satu baris

Ex:
a, b, c = 1, 2, "Mantap"

print('a:', a)
print('b:', b)
print('c:', c)

# kita juga bisa memberikan satu nilai yang sama untuk
# beberapa variabel

d = e = f = 10

print('d:', d)
print('e:', e)
print('f:', f)

"""Tipe Data pada Python"""

Text Types      : str
Numeric Types   : int, float, complex
Sequence Types  : list, tuple, range
Mapping Types   : dict
Set Types       : set, frozenset
Boolean Types   : bool
Binary Types    : bytes, bytearray, memoryview
None Types      : NoneType

Selain itu jika kita tidak tahu tipe apakah data yang kita akan masukkan, kita bisa mengecek,memeriksa atau mengetahui tipe data dari suatu variabel.
Untuk melakukannya, kita bisa menggunakan fungsi type() bawaan python.

a = 'Jakarta'
b = 50

print(type(a))
print(type(b))

<class 'str'>
<class 'int'>

1. Artimatika pada Python

Penjumlahan     +   1 + 3 = 4   Menjumlahkan nilai dari masing-masing operan atau bilangan
Pengurangan     -   4 - 1 = 3   Mengurangi nilai operan di sebelah kiri menggunakan operan di sebelah kanan
Perkalian       *   2 * 4 = 8   Mengalikan operan/bilangan
Pembagian       /   10 / 5 = 2  Untuk membagi operan di sebelah kiri menggunakan operan di sebelah kanan
Sisa Bagi       %   11 % 2 = 1  Mendapatkan sisa pembagian dari operan di sebelah kiri operator ketika dibagi oleh operan di sebelah kanan
Pangkat         **  8 ** 2 = 64 Memangkatkan operan disebelah kiri operator dengan operan di sebelah kanan operator
Pembagian Bulat //  10 // 3 = 3 Sama seperti pembagian. Hanya saja angka dibelakang koma dihilangkan


2. Perbandingan pada Python
"""Operator perbandingan/relasi adalah operator yang bertugas untuk membandingkan antar dua Operand. Jika hasil perbandingan benar, 
maka akan menghasilkan nilai True, dan sebaliknya jika salah maka akan menghasilkan nilai False"""

Sama dengan                     ==  1 == 1  bernilai True Jika masing-masing operan memiliki nilai yang sama, maka kondisi bernilai benar atau True.
Tidak sama dengan               !=  2 != 2  bernilai False Akan menghasilkan nilai kebalikan dari kondisi sebenarnya.
Tidak sama dengan               <>  2 <> 2  bernilai False Akan menghasilkan nilai kebalikan dari kondisi sebenarnya.
Lebih besar dari                >   5 > 3   bernilai True Jika nilai operan kiri lebih besar dari nilai operan kanan, maka kondisi menjadi benar.
Lebih kecil dari                <   5 < 3   bernilai True Jika nilai operan kiri lebih kecil dari nilai operan kanan, maka kondisi menjadi benar.
Lebih besar atau sama dengan    >=  5 >= 3  bernilai True Jika nilai operan kiri lebih besar dari nilai operan kanan, atau sama, maka kondisi menjadi benar.
Lebih kecil atau sama dengan    <=  5 <= 3  bernilai True Jika nilai operan kiri lebih kecil dari nilai operan kanan, atau sama, maka kondisi menjadi benar

3. Penugasan pada Python
"""Operator Assignment adalah operator untuk memasukkan suatu nilai/tugas ke dalam suatu variabel. Dalam Bahasa Pemrograman Python, 
Operator Assignment menggunakan tanda sama dengan (=). Misal nilai = 29, artinya nilai telah diberi tugas untuk menyimpan angka 29."""

Sama dengan/Pengisian       =       a = 1   Memberikan nilai di kanan ke dalam variabel yang berada di sebelah kiri.
Tambah sama dengan          +=      a += 2  Memberikan nilai variabel dengan nilai variabel itu sendiri ditambah dengan nilai di sebelah kanan.
Kurang sama dengan          -=      a -= 2  Memberikan nilai variabel dengan nilai variabel itu sendiri dikurangi dengan nilai di sebelah kanan.
Kali sama dengan            *=      a *= 2  Memberikan nilai variabel dengan nilai variabel itu sendiri dikali dengan nilai di sebelah kanan.
Bagi sama dengan            /=      a /= 4  Memberikan nilai variabel dengan nilai variabel itu sendiri dibagi dengan nilai di sebelah kanan.
Sisa bagi sama dengan       %=      a %= 3  Memberikan nilai variabel dengan nilai variabel itu sendiri dibagi dengan nilai di sebelah kanan. Yang diambil nantinya adalah sisa baginya.
Pangkat sama dengan         **=     a **= 3 Memberikan nilai variabel dengan nilai variabel itu sendiri dipangkatkan dengan nilai di sebelah kanan.
Pembagian bulat sama dengan //=     a //= 3 Membagi bulat operan sebelah kiri operator dengan operan sebelah kanan operator kemudian hasilnya diisikan ke operan sebelah kiri.
&=                                  x &= 3  sama dengan x = x & 3   
|=                                  x |= 3  sama dengan x = x | 3   
^=                                  x ^= 3  sama dengan x = x ^ 3   
>>=                                 x >>= 3 sama dengan x = x >> 3  
<<=                                 x <<= 3 sama dengan x = x << 3

4. Logika pada Python
"""Operator Logika digunakan untuk membandingkan dua Operand atau dua nilai yang bertipe BOOLEAN dan akan menghasilkan nilai Boolean yaitu TRUE atau FALSE.
Operator logika adalah operator yang sangat penting. Operator ini sangat berkaitan erat dengan operator perbandingan.
Dan kedua-duanya juga mengembalikan nilai dengan tipe data yang sama yaitu BOOLEAN."""

and                                 x < 5 and  x < 10       Mengembalikan True jika dua statement sama-sama benar    
or                                  x < 5 or x < 4          Mengembalikan True jika salah satu statement bernilai benar
not                                 not(x < 5 and x < 10)   Menegasikan hasil. True menjadi False dan sebaliknya

5. Identitas pada Python
"""Operator ini didefinisikan dengan is dan is not. Tugasnya adalah untuk mengetahui apakah dua buah variabel merupakan objek yang sama atau memiliki nilai yang sama atau tidak. 
Jika sama akan menghasilkan nilai TRUE dan sebaliknya, jika salah akan menghasilkan nilai FALSE.
Karena tidak semua nilai yang sama memiliki tempat / posisi yang sama di dalam memori."""

is                                  x is y          Menghasilkan nilai TRUE jika kedua nilai operand memiliki identitas yang sama.
is not                              x is not y      Menghasilkan nilai FALSE jika kedua nilai operand memiliki identitas yang sama.

6. Keanggotaan pada Python
"""Operator Keanggotaan hanya bisa digunakan pada variable jenis SEQUENCE yang dapat menampung banyak nilai. 
Fungsi dari operator ini adalah untuk memeriksa apakah suatu nilai merupakan salah satu anggota dari variabel berjenis sequence atau tidak. 
Kemudian akan menghasilkan nilai TRUE atau FALSE."""

in                                  x in y          Menghasilkan nilai TRUE jika nilai yang ditentukan berada dalam objek tertentu 
not in                              x not in y      Menghasilkan nilai TRUE jika nilai yang ditentukan tidak ada dalam objek tertentu

7. Bitwise pada Python
"""Jenis operator terakhir ini hampir sama seperti Operator Logika, akan tetapi operator ini melakukan operasi berdasarkan bilangan BIT/BINARY. 
Bilangan biner sendiri merupakan jenis bilangan yang hanya terdiri dari dua jenis angka, yakni 0 dan 1. 
Jika nilai asal yang dipakai bukan bilangan biner, akan dikonversi secara otomatis oleh Python menjadi bilangan biner."""

&   Bitwise AND                     Mengembalikan bit 1 jika dua bit bernilai 1
|   Bitwise OR                      Mengembalikan bit 1 jika salah satu bit bernilai 1
 ^  Bitwise XOR                     Mengembalikan bit 1 jika hanya satu bit saja yang bernilai 1
~   Bitwise NOT                     Membalikkan semua bit
<<  Bitwise Zero fill left shift    Menggeser bit ke kiri dengan mendorong digit 0 dan membiarkan bit paling kiri terlepas
>>  Bitwise Signed right shift      Menggeser bit ke kanan dengan mendorong salinan digit sebelah kiri dan membiarkan digit sebalah kanan terlepas



-- Urutan Operasi Artimatika

• Dari dulu, operasi perhitungan selalu dimulai dari tanda kurung (Parenthese), pangkat (Exponensial), perkalian
(Multiplication) dan pembagian (Division), sampai penjumlahan (Addition) dan pengurangan (Subtraction). Agar
lebih mudah mengingatnya, kita bisa persingkat menjadi PEMDAS.
• Jika kedudukannya sama, maka dimulai dari yang paling kiri (yang paling dulu dikomputasi.

--Lalu secara keseluruhan Prioritas Eksekusi OPERATOR pada Python adalah:

**                                  Aritmatika
~, +, -                             Bitwise
*, /, %, //                         Aritmatika
+, -                                Aritmatika
>>, <<                              Bitwise
&                                   Bitwise
^, |                                Bitwise
<=, <, >, >=                        Perbandingan
<> , ==, !=                         Perbandingan
=, %=, /=, //=, -=, +=, *=, **=     Penugasan
is, is not                          Identitas
in, not in  Membership              (Keanggotaan)
not, or, and                        Logika


"""DATA STRUCTURE/COLLECTION"""
1. LIST STRUCTURE / List

List berfungsi untuk merepresentasikan/menyimpan berbagai jenis data (values) dalam satu variabel.

Tipe data list adalah tipe data koleksi yang bersifat ordered (terurut) dan juga bersifat changable atau muteable (bisa diubah). 
Tipe data ini bisa kita definisikan dengan tanda kurung siku [] di dalam Python. Kurung siku sendiri merupakan hal unik yang dimiliki LIST.

List merupakan salah satu dari empat jenis built in data types dari python selain tuple, set dan dictionary

• Tidak hanya angka, list juga bisa diisi dengan jenis data lainnya
• Selain itu, kita juga bisa memasukkan list di dalam list, yang artinya bisa ada beberapa list dalam sebuah list besar.
• list juga bisa diisi dengan kombinasi jenis tipe data yang berbeda, bisa ada tipe data String, Integer dan bahkan Boolean dalam 1 list yang sama.

List bersifat ordered (berurutan) sehingga setiap elemennya pasti memiliki index dan negative index.
Yang perlu diperhatikan adalah: bahwa indeks negatif tidak dimulai dari 0, akan tetapi dimulai dari angka 1.

 P  Y  T  H  O N
 0  1  2  3  4 5  #Urutan Indeks
-6 -5 -4 -3 -2-1  #Negative Indeks

# list kosong
list_kosong = []

# list yang berisi kumpulan string
list_buah = ['Pisang', 'Nanas', 'Melon', 'Durian']

# list yang berisi kumpulan integer
list_nilai = [80, 70, 90, 60]

# list campuran berbagai tipe data
list_jawaban = [150, 33.33, 'Presiden Sukarno', False]

print('list_kosong:', list_kosong)
print('list_buah:', list_buah)
print('list_nilai:', list_nilai)
print('list_jawaban:', list_jawaban)

Slicing list adalah teknik untuk memotong nilai pada list yang dimaksudkan untuk kita 
mengambil beberapa nilai dari anggota list dengan mendefinisikan indeks kiri dan indeks kanan.

a. parameter indeks sebelah kiri mendefinisikan awal indeks dari nilai yang akan ditampilkan.
b. parameter indeks sebelah kanan mendefinisikan batas yang harus ditampilkan.

list_buah = ['Pisang', 'Nanas', 'Melon', 'Durian']

print(list_buah[0:1])
print(list_buah[0:2])
print(list_buah[1:3])
print(list_buah[0:-1])
print(list_buah[-1:-3])
print(list_buah[-1:3])
print(list_buah[-3:-1])

['Pisang']
['Pisang', 'Nanas']
['Nanas', 'Melon']
['Pisang', 'Nanas', 'Melon']
[]
[]
['Nanas', 'Melon']

Kita juga bisa melakukan slicing data tanpa mendefinisikan indeks batas
list_buah = ['Pisang', 'Nanas', 'Melon', 'Durian']

print(list_buah[0:])
print(list_buah[1:])
print(list_buah[2:])
print(list_buah[3:])
print(list_buah[:0])
print(list_buah[:1])
print(list_buah[:2])
print(list_buah[:3])
print(list_buah[:4])

['Pisang', 'Nanas', 'Melon', 'Durian']
['Nanas', 'Melon', 'Durian']
['Melon', 'Durian']
['Durian']
[]
['Pisang']
['Pisang', 'Nanas']
['Pisang', 'Nanas', 'Melon']
['Pisang', 'Nanas', 'Melon', 'Durian']

"""Lalu bagaimana caranya mengubah data yang terdapat dalam LIST?"""

list_buah = ['Pisang', 'Nanas', 'Melon', 'Durian']

print(list_buah)

# ubah data pertama
list_buah[0] = 'Jeruk'

print(list_buah)

# ubah data terakhir
list_buah[-1] = 'Mangga'

print(list_buah)

# ubah data dalam range
list_buah[1:3] = ['Naga', 'Pepaya']

print(list_buah)

list_buah = ['Jeruk', 'Naga', 'Pepaya', 'Mangga']
print(list_buah)

# tambah data di BELAKANG list
list_buah.append('Sirsak')
print(list_buah)

Parameter pertama untuk mendefinisikan posisi indeks dari data yang akan dimasukkan
Parameter kedua untuk mendefinisikan nilai yang akan dimasukkan ke dalam list

# tambah data di awal list
list_buah.insert(0, 'Jambu')
print(list_buah)

# tambah data di index mana pun dalam list
list_buah.insert(2, 'Manggis')
print(list_buah)

Method Insert bisa membuat kita dapat menambahkan data di posisi mana pun.

Method dan fungsi Build-in pada List Python
len(nama_list)
max(nama_list)
min(nama_list)
type(nama_list)

"""MENGHAPUS DATA DALAM LIST"""

Untuk menghapus item dari list, kita bisa menggunakan dua buah fungsi; 
fungsi pop() dan fungsi remove(), kita juga bisa menggunakan statement del.

Fungsi pop() akan mengambil item terakhir dari sebuah list, lalu menghapusnya. 
Karena ia juga “mengambil”, maka kita bisa menyimpan hasil kembalian dari fungsi pop() ke dalam sebuah variabel.

list_angka = [1, 2, 3, 4, 5]
print(list_angka)

# hapus satu angka di belakang
angka_yang_terhapus = list_angka.pop()

print('angka yang terhapus:', angka_yang_terhapus)
print(list_angka)

[1, 2, 3, 4, 5]
angka yang terhapus: 5
[1, 2, 3, 4]

Selanjutnya adalah fungsi remove(). 
Fungsi ini akan menghapus data yang memiliki nilai yang sama dengan parameter yang dimasukkan.
yang artinya fungsi ini dapat menghapus data yang sama dengan yang didefinisikan

list_buah = ['Mangga', 'Jambu', 'Jeruk', 'Jambu']
print(list_buah)

# hapus item pertama dengan nilai 'Jambu'
list_buah.remove('Jambu')

print(list_buah)

['Mangga', 'Jambu', 'Jeruk', 'Jambu']
['Mangga', 'Jeruk', 'Jambu']

Selanjutnya, kita juga bisa menghapus item pada list dengan menggunakan statement del. 
Dengan statement ini, kita bisa menghapus indeks berapa pun dari item list.

print('\n' * 2) #melakukan enter 2x

list_buah = ['Mangga', 'Jambu', 'Jeruk', 'Jambu']
print(list_buah)

del list_buah[1]
print(list_buah)

del list_buah[0:2]
print(list_buah)

['Mangga', 'Jambu', 'Jeruk', 'Jambu']
['Mangga', 'Jeruk', 'Jambu']
['Jambu']

menggabungkan dua buah list (atau lebih) menjadi satu kesatuan

a = [1, 2, 3]
b = ['a']
c = [True, 'b', False]

listBaru = a + b + c

hanya bermodalkan '+'

Terakhir tapi bukan yang paling akhir, kita bisa mengurutkan data list pada python dengan memanggil fungsi <list>.sort().

list_buah = ['Mangga', 'Jeruk', 'Zaitun', 'Apel', 'Durian']
print(list_buah)

# urutkan secara ascending
list_buah.sort()
print(list_buah)

# membalikkan posisi item list (tidak harus berurut)
list_buah.reverse()
print(list_buah)

['Mangga', 'Jeruk', 'Zaitun', 'Apel', 'Durian']
['Apel', 'Durian', 'Jeruk', 'Mangga', 'Zaitun']
['Zaitun', 'Mangga', 'Jeruk', 'Durian', 'Apel']

Beberapa Method Yang bisa digunakan dalam tipe data atau struktur LIST. 

append()    Menambahkan elemen baru pada list
clear()     Menghapus semua item pada list
copy()      Mengembalikan hasil duplikat dari list
count()     Mengembalikan jumlah item pada list sesuai yang didefinisikan
index()     Mengembalikan indeks pertama dari item yang sudah didefinisikan
insert()    Menambahakn item baru pada list pada posisi tertentu
pop()       Menghapus item terakhir pada list, atau juga bisa menghapus item pada posisi yang didefinisikan
remove()    Hapus item pada list sesuai dengan nilai yang didefinisikan
reverse()   Membalikkan posisi tiap item pada list
sort()      Mengurutkan list


2. TUPLE STRUCTURE / Tuple

Apa bedanya Tuple dengan List?
Pada dasarnya Tuple sama saja dengan list. Dia sama-sama digunakan untuk menyimpan data himpunan. 
Sama-sama bisa menampung berbagai macam tipe data dalam satu himpunan. namun tentu ada beberapa perbedaan. 
Hanya saja setelah diberi nilai, tuple tidak bisa diubah lagi. Hal ini berbeda dengan list.

Tuple bersifat ordered (terurut) dan juga bersifat """unchangable/immuteable""" (tidak bisa diubah). 
Ordered berarti datanya bisa kita akses menggunakan indeks, 
dan unchangeable berarti datanya tidak akan pernah bisa diubah setelah pertama kali definisikan.

Variable yang menyimpan value disertai dengan koma bisa menjadi Tuples.

Dalam python, tipe data tuple didefinisikan dengan tanda kurung biasa (). berbeda dengan list yang menggunakan kurung siku [].

# cara standar
tuple_jenis_kelamin = ('laki-laki', 'perempuan')

# tanpa kurung
tuple_status_perkawinan = 'menikah', 'lajang'

# menggunakan fungsi tuple()
tuple_lulus = tuple(['lulus', 'tidak lulus'])

Cara yang pertama adalah cara standar dan paling dasar
Cara yang kedua tanpa tanda kurung. Ini mungkin kelihatan agak aneh, tapi yang seperti ini normal di python 😏
Cara yang ketiga adalah dengan menggunakan fungsi tuple() dan melemparkan list sebagai parameternya.

Cara Akses Tuple (Index-slicing)

Mengakses data pada tuple tidak jauh berbeda dengan cara mengakses data pada list, bahkan bisa kita bilang sama persis dalam keumumannya.
Sama seperti halnya List, Cara akses nilai di dalam Tuple menggunakan tanda kurung siku ([]).

#TUPLE STRUCTURE

# cara standar
tuple_jenis_kelamin = ('laki-laki', 'perempuan')

# tanpa kurung
tuple_status_perkawinan = 'menikah', 'lajang'

# menggunakan fungsi tuple()
tuple_lulus = tuple(['lulus', 'tidak lulus'])

print(tuple_jenis_kelamin)
print(tuple_status_perkawinan)
print(tuple_lulus)

#Untuk membuat tuple kosong, kita cukup dengan menuliskan dua tanda kurung seperti berikut:

tuple_kosong = ()

print(tuple_kosong)

#Untuk mendefinisikan tuple yang hanya berisi satu item, kita tetap diharuskan menulis tanda koma.

tuple_tunggal = (10,)

print(tuple_tunggal)

#Karena jika tidak, maka python akan menggap tanda kurungnya tidak ada.

print(type((10))) # yang ini dianggap integer biasa
print(type((10,))) # yang ini dianggap tuple

#Indexing

tuple_jenis_kelamin = ('laki-laki', 'perempuan')

print(tuple_jenis_kelamin[1]) # indeks satu
print(tuple_jenis_kelamin[0]) # indeks nol

#Negative Index

print(tuple_jenis_kelamin[-2])
print(tuple_jenis_kelamin[-1])

#Slicing Tuple dengan batas

tuple_buah = ('Pisang', 'Nanas', 'Melon', 'Durian')

print(tuple_buah[0:1])
print(tuple_buah[0:2])
print(tuple_buah[1:3])
print(tuple_buah[0:-1])
print(tuple_buah[-1:-3])
print(tuple_buah[-1:3])
print(tuple_buah[-3:-1])

#Slicing Tuple tanpa batas

tuple_buah = ('Pisang', 'Nanas', 'Melon', 'Durian')

print(tuple_buah[0:])
print(tuple_buah[1:])
print(tuple_buah[2:])
print(tuple_buah[3:])
print(tuple_buah[:0])
print(tuple_buah[:1])
print(tuple_buah[:2])
print(tuple_buah[:3])
print(tuple_buah[:4])



Kita telah mempelajari pada pertemuan sebelumnya bahwa kita bisa mengubah data pada list. Akan tetapi, berbeda dengan Tuple. 
Kita tidak bisa mengubah data pada tuple. Dan jika kita kekeuh berusaha mengubah data tertentu dari tuple, kita hanya akan mendapatkan error.

# mencoba edit data list
list_siswa = ['Andi', 'Budi']
list_siswa[0] = 'Ardi'

# mencoba edit data tuple
tuple_siswa = ('Andi', 'Budi')
tuple_siswa[0] = 'Ardi'

#TUPLE tidak bisa diubah, berbeda dengan list

Fungsi bawaan Tuple
len(tuple) Mengembalikan total panjang tuple 
max(tuple) Mengembalikan item dari tuple dengan nilai max
min(tuple) Mengembalikan item dari tuple dengan nilai min
tuple(seq) Mengubah a sequence list of items menjadi tuple

#Sequence Unpacking
equence unpacking. Fitur ini berfungsi untuk mengekstrak isi dari tuple ke dalam variabel-variabel tunggal secara berurutan. 
Kita hanya perlu menggunakan operator assignment standar (simbol sama dengan =) dan mendefinisikan nama variabel dengan koma.

siswa = ('Jathy Hardhiyan', 'Magelang', 18)

# ekstrak data atau juga dinamakan sequence unpacking
nama, asal, usia = siswa

# setiap variabel di atas akan memiliki nilai dari tiap isi tuple
# secara berurutan
print('Nama:', nama)
print('Asal:', asal)
print('Usia:', usia)

#Variabel nama memiliki nilai dari siswa[0]
#Variabel asal memiliki nilai dari siswa[1]
#Variabel usia memiliki nilai dari siswa[2]

Menggabungkan dua buah tuple atau lebih

Hal lain yang bisa kita lakukan dengan tuple adalah: menggabungkan beberapa tuple menjadi satu tuple baru.

Kita bisa melakukan hal tersebut menggunakan operator penjumlahan (+)

#Menggabungkan 2 Tuple berbeda menjadi 1

a = (1, 2, 3)
b = (50, 60, 70)

Join_Tuple = a + b

print(Join_Tuple)

print(min(a))

print(max(b))

len((Join_Tuple))

3. DICTIONARY STRUCTURE / Dictionary 

Dictionary merupakan jenis built-in data types yang terdiri dari 'key' dan 'value' sebagai elementnya
(berbeda dari list yang terdiri dari index yang sudah tersusun dengan angka secara berurutan dan element).

Singkatnya Dictionary adalah Data Strukture pada python yang berfungsi untuk menyimpan kumpulan 
data/nilai dengan pendekatan “Key-Value”.

a.  Yang pertama adalah 'key', ia merupakan nama atribut suatu item pada dictionary.
b.  Yang kedua adalah 'value', ia adalah nilai yang disimpan pada suatu atribut.

 KEY    VALUES
"page": 10000

Dictionary items memiliki beberapa sifat, yaitu

• Unordered - tidak berurutan
• Changeable - bisa diubah
• Unique - alias tidak bisa menerima dua keys yang sama
• Values bisa dimasuki semua jenis data yang berbeda sifat
• Karakteristik utama dari Dictionary adalah memiliki kurung kurawal {}
•

'Unordered' artinya ia tidak berurutan, sehingga key/atribut yang pertama kali kita definisikan, 
tidak berarti dia akan benar-benar menjadi yang “pertama” dibandingkan dengan key yang lainnya. 
Juga, unordered berarti tidak bisa diakses menggunakan index (integer) sebagaimana halnya list. 

Sedangkan changeable artinya kita bisa kita mengubah 'value' yang telah kita masukkan ke dalam sebuah dictionary. 
Hal ini berbeda dengan tipe data set mau pun tuple yang mana keduanya bersifat immutable alias tidak bisa diubah.

Dictionary tidak bisa memiliki lebih dari satu 'key' yang sama karena ia bersifat unique. Sehingga jika ada dua buah 
key yang sama, key yang didefinisikan terakhir akan menimpa nilai dari key yang didefinisikan lebih awal.

#Key pada Dictionary bersifat UNIQUE
#Key yang sama dan dimasukan terakhir kali akan menimpa key sebelumnya

artikel = {
  "judul": "Menu Masakan Enak",
  "judul": "Menu Masakan Enak Tradisional"
}

print(artikel.get("judul"))

item pada dictionary juga bisa menerima berbagai macam tipe data, 
mulai dari tipe data asli mau pun tipe data terusan seperti objek.

Untuk membuat dictionary terdapat 2 cara:

a. Yang pertama dengan tanda kurung kurawal {}.
b. Dan yang kedua bisa menggunakan fungsi atau konstruktor dict().

# cara pertamaa
buku = {
  "judul": "Daun Yang Jatuh Tidak Pernah Membenci Angin",
  "penulis": "Tere Liye"
}

print(buku)

# cara kedua
buku2 = dict(
  judul="Daun Yang Jatuh Tidak Pernah Membenci Angin",
  penulis="Tere Liye"
)

print(buku2)

pertemuan_hari_ini = {
  "judul": "Belajar Dictionary Pada Python 3",
  "tanggal": "01 Februari 2021",
  "kategori": ["Python", "Python Dasar"],
  "page_views": 10,
  "published": True,
  "share_count": {"facebook": 0,"twitter": 2}
}

#Terdapat berbagai tipe data seperti String, Integer bahkan Boolean dan List

Kita bisa mengakses item pada dictionary dengan dua cara:

a. dengan menggunakan kurung siku ([]) dan menuliskan key nya sesuai dengan yang diinginkan
b. atau dengan menggunakan fungsi get()

Perlu diingat bahwa Dictionary Tidak dapat menggunakan slicing atau stride 
karena bentuk key tidak hanya terpaku dengan angka yang berurutan seperti index. 



print('Judul:', pertemuan_hari_ini.get('judul'))
# atau
print('Tanggal:', pertemuan_hari_ini['tanggal'])

# bisa menggunakan fungsi berantai untuk dictionary bertingkat
print('Facebook share:', pertemuan_hari_ini.get('share_count').get('facebook'))
# bisa juga dengan kurung siku dua-duanya
print('Twitter share:', pertemuan_hari_ini['share_count']['twitter'])

Hanya saja fungsi get() memiliki keunggulannya tersendiri,
Kita bisa mengatur nilai default jika 'key' pada dictionary yang kita panggil tidak ditemukan. 
Hal itu akan mencegah sistem untuk menampilkan error.

share_count = pertemuan_hari_ini.get('share_count')

# ini error
print('Instagram share:', share_count['instagram'])
# sedangkan ini tidak error
print('Instagram share:', share_count.get('instagram', 0))

--
share_count = pertemuan_hari_ini.get('share_count')

# ini error
#print('Instagram share:', share_count['instagram'])
# sedangkan ini tidak error
print('Instagram share:', share_count.get('instagram', 0))

#Kita juga bisa menampilkan semua isi dari sebuah dictionary dengan memanfaatkan perulangan.

buku = {
  'judul': 'Hafalan Sholat Delisa',
  'penulis': 'Tere Liye'
}

for key in buku:
  print(key, '->', buku[key])

#Atau kita juga bisa memanggil fungsi dictionary.items() untuk perulangan yang lebih simpel

for nama_atribut, nilai in buku.items():
  print(nama_atribut, '->', nilai)


Terkadang, kita akan kesulitan untuk mencari dictionaries aslinya di dalam suatu barisan code jika sudah sangat
banyak, Untuk mengakses dictionaries secara keseluruhan, terdapat tiga cara

a. Menggunakan Object.keys() untuk mengakses semua 'keys'
b. Menggunakan Object.values() untuk mengakses semua 'values'
c. Menggunakan Object.items() untuk mengakses semua 'keys' dan 'values'

'Mengubah Nilai Item'

Seperti yang telah kita singgung di atas bahwasanya item pada dictionary bersifat changeable alias bisa diubah.

Untuk mengubah nilai item pada suatu dictionary, caranya simpel seperti mengubah variabel pada umumnya.

mahasiswa = {
  'nama': 'Lendis Fabri',
  'asal': 'Indonesia'
}

# mengubah data
print('Nama awal:', mahasiswa.get('nama'))

#Proses berubahnya data
mahasiswa['nama'] = 'Jathy Hardhiyan'
print('Setelah diubah:', mahasiswa.get('nama'))

#Menambahkan data

#Menambahkan Data Di dictionary

mahasiswa['Jenis Kelamin']='Pria'
print(mahasiswa)

#Menambahkan Data Di dictionary

mahasiswa['Jenis Kelamin']='Pria'
print('Setelah di tambahkan data baru:', mahasiswa.get('Jenis Kelamin'))

OUTPUT:

Nama awal: Lendis Fabri
Setelah diubah: Jathy Hardhiyan

a. Kalau key yang kita definisikan ternyata sudah ada, sistem akan me-replace item yang lama dengan yang baru, alias meng-edit
b. Tapi jika key yang kita definisikan ternyata tidak ada, maka sistem akan menambahkannya sebagai item baru.

mahasiswa = {
  'nama': 'Jathy Hardhiyan',
  'asal': 'Indonesia',
}

# output None
print('Hobi:', mahasiswa.get('hobi'))
# tambah data
mahasiswa['hobi'] = 'Memandang Langit'
# print ulang
print('Hobi dari {} adalah {}'.format(
  mahasiswa.get('nama'),
  mahasiswa.get('hobi')
))

Hobi: None
Hobi dari Jathy Hardhiyan adalah Memandang Langit

print(mahasiswa)

{'nama': 'Jathy Hardhiyan', 'asal': 'Indonesia', 'hobi': 'Memandang Langit'}

Menghapus item Dictionary

Terdapat beberapa cara yang berbeda (tergantung tujuan) untuk menghapus item yang ada di dalam Dictionary

a. Menggunakan Object.remove(value) untuk menghapus element secara spesifik
b. Menggunakan Object.discard("target") untuk menghapus element secara spesifik
c. Menggunakan Object.pop(value) untuk menghapus suatu elemen dan kita bisa mendapatkan nilai kembalian dari data yang telah dihapus.
d. Menggunakan Object.clear() untuk menghapus isi seluruh elemen
e. Dapat juga menggunakan fungsi Object.del() untuk menghapus suatu value secara spesifik


4. SETS STRUCTURE / Sets

Set dalam bahasa pemrograman python adalah tipe data kolektif yang digunakan untuk menyimpan banyak nilai dalam satu variabel dengan ketentuan:

a. nilai anggota yang disimpan harus unik (tidak duplikat).
b. nilai anggota yang sudah dimasukkan tidak bisa diubah lagi.
c. set bersifat unordered alias tidak berurut –yang artinya tidak bisa diakses dengan index.
d. Sets bersifat mutable tapi tidak replicate (jika ada lebih dari satu element data yang sama, data duplikat setelahnya tidak akan dimasukkan ke dalam sets).
e. Sets merupakan jenis built-in data types yang paling unik dikarenakan tidak memiliki indeks seperti list dan tuples ataupun 'key' seperti dictionaries.
f. Karakteristiknya mirip dengan dictionaries, dimana sets menggunakan kurung kurawal { } untuk menyimpan data. 
g. Sets tidak bisa diisi oleh jenis built-in data types yang bersifat mutable (seperti list, set, dan dictionaries).

secara teori & umum kita bisa membuat set dengan 2 cara: dengan kurung kurawal {}, atau dengan sebuah list yang kita passing ke dalam fungsi set().

# menggunakan kurung kurawal
himpunan_siswa = {'Huda', 'Lendis', 'Wahid', 'Basith'}
print(himpunan_siswa)

# mengkonversi list ke dalam set
himpunan_buah = set(['mangga', 'apel'])
print(himpunan_buah)

# set dengan tipe data yang berbeda-beda
set_campuran = {'manusia', 'hewan', 5, True, ('A', 'B')}
print(set_campuran)

Tipe data set bersifat unordered alias tidak berurut. Itu artinya, kita tidak bisa menggunakan 'index' untuk mengakses nilai pada set. 
Kalau pun kita memaksa, kita hanya akan mendapatkan error.
Karena Sets bersifat Unordered maka isi dari Sets, meskipun kita mencoba memanggilnya maka hasilnya akan berbeda dari awalnya,
atau hasilnya akan acak.

Example yang akan menghasilkan Error
set_ku = {'a'}
print(set_ku[0])

Output:
TypeError                                 Traceback (most recent call last)
Input In [1], in <cell line: 2>()
      1 set_ku = {'a'}
----> 2 print(set_ku[0])

TypeError: 'set' object is not subscriptable

Set bersifat unchangable, yang berarti bahwa nilai yang sudah kita masukkan ke dalam set, tidak bisa kita ubah lagi.

Akan tetapi, kita tetap bisa menambah dan menghapus anggota pada set. Dan, karena set bersifat unchangable, 
set juga hanya bisa menerima anggota dari tipe data yang juga bersifat immutable.

# anggota set harus dari tipe data yang immutable
set_buah = { 'mangga', 'lemon', 'alpukat', True, 1, 2, 3 }

# kita bisa menjadikan tuple sebagai anggota
# karena ia bersifat immutable
papan_ketik = {
  (1, 2, 3),
  (4, 5, 6),
  (7, 8, 9),
  (0)
}

#Tapi kita tidak bisa memasukkan list sebagai anggota karena list bersifat mutable,

x = { 35, 100, ['a', 'b'] }

---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
Input In [4], in <cell line: 1>()
----> 1 x = { 35, 100, ['a', 'b'] }

TypeError: unhashable type: 'list'

Selanjutnya, set pada python juga tidak bisa menerima nilai duplikat. Jika kita memasukkan nilai yang sudah ada pada suatu set, 
maka nilai tersebut hanya akan muncul atau dimasukkan 1 kali saja.

Perhatikan contoh berikut ketika saya membuat list dengan kata “pagi” yang muncul sebanyak 2 kali:


Example dari list:

list_kata = [
  'pagi', 'ini', 'adalah', 'pagi', 'yang',
  'sangat', 'cerah'
]

print(list_kata)

Output:

['pagi', 'ini', 'adalah', 'pagi', 'yang', 'sangat', 'cerah']

Lalu bagaimana jika kita memasukkan data yang sama namun untuk Sets?

kata_unik = {
  'pagi', 'ini', 'adalah', 'pagi', 'yang',
  'sangat', 'cerah'
}

# atau bisa langsung konversi list_kata menjadi set
# supaya lebih ringkas:
# kata_unik = set(list_kata)

print(kata_unik)

Output:

{'yang', 'sangat', 'ini', 'pagi', 'cerah', 'adalah'}

Maka 'Pagi' hanya muncul 1x. 

Seperti yang telah disinggung di atas bahwa meskipun nilai set tidak bisa diubah / unchangable, tapi tetap bisa ditambah dan dihapus.

Kita bisa menambah anggota baru ke dalam set dengan fungsi add() dan fungsi update().

himpunan_abjad = {'a', 'b', 'c'}
print(himpunan_abjad)

# menambah satu-satu
himpunan_abjad.add('d')
himpunan_abjad.add('e')

# menambah lebih dari satu anggota sekaligus
himpunan_abjad.update({ 'f', 'g' })
# bisa juga pakai list
himpunan_abjad.update(['h', 'i'])

print(himpunan_abjad)

Output:

{'a', 'c', 'b'}

{'i', 'e', 'g', 'f', 'a', 'c', 'b', 'h', 'd'}

Untuk menghapus anggota pada set, terdapat 4 fungsi yang bisa kita gunakan:

a. remove(nilai) Untuk menghapus nilai yang dicari. Jika nilai yang dicari tidak ada, maka akan error.

b. discard(nilai) Untuk menghapus nilai yang dicari. Jika nilai yang dicari tidak ada, tidak akan error.

c. pop() Mengambil dan menghapus nilai yang ada di sebelah kiri.

d. clear() Menghapus semua anggota.

himpunan = {'maya', 'budi', 100, ('a', 'b'), False, True}
print(himpunan)

{'maya', False, True, 'budi', 100, ('a', 'b')}

# akan error jika nilai 100 tidak ada di dalam set
himpunan.remove(100)
print(himpunan)

{'maya', False, True, 'budi', ('a', 'b')}
---------------------------------------------------------------------------
KeyError                                  Traceback (most recent call last)
Input In [13], in <cell line: 2>()
      1 # akan error jika nilai 100 tidak ada di dalam set
----> 2 himpunan.remove(100)
      3 print(himpunan)

KeyError: 100

# tidak akan error jika ('a', 'b') tidak ada di dalam set
himpunan.discard(('a', 'b'))
print(himpunan)

{'maya', False, True, 'budi'}

# remove nilai yang ada di sebelah kiri
nilaiYangDihapus = himpunan.pop()
print('nilaiYangDihapus =', nilaiYangDihapus)
print(himpunan)

nilaiYangDihapus = maya
{False, True, 'budi'}

# hapus semua nilai
himpunan.clear()
print(himpunan)

set()

'Fungsi Keanggotaan Pada Set'
Di antara keunggulan tipe data set adalah: keunikan anggotanya. 
Sehingga, dengan keunikan tersebut, python menyediakan kepada kita berbagai fungsi keanggotaan yang berguna untuk pengolahan data.

a. fungsi union (gabungan)
b. fungsi intersection (irisan)
c. fungsi difference (selisih)
d. fungsi symmetric difference (komplement)
e. dan lain sebagainya

Example:

grup_smp = {'andi', 'budi', 'ratna', 'sari'}

grup_sma = {'putri', 'ratna', 'andi', 'agus'}

UNION 
Kita bisa melakukan operasi union, alias menggabungkan kedua anggota dari grup smp dan grup sma.
Dalam python, kita bisa melakukan operasi union dengan simbol pipe (|) atau bisa memanggil fungsi set.union()

# cara 1
print(grup_smp | grup_sma)
# cara 2
print(grup_smp.union(grup_sma)

Output:
{'agus', 'andi', 'budi', 'ratna', 'sari', 'putri'}
{'agus', 'andi', 'budi', 'ratna', 'sari', 'putri'}

Another Examples
# Membuat set A and B 
A = {1, 2, 3, 4, 5} 
B = {4, 5, 6, 7, 8}

print(A)
print(B)

{1, 2, 3, 4, 5}
{4, 5, 6, 7, 8}

# Gabungan menggunakan operator | palang
# output: {1, 2, 3, 4, 5, 6, 7, 8} 
print(A | B) 

{1, 2, 3, 4, 5, 6, 7, 8}

# Membuat set A and B 
C = {1, 2, 3, 4, 5} 
D = {4, 5, 6, 7, 8}

print(C)
print(D)

{1, 2, 3, 4, 5}
{4, 5, 6, 7, 8}

# Menggunakan fungsi union() 
# output: {1, 2, 3, 4, 5, 6, 7, 8} 
C.union(D) 

{1, 2, 3, 4, 5, 6, 7, 8}

INTERSECTION
intersection atau Irisan berfungsi menggabungkan 2 anggota yang sama dari 2 set yang berbeda,
jadi hanya akan memunculkan anggota yang ada di 2 set yang berbeda.
Kita bisa melakukannya dengan dua cara: yakni menggunakan simbol &, atau menggunakan fungsi set.intersection() seperi berikut

print(grup_smp & grup_sma) # cara 1
print(grup_smp.intersection(grup_sma)) # cara 2

{'ratna', 'andi'}
{'ratna', 'andi'}

Another Examples:
# Membuat set A and B 
A = {1, 2, 3, 4, 5} 
B = {4, 5, 6, 7, 8} 

# Irisan menggunakan operator & 
# output: {4,5} 
print(A & B) 

# Menggunakan fungsi intersection() 
# output: {4,5} 
A.intersection(B) 

# output: {4,5} 
B.intersection(A) 

Output:
{4, 5}

DIFFERENCE
difference atau selisih adalah proses mengekstrak anggota grup pertama, yang bukan anggota grup kedua.
Untuk melakukannya, kita bisa menggunakan simbol - atau dengan memanggil fungsi set.difference()

Untuk melakukannya, kita bisa menggunakan simbol - atau dengan memanggil fungsi set.difference() 

# difference
print('\nanggota grup smp yang bukan anggota grup sma')
print(grup_smp - grup_sma)
print(grup_smp.difference(grup_sma))


anggota grup smp yang bukan anggota grup sma
{'budi', 'sari'}
{'budi', 'sari'}

print('\ndibalik, anggota grup sma yang bukan anggota grup smp:')
print(grup_sma - grup_smp)
print(grup_sma.difference(grup_smp))


dibalik, anggota grup sma yang bukan anggota grup smp:
{'putri', 'agus'}
{'putri', 'agus'}

Another Examples:

# membuat A and B 
A = {1, 2, 3, 4, 5} 
B = {4, 5, 6, 7, 8} 

{1, 2, 3, 4, 5}
{4, 5, 6, 7, 8}

# Menggunakan operator - pada A 
# Output: {1, 2, 3} 
print(A - B) 

{1, 2, 3}

# Output: {1, 2, 3} 
A.difference(B) 

{1, 2, 3}

# Menggunakan operator - pada B 
# Output: {8, 6, 7} 
print(B - A) 

{8, 6, 7}

# Output: {8, 6, 7} 
B.difference(A) 

#Kok jadi beurut ya?
{6, 7, 8}


SYMETRIC DIFFERENCE
Bedanya dengan difference, symmetric difference akan menghasilkan anggota-anggota dari kedua grup, 
yang mana tiap anggota tersebut hanya menjadi anggota dari satu grup saja.

Komplemen dilakukan dengan menggunakan operator ^. Bisa juga dengan menggunakan fungsi symmetric_difference().

# symmetric_difference
print('\nanggota yang hanya ikut satu grup saja:')
print(grup_sma.symmetric_difference(grup_smp))

anggota yang hanya ikut satu grup saja:
{'putri', 'budi', 'sari', 'agus'}

Another Examples
# membuat A and B 
A = {1, 2, 3, 4, 5} 
B = {4, 5, 6, 7, 8} 

{1, 2, 3, 4, 5}
{4, 5, 6, 7, 8}

# Menggunakan operator ^ pada A 
# Output: {1, 2, 3, 6, 7, 8} 
print(A ^ B) 

{1, 2, 3, 6, 7, 8}

# Output: {1, 2, 3, 6, 7, 8} 
A.symmetric_difference(B) 

{1, 2, 3, 6, 7, 8}

# Menggunakan operator ^ pada B 
# Output: {1, 2, 3, 6, 7, 8} 
print(B ^ A) 

{1, 2, 3, 6, 7, 8}

# Output: {1, 2, 3, 6, 7, 8} 
B.symmetric_difference(A) 

{1, 2, 3, 6, 7, 8}


Tabel berikut berisi daftar metode atau fungsi set yang disediakan oleh python.

Metode                          Deskripsi

add()                           Menambahkan satu anggota ke set
clear()                         Menghapus semua anggota set
copy()                          Mengembalikan shallow copy dari set
difference()                    Mengembalikan set baru berisi selisih dua atau lebih set
difference_update()             Menghapus semua anggota set lain yang ada di set ini
discard()                       Menghapus satu anggota dari set
intersection()                  Mengembalikan set baru berisi irisan antara dua atau lebih set
intersection_update()           Mengupdate set dengan irisan set bersangkutan dan set lainnya
isdisjoint()                    Mengembalikan True jika dua set tidak memiliki irisan
issubset()                      Mengembalikan True jika set lain berisi set ini
issuperset()                    Mengembalikan True jika set ini berisi set lain
pop()                           Menghapus dan mengembalikan anggota acak dari sebuah set
remove()                        Menghapus satu anggota dari set
symmetric_difference()          Mengembalikan set baru berisi komplemen dari dua set
symmetric_difference_update()   Mengupdate set dengan komplemen dari set ini dan set lainnya
union()                         Mengembalikan set baru berisi gabungan dua atau lebih set
update()                        Mengupdate set dengan gabungan set ini dan set lainnya

