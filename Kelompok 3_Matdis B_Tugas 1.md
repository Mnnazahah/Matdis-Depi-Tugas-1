# Assignment 01

**Group members**
- Ilham Ahmad Fahriji (10231042) (Problem #1)
- Aditya Laksamana P Butar Butar (10231006) (Problem #2)
- Muhammad Ayash Az Dzikri (10231060) (Problem #3)
- Ranaya Chintya Mahitsa (10231078) (Problem #4)
- Cantika Ade Qutnindra Maharani (10231024) (Problem #5)

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
1. Jangan Keluar Dari Ruangan Kelas !
    untuk ini bukan proposisi karena termasuk didalam sebuah kalimat perintah
2. Berapa kali mahasiswa harus mengikuti Kelas Matematika Discrete ?
    untuk ini bukan proposisi karena termasuk didalam sebuah kalimat pertanyaan
3. $3 + y =14$ 
    Karena Nilai kebenaran dari pernyataan tersebut bergantung pada Y, tapi nilainya belum ditentukan
4. $34 \equiv 1 \quad (\text{mod }11)$
    ini termasuk kedalam sebuah proposisi karena benar nilai modulus 34 dari 11 adalah 1
5. Anita dan Bayu saling berteman.
    ini adalah sebuah proposisi karena ada nilai kebenarannya atau bisa juga salah
## Problem 2
Di dalam kuliah disinggung terkait operator
logika disjungsi ekslusif (_exclusive or_), yang disimbolkan $\oplus$.
Susunlah tabel kebenarannya dan berikan dua contoh
proposisi yang mewakili disjungsi ekslusif tersebut.


### Answer
Ini adalah jawaban dari Problem 2 

Pertama diminta untuk menyusun tabel kebenaran logika disjungsi ekslusif (exclusive or) disimbolkan dengan tanda $\oplus$.

|$p$ | $q$ | $p \oplus r$ |
|--|---|----|
|T | T | F  | 
|T | F | T  | 
|F | T | T  | 
|F | F | F  | 

Yang kedua diminta untuk memberikan dua contoh proposisi yang mewakili disjungsi ekslusif tersebut.

1. Contoh yang pertama  : Kelompok 3 akan mengadakan acara dicafe atau direstoran besok sore
2. Contoh yang kedua : Ilham hanya dapat memilih program studi Teknik Sipil atau Sistem Informasi saat tes UTBK

## Problem 3
Susunlah tabel kebenaran untuk proposisi majemuk berikut:
1. $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$
2. $((p \leftrightarrow \neg q) \oplus r) \vee r$


### Answer
tabel kebenaran proposisi $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$ $((p \leftrightarrow \neg q) \oplus r) \vee r$:

|$p$|$q$|$r$|$\neg p$|$\neg \neg q$|$\neg p \wedge q$|$\neg \neg q \rightarrow p$|$(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$|$p \leftrightarrow \neg q$|$((p \leftrightarrow \neg q) \oplus r)$|$((p \leftrightarrow \neg q) \oplus r) \vee r$|
|---|---|---|---|---|---|---|---|---|---|---|
| T | T | T | F | F | F | T | T | F | T | T |
| T | T | F | F | F | F | T | T | F | F | F |
| T | F | T | F | T | F | T | T | T | T | T |
| T | F | F | F | T | F | T | T | T | F | F |
| F | T | T | T | F | T | F | F | T | F | T |
| F | T | F | T | F | F | T | T | F | T | T |
| F | F | T | T | T | F | T | T | F | T | T |
| F | F | F | T | T | F | T | T | T | F | F |
## Problem 4
Tentukan konvers, kontrapositive, dan invers dari
pernyataan kondisional berikut
1. Jika hari ini hujan, maka saya tidak akan datang ke
   kuliah matematika diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika
   hari kemarin saya lupa untuk belajar.


### Answer 
A. p = Jika hari ini hujan.
   q = maka saya tidak akan datang ke kuliah matematika diskrit.

- konvers $( q \rightarrow p )$ = Jika saya tidak akan datang ke kuliah matematika diskrit, maka hari ini hujan.
- kontrapositive $(\neg q \rightarrow \neg p)$ = jika saya datang ke kuliah matematika diskrit, maka hari ini tidak hujan.
- invers $(\neg p \rightarrow \neg q)$ = Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit.

B. p = Saya akan belajar hingga jam dua dini hari
   q = jika hari kemarin saya lupa untuk belajar.

 - konvers $( q \rightarrow p )$ = Jika hari kemarin saya lupa untuk belajar, maka saya akan belajar hingga jam dua dini hari.
- kontrapositive $(\neg q \rightarrow \neg p)$ = Jika hari kemarin saya tidak lupa untuk belajar, maka saya tidak akan belajar hingga jam dua dini hari.
- invers $(\neg p \rightarrow \neg q)$ = Saya tidak akan belajar hingga jam dua dini hari, jika hari kemarin saya tidak lupa untuk belajar.


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

Dari soal tersebut dapat kita pastikan akan terdapat 3 kemungkinan yang dapat dicoba pembuktiannya.

Anggap saja pernyataan mengenai kotak 1,2 dan 3 adalah pernyataan $A$ dan pernyataan $B$

Jika pernyataan $A$ "Kotak 1 dan 2 adalah kotak kosong" dan pernyataan $B$ "kotak 1 berisikan koin emas" maka 
- $`p = `$ \"$`A`$ Kotak 1 dan 2 adalah kotak kosong\" 
 - $`q = `$ \"$`B`$ kotak 1 dan 2 adalah kotak kosong \"
  - $` \neg p = `$ \"$`A`$ kotak 1 berisikan koin emas\" 
 - $` \neg q = `$ \"$`B`$ kotak 1 berisikan koin emas\" 


*kemungkinan pertama* 

$A$ kotak 1 dan 2 adalah kotak kosong

setara dengan $\rightarrow$ - $`p$ jujur

$\rightarrow$ $A$ berisikan pernyataan jujur $\rightarrow$ Kotak 1 dan 2 adalah kotak kosong $\rightarrow$ -$`q$ jujur

$\rightarrow$ $B$ berisikan pernyataan jujur $\rightarrow$ Kotak 1 berisikan koin emas, *Padahal* kotak satu merupakan kotak kosong.

Dikarenakan adanya kontradiksi asumsi di awal $A$ adalah "kotak 1 dan 2 merupakan kotak kosong" tidak benar  atau -$`p$ salah

*Kemungkinan kedua*

$B$ kotak 1 berisikan koin emas

setara dengan $\rightarrow$ -$ ` \neg p $

$\rightarrow$ $A$ berkata bohong $\rightarrow$ Kotak 1 dan 2 bukan kotak kosong $\rightarrow$ -$`q$ adalah salah

$\rightarrow$ $B$ berkata bohong $\rightarrow$ kotak 1 tidak berisikan koin emas. 

kemungkinan dua dinyatakan salah karena terdapat kontradiksi asumsi yang mana "kotak 1 tidak berisikan emas" padahal pada peryataan pertama kotak 1 dan 2 bukan kotak kosong.

*Kemungkinan tiga*

$A$ kotak 1 dan 2 bukan kotak kosong

$\rightarrow$ $A$ berkata bohong $\rightarrow$  kotak 1 dan 2 bukan kotak kosong  $\rightarrow$ -$`q$ adalah salah

$\rightarrow$ $B$ berkata bohong $\rightarrow$ kotak 1 tidak berisikan koin emas $\rightarrow$ - $`\neg q$ adalah salah 

Pernyataan dianggap tautologi dikarenakan kedua pernyataan bernilai salah, dan kotak dua merupakan kotak yang berisikan koin emas.