# Assignment 1

**Anggota Kelompok**
- Raditya Yudianto NIM 10231076   ( Problem 1-5 )
- Ade Ayu Kholifah Putri NIM 10231004 ( Problem 1,2,5)
- Az-Zahra Atikah Nurhaliza NIM 10231022 ( Problem 1,3,5)
- Muhammad Ariel Rayhan NIM 10231058 ( Problem 1,3,5)
- Hita Higueta Pancaro NIM 10231040 (Problem 1,4,5)
- Zahwa Hanna Dwi Putri NIM 10231092 (Problem 5)




## Problem 1
Manakah pernyataan berikut yang merupakan proposisi? Berikan juga alasannya

1. Jangan keluar dari ruangan kelas!
2. Berapa kali mahasiswa harus mengikuti kelas Matematika diskrit?
3. 3 + y = 14
4. 34 = 1 (mod 11)
5. Anita dan Bayu saling berteman.
   
## Answer 1
1. bukan proposisi karena itu merupakan kalimat perintah dan tidak dapat diketahui kebenaran ataupun kesalahannya
2. bukan proposisi karena pertanyaan ini tidak bisa dijawab dengan pasti (jawaban dapat berupa 1x,2x,3x,etc)
3. bukan termasuk proposisi karena y harus diketahui sebelum pernyataan itu dapat diketahui kebenarannya
4. termasuk proposisi karena 34 = 1 (mod 11) bernilai _True_ dikarenakan jika 34 dibagi dengan 11 akan bersisa 1
5. termasuk proposisi karena pernyataan tersebut bisa bernilai _True_ or _False_
   
## Problem 2
Di dalam kuliah disinggung terkait operator logika disjungsi ekslusif (exclusive or), yang disimbolkan $\oplus$
. Susunlah tabel kebenarannya dan berikan dua contoh proposisi yang mewakili disjungsi ekslusif tersebut.

## Answer 2
| p | q | Hasil   |
|---|---|---------|
| F | F | False   |
| F | T | True    |
| T | F | True    |
| T | T | False   |

Untuk contoh proposisinya ialah "saya ingin membeli mobil berwarna merah atau mobil berwarna biru, tetapi tidak keduanya sekaligus" dan juga "Restoran yang rame biasanya memiliki harga yang murah atau makanan yang benar benar enak, namun bukan keduanya"


## Problem 3
Susunlah Tabel kebenaran untuk proposisi majemuk berikut

($\neg$ p $\wedge$ q) $\rightarrow$ ($\neg$ $\neg$ q $\rightarrow$ p)

((p $\leftrightarrow$ $\neg$ q) $\oplus$ r) $\vee$ r

## Answer
tabel kebenaran dari ($\neg$p $\wedge$ q) $\rightarrow$ ($\neg$ $\neg$ q $\rightarrow$ p)

| p  | q  | $\neg$ p |$\neg$ p $\wedge$ q  |$\neg$ $\neg$ q $\rightarrow$ p| $\neg$ p $\wedge$ q $\rightarrow$($\neg$ $\neg$ q $\rightarrow$ p) |
|----|----|---------|------------------|---------|--------------------|
| T  | T  |     F   |  F               | T       | T                  |
| T  | F  |     F   |  F               | T       | T                  |
| F  | T  |     T   |  T               | F       | F                  |
| F  | F  |     T   |  F               | T       | T                  |

tabel kebenaran dari $((p \leftrightarrow \neg q) \oplus r) \vee r$

| p | q | r | $\neg$ q | $p \leftrightarrow \neg q$ | $(p \leftrightarrow \neg q) \oplus r$ | $((p \leftrightarrow \neg q) \oplus r) \vee r$ |
|---|---|---|----|-------|------------|---------------------|
| F | F | F | T  |   T   |      F     |         F           |
| F | F | T | T  |   T   |      T     |         T           |
| F | T | F | F  |   F   |      F     |         F           |
| F | T | T | F  |   F   |      T     |         T           |
| T | F | F | T  |   F   |      F     |         F           |
| T | F | T | T  |   F   |      T     |         T           |
| T | T | F | F  |   T   |      T     |         T           |
| T | T | T | F  |   T   |      F     |         T           |


## Problem 4
Tentukan konvers, kontrapositive, dan invers dari pernyataan kondisional berikut

A.  Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika diskrit.

B. Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.
  
## Answer 4
A. Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika diskrit.
- Konvers: Jika saya tidak akan datang ke kuliah matematika diskrit, maka hari ini hujan.
- Kontrapositif: Jika saya akan datang ke kuliah matematika diskrit, maka hari ini tidak hujan.
- Invers: Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit.
  
B. Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.
- Konvers: Jika saya lupa untuk belajar hari kemarin, maka saya akan belajar hingga jam dua dini hari.
- Kontrapositif: Jika saya tidak akan belajar hingga jam dua dini hari, maka saya tidak lupa untuk belajar hari kemarin.
- Invers: Jika saya tidak lupa untuk belajar hari kemarin, maka saya tidak akan belajar hingga jam dua dini hari.

## Problem 5
Sebagai imbalan karena menyelamatkan putri seorang raja, seorang pemuda diberi kesempatan untuk memperoleh sejumlah koin emas yang tersimpan di salah satu tiga kotak yang ditawarkan oleh raja. Dua kotak diantara tiga kotak merupakan kotak kosong. Agar pemuda tersebut memperoleh koin emas, dia harus memilih kotak yang tepat. Di setiap kotak tertulis ukiran berikut:

Kotak 1 dan Kotak 2 tertulis: "Kotak tidak berisi apa-apa".
Kotak 3: "Koin emas berada di kotak 1".
Permaisuri yang tidak pernah berbohong membantu pemuda tersebut dengan mengatakan bahwa hanya ada satu ukiran yang sesuai dengan isi kotak, dan dua sisanya adalah palsu. Kotak manakah yang harus dipilih oleh pemuda tersebut?

## Answer 5
_p_= Kotak 1 benar

_q_= kotak 2 benar

_r_= kotak 3 benar

### Jika kotak 1 Benar / pernyataan _p_, dan kotak lainnya salah
- Kotak 1  = kotak kosong
- kotak 2  = kotak berisi koin emas
- kotak 3  = kotak 1 tidak berisi koin emas

 KESIMPULAN = Kotak 1 & 3 kotak kosong , dan kotak 2 berisi koin emas 

 ### Jika kotak 2 benar / pernyataan _q_, dan kotak lainnya salah
 - kotak 1 = kotak berisi koin emas
 - kotak 2 = kotak kosong
 - kotak 3 = kotak 1 tidak berisi koin emas 
  
  KESIMPULAN = *Kontradiksi* karena pernyataan p dan q berlainan 

 ### Jika Kotak 3 benar / pernyataan _r_, dan kotak lainnya salah 
 - Kotak 1 = kotak berisi koin emas
 - kotak 2 = kotak berisi koin emas
 - kotak 3 = kotak 1 berisi koin emas

 KESIMPULAN = *Kontradiksi* karena hanya boleh ada 1 kotak yang berisi koin emas

 Jadi Menurut Pernyataan _p_ , pemuda tersebut harus memilih kotak 2 karena kotak tersebut berisi koin emas