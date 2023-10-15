# Assignment 01
**Group members**
- Risky Nur Fatimah Bahar (10231084) (Problem 1)
- Muhammad Novri Aziztra (10231066) (Problem 2)
- Desnita Dwi Putri (10231030) (Problem 3)
- Amalia Tiara Rezfani (10231012) (Problem 4)
- Jonathan Joseph Yudita Tampubolon (10231048) (Problem 5)
  
  
## Problem 1
Manakah pernyataan berikut yang merupakan proposisi?
Berikan juga alasannya
1. Jangan keluar dari ruangan kelas!
2. Berapa kali mahasiswa harus mengikuti kelas Matematika
  diskrit?
3. $3 + y = 14$ 
4. $34 \equiv 1 \quad (\text{mod } 11)$
5. Anita dan Bayu saling berteman.

:bulb: **Petunjuk**: Silahkan dilihat makna operasi modulo
di sub-poin (4) di [Modular Arithmetic](https://en.wikipedia.org/wiki/Modular_arithmetic)

### Answer

1. Bukan merupakan proposisi, karena pernyataan tersebut merupakan kalimat perintah. Kalimat perintah tidak memiliki nilai benar atau salah, sehingga tidak bisa disebut sebagai proposisi.
2. Bukan merupakan proposisi, karena pernyataan tersebut merupakan kalimat tanya. Kalimat tanya tidak memiliki nilai benar atau salah, sehingga tidak bisa disebut sebagai proposisi.
3. Bukan merupakan proposisi, karena variable y tidak diketahui sehingga tidak ada penyelesaian yang artinya tidak memiliki nilai benar ataupun salah. Jadi tidak bisa disebut sebagai proposisi.
4. Merupakan proposisi, karena 34 dan 1 jika dibagi 11 sisa baginya sama-sama 1 sehingga pernyataan tersebut memliki nilai kebenaran.
5. Merupakan proposisi, karena kalimat tersebut memiliki nilai kebenaran.
   
_Source : https://mathcyber1997.com/materi-soal-dan-pembahasan-kongruensi-modulo/_

## Problem 2
Di dalam kuliah disinggung terkait operator
logika disjungsi ekslusif (_exclusive or_), yang disimbolkan $\oplus$.
Susunlah tabel kebenarannya dan berikan dua contoh
proposisi yang mewakili disjungsi ekslusif tersebut.


### Answer

#### Tabel Kebenaran exclusive or ($\oplus$)

| $p$ | $q$ | $p$ $\oplus$ $q$ |
|-----|-----|------------------|
|  T  |  T  |  F  |
|  T  |  F  |  T  |
|  F  |  T  |  T  |
|  F  |  F  |  F  |


#### Contoh Proposisi
1. $p$ = Eros memilih masuk ke prodi Informatika
   
   $q$ = Eros memilih masuk ke prodi Sistem Informasi

   $p$ $\oplus$ $q$ = Eros memilih masuk ke prodi Informatika atau Sistem Informasi

2. $p$ = Angka 3 merupakan bilangan ganjil
   
   $q$ = Angka 3 merupakan bilangan genap
   
   $p$ $\oplus$ $q$ = Angka 3 merupakan bilangan ganjil atau genap

 _Source: https://www.kompas.com/skola/read/2022/06/08/125201469/disjungsi-inklusif-dan-disjungsi-eksklusif-pengertian-dan-contohnya#google_vignette_


## Problem 3
Susunlah tabel kebenaran untuk proposisi majemuk berikut:
1. $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$
2. $((p \leftrightarrow \neg q) \oplus r) \vee r$


### Answer
1. $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$
   
|$p$ | $q$ | $\neg p$ | $\neg q$| $\neg \neg q$ |$\neg p \wedge q$ | $\neg \neg q \rightarrow p$ | $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$ |
|---|---|---|---|---|---|---|---|
| T | T | F | F | T | F | T | T |
| T | F | F | T | F | F | T | T |
| F | T | T | F | T | T | F | F |
| F | F | T | T | F | F | T | T |

2. $((p \leftrightarrow \neg q) \oplus r) \vee r$

   
|$p$ | $q$ | $r$ | $\neg q$ | $p \leftrightarrow \neg q$ | $(p \leftrightarrow \neg q) \oplus r$ | $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$ |
|---|---|---|---|---|---|---|
| T | T | T | F | F | T | T |
| T | T | F | F | F | F | F |
| T | F | T | T | T | F | T |
| T | F | F | T | T | T | T |
| F | T | T | F | T | F | T |
| F | T | F | F | T | T | T |
| F | F | T | T | F | T | T |
| F | F | F | T | F | F | F |

_Source:  https://www.ketutrare.com/2013/05/jenis-jenis-gerbang-logika-yang.html_

## Problem 4
Tentukan konvers, kontrapositive, dan invers dari
pernyataan kondisional berikut
1. Jika hari ini hujan, maka saya tidak akan datang ke
   kuliah matematika diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika
   hari kemarin saya lupa untuk belajar.


### Answer 
1. Pernyataan Asli $(p \rightarrow q)$
$p$: Hari ini hujan.
$q$: Saya tidak akan datang ke kuliah matematika diskrit.
Pernyataan: Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika diskrit.

Konvers $(q \rightarrow p)$
Jika saya tidak datang ke kuliah matematika diskrit, maka hari ini hujan.

Kontrapositive $(\neg q \rightarrow \neg p):$
Jika saya datang ke kuliah matematika diskrit, maka hari ini tidak hujan.

Invers $(\neg p \rightarrow \neg q):$
Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit.

Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.

2. Pernyataan Asli $(q \rightarrow p):$
$p$: Saya akan belajar hingga jam dua dini hari.
$q$: Hari kemarin saya lupa untuk belajar.
Pernyataan: Jika hari kemarin saya lupa untuk belajar, maka saya akan belajar hingga jam dua dini hari.

Konvers $(p \rightarrow q):$
Jika saya akan belajar hingga jam dua dini hari, maka hari kemarin saya lupa untuk belajar.

Kontrapositive $(\neg q \rightarrow \neg p):$
Jika hari kemarin saya tidak lupa untuk belajar, maka saya tidak akan belajar hingga jam dua dini hari.

Invers $(\neg p \rightarrow \neg q):$
Jika saya tidak belajar hingga jam dua dini hari, maka hari kemarin saya tidak lupa untuk belajar.

Pernyataan 1:

$p$: Hari ini hujan.

$q$: Saya tidak akan datang ke kuliah matematika diskrit.

Tabel Kebenaran Pernyataan 1:

|$p$ | $q$ | $p \rightarrow  q$  |$\neg q$ $\rightarrow$ $\neg$ $p$|$\neg$ $p$ $\rightarrow$ $\neg$ $q$|
|--|---|---|----|----|
|T | T | T  |T  |T   |
|T | F | F  |T  |F   |
|F | T | T  |F  |T   |
|F | F | F  |T  |T   |

Pernyataan 2:

$p$: Saya akan belajar hingga jam dua dini hari.


$q$: Hari kemarin saya lupa untuk belajar.


Tabel kebenaran pernyataan 2 :
|$p$ | $q$ | $q \rightarrow p$  | $p \rightarrow q$ | $\neg p \rightarrow \neg q$ | $\neg q \rightarrow \neg p$ |
|--|---|----|----|---|---|
|T | T | T  | T  |T  |T  |
|T | F | T  | F  |F  |T  |
|F | T | F  | T  |T  |F  |
|F | F | T  | F  |T  |T  |

_Source : https://www.ruangguru.com/blog/mengulik-materi-logika-matematika_

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
Misal 3 proposisi P,Q,R

* Kotak 1 (P): "Kotak tidak berisi apa-apa"
* Kotak 2 (Q): "Kotak tidak berisi apa-apa"
* Kotak 3 (R): "Koin emas berada di kotak 1"
  
Jadi hanya ada 1 pernyataan yang benar,sisanya salah

|$P$ | $Q$ | $R$ |
|--|---|----|
|F | F | F  | 
|F | T | F  | 
|T | F | T  | 
|T | T | F  |

* P=0, Q=0: Ini berarti kedua kotak 1 dan kotak 2 kosong. Tidak ada cara pernyataan R bisa benar karena koin emas ada di kotak 1. Jadi, R harus salah (0).

* P=0, Q=1: Ini berarti kotak 1 kosong, tetapi kotak 2 berisi koin emas (yang bertentangan dengan informasi yang diberikan). Oleh karena itu, tidak ada cara R bisa benar. R harus salah (0).

* P=1, Q=0: Ini berarti kotak 1 berisi koin emas, yang sesuai dengan pernyataan R. Jadi, R bisa benar (1).

* P=1, Q=1: Ini berarti kedua kotak 1 dan kotak 2 berisi koin emas (yang bertentangan dengan informasi yang diberikan). Oleh karena itu, tidak ada cara R bisa benar. R harus salah (0).

_Source : https://en.wikipedia.org/wiki/Modular_arithmetic_