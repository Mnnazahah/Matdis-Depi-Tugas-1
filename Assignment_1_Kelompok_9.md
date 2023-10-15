# Assignment 01

*Group members*
- Ariel Itsbat Nurhaq (10231018) (Problem #1)
- Noviansyah (10231072) (Problem #2)
- Muchlis Wahyu Saputra (10231054) (Problem #3)
- Eka Kusuma Yanti (10231036) (Problem #4)
- Verina Rahma Dinah (10231090) (Problem #5)

## Problem 1
Manakah pernyataan berikut yang merupakan proposisi?
Berikan juga alasannya
1. Jangan keluar dari ruangan kelas!
2. Berapa kali mahasiswa harus mengikuti kelas Matematika
  diskrit?
3. $3 + y = 14$ 
4. $34 \equiv 1 \quad (\text{mod } 11)$
5. Anita dan Bayu saling berteman.

### Answer
Jawaban yang benar adalah point ke 4 dan ke 5, untuk point ke 4 dikarenakan 34 merupakan ekuivaken 1 yang dimana ekuivalen mengacu pada hubungan antara dua proposisi atau pernyataan yang menyiratkan bahwa keduanya memiliki nilai kebenaran yang sama. Dengan kata lain, jika dua proposisi dianggap ekuivalen, berarti jika salah satu proposisi benar, maka yang lainnya juga benar, dan jika salah satu proposisi salah, maka yang lainnya juga salah. Sebagai contoh, jika kita memiliki dua proposisi A dan B yang dianggap ekuivalen, kita dapat menyatakan bahwa A benar jika dan hanya jika B benar, dan A salah jika dan hanya jika B salah. Dan untuk point kedua mengapa itu termasuk proposisi, karena dapat diuji dengan mengumpulkan informasi hubungan anita dan bayu. Jika memang benar bahwa Anita dan Bayu berteman, maka pernyataan tersebut adalah proposisi yang benar. Jika tidak, maka pernyataan tersebut adalah proposisi yang salah. 

## Problem 2
Di dalam kuliah disinggung terkait operator
logika disjungsi ekslusif (exclusive or), yang disimbolkan $\oplus$.
Susunlah tabel kebenarannya dan berikan dua contoh
proposisi yang mewakili disjungsi ekslusif tersebut.


### Answer
Disjungsi eksklusif hanya bernilai benar jika salah satu proposisinya saja yang benar

Tabel kebenaran disjungsi eksklusif
|$p$ | $q$ | $p \bigoplus q$  |
|--|---|----|
|T | T | F | 
|T | F | T | 
|F | T | F | 
|F | F | F |

Example 1 :

p = "Saya akan liburan ke jakarta"

q = "Saya akan liburan ke yogyakarta"

$p \bigoplus \ q$ = "Saya akan liburan ke jakarta atau liburan ke yogyakarta, tetapi tidak bisa liburan ke dua tempat yang berbeda secara bersamaan"

Example 2 :

p = "Anda bisa memesan kopi panas"

q = "Anda bisa memesan teh dingin"

$p \bigoplus q$ = "Anda bisa memesan kopi panas atau teh dingin, tetapi tidak bisa memesan keduanya"
## Problem 3
Susunlah tabel kebenaran untuk proposisi majemuk berikut:
1. $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$
2. $((p \leftrightarrow \neg q) \oplus r) \vee r$


### Answer
#### 3.1
|$p$|$q$|$\neg p$ | $\neg p \wedge q $| $\neg q $ | $\neg \neg q $ | $\neg \neg q \rightarrow p $ | $ (\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p) $  |
|:-:|:-:|:--:|:----:|:--:|:---:|:------:|:----------------:|
| T | T |  F |   F  |  F |  T  |    T   |         T        |
| T | F |  F |   F  |  T |  F  |    T   |         T        |
| F | T |  T |   T  |  F |  T  |    F   |         F        |
| F | F |  T |   F  |  T |  F  |    T   |         T        |

#### 3.2
|$p$|$q$|$r$|$\neg q$|$p \leftrightarrow \neg q$|$(p\leftrightarrow \neg q) \oplus r$| $((p\leftrightarrow \neg q) \oplus r) \vee r$ |
|:-:|:-:|:-:|:--:|:------:|:----------:|:--------------:|
| T | T | T |  F |    F   |      T     |        T       |
| T | T | F |  F |    F   |      F     |        F       |
| T | F | T |  T |    T   |      F     |        T       |
| T | F | F |  T |    T   |      T     |        T       |
| F | T | T |  F |    T   |      F     |        T       |
| F | T | F |  F |    T   |      T     |        T       |
| F | F | T |  T |    F   |      T     |        T       |
| F | F | F |  T |    F   |      F     |        F       |

## Problem 4
Tentukan konvers, kontrapositive, dan invers dari
pernyataan kondisional berikut
1. Jika hari ini hujan, maka saya tidak akan datang ke
   kuliah matematika diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika
   hari kemarin saya lupa untuk belajar.


### Answer 
1. Diketahui $p \rightarrow q$ dengan dua proposisi $p$ dan $q$ sebagai berikut:

   $p$ = Jika hari ini hujan
   
   $q$ = Maka saya tidak akan datang ke kuliah matematika diskrit
   - Konvers dari $p \rightarrow q$ adalah $q \rightarrow p$

       Jika saya tidak akan datang ke kuliah matematika diskrit, maka hari ini hujan.
   - Kontrapositive dari $p \rightarrow q$ adalah $(\neg q \rightarrow \neg p)$

       Jika saya akan datang ke kuliah matematika diskrit, maka hari ini tidak hujan.
   - Invers dari $p \rightarrow q$ adalah $(\neg p \rightarrow \neg q)$

       Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit.

2. Diketahui $p \rightarrow q$ dengan dua proposisi $p$ dan $q$ sebagai berikut:

   $p$ = Saya akan belajar hingga jam dua dini hari
   
   $q$ = Jika hari kemarin saya lupa untuk belajar
   - Konvers dari $p \rightarrow q$ adalah $q \rightarrow p$

       Jika hari kemarin saya lupa untuk belajar, maka saya akan belajar hingga jam dua dini hari.
   - Kontrapositive dari $p \rightarrow q$ adalah $(\neg q \rightarrow \neg p)$

       Jika hari kemarin saya tidak lupa untuk belajar, maka saya tidak akan belajar hingga jam dua dini hari.
   - Invers dari $p \rightarrow q$ adalah $(\neg p \rightarrow \neg q)$

       Jika saya tidak akan belajar hingga jam dua dini hari, maka hari kemarin saya tidak lupa untuk belajar.

## Problem 5
Sebagai imbalan karena menyelamatkan putri seorang
raja, seorang pemuda diberi kesempatan untuk
memperoleh sejumlah koin emas yang tersimpan
di salah satu tiga kotak yang ditawarkan oleh raja.
Dua kotak diantara tiga kotak merupakan kotak kosong.
Agar pemuda tersebut memperoleh koin emas, dia harus memilih
kotak yang tepat. Di setiap kotak tertulis ukiran berikut:
- Kotak 1 dan Kotak 2 tertulis: "Kotak tidak berisi apa-apa".
- Kotak 3: "Koin emas berada di kotak 1".  

Permaisuri yang tidak pernah berbohong membantu pemuda 
tersebut dengan mengatakan bahwa hanya ada satu ukiran
yang sesuai dengan isi kotak, dan dua sisanya adalah palsu.
Kotak manakah yang harus dipilih oleh pemuda tersebut?

### Answer
Misalkan tiga proposisi sebagai berikut: 
- $p$ = kotak 1 berisi koin emas
- $q$ = kotak 2 berisi koin emas
- $r$ = kotak 3 berisi koin emas
  
Informasi yang kita dapatkan yaitu:

1. Kotak 1 dan Kotak 2 tertulis: "Kotak tidak berisi apa-apa".

   Kotak 3: "Koin emas berada di kotak 1".  

2. Dua kotak diantara tiga kotak tidak berisikan apa-apa 

$( p \wedge \neg q \wedge \neg r )$ $\vee$ $( \neg p \wedge \neg q \wedge r )$ $\vee$ $( \neg p \wedge q \wedge \neg r )$
   
3. Hanya ada satu ukiran yang benar, dua diantaranya harus salah

Berdasarkan soal kita memiliki tiga kemungkinan. Kita akan uji masing-masing kemungkinan.

Kemungkinan pertama:
Jika $p$ benar $\Rightarrow$ maka $q$ dan $r$ bernilai salah

$( p \wedge \neg q \wedge \neg r )$ =$(T \wedge F \wedge F  )$ = $F$

pada kemungkinan pertama, kita mendapatkan dua ukiran yang sesuai, sehingga kemungkinan pertama bahwa $p$ benar adalah tidak tepat

Kemungkinan kedua:
Jika $q$ benar $\Rightarrow$ maka $p$ dan $r$ bernilai salah

$( \neg p \wedge q \wedge \neg r )$ = $(F \wedge T \wedge F  )$ = $F$

kemungkinan dua sesuai dengan aturan bahwa hanya satu ukiran yang sesuai.

Kemungkinan ketiga: 
Jika $r$ benar $\Rightarrow$ maka $p$ dan $q$ bernilai salah

$( \neg p \wedge \neg q \wedge r )$ = $(F \wedge F \wedge T )$ = $F$

kemungkinan tiga sesuai dengan informasi satu,yang dimana kotak 1 dan 2 tidak berisikan apa-apa. Akan tetapi, ada lebih dari satu ukiran yang sesuai dengan isi kotak, maka hal ini bertentangan dengan pernyataan Permaisuri. jadi kemungkinan 3 tidak tepat.

Karena hanya ada satu ukiran yang sesuai, dan mengingat bahwa Permaisuri tidak pernah berbohong, kita bisa menyimpulkan bahwa kemungkinan 2 adalah yang paling tepat yang dimana kotak 2 berisi koin emas.