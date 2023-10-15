# Assignment 01

**Group members**
- Ahmad Daffa Alfattah (10231008) (Problem 1)
- Rayhan Iqbal (10231080) (Problem 2)
- Indah Nur Fortuna (10231044) (Problem 3)
- Cintya Widhi Astuti (10231026) (Problem 4)
- Muhammad Dani (10231062) (Problem 5)

## Problem 1
Manakah pernyataan berikut yang merupakan proposisi?
Berikan juga alasannya
1. Jangan keluar dari ruangan kelas!
2. Berapa kali mahasiswa harus mengikuti kelas Matematika
  diskrit?
3. $3 + y = 14$ 
4. $34 \equiv 1 \quad (\text{mod } 11)$
5. Anita dan Bayu saling berteman.

**Jawaban**

1.Bagian ini bukanlah proposisi sebab bagian ini  lebih merupakan suatu perintah atau instruksi daripada pernyataan yang memiliki kebenaran yang dapat dinilai.

2.Bagian ini bukanlah Proposisi karena proposisi memiliki nilai kebenaran atau salah tetapi bagian ini adalah kalimat pertanyaan

3.Bagian ini adalah proposisi karena $y = 11$ jadi Bagian ini adalah proposisi yang memiliki nilai kebenaran

4.Dalam bagian ini, $"34 = 1 (mod 11)"$ berarti bahwa 34 dan 1 memiliki sisa yang sama ketika dibagi oleh 11.

Dengan demikian, pernyataan $ "34 = 1 (mod 11)"$ adalah proposisi yang memiliki nilai kebenaran salah.

5.Pernyataan "Anita dan Bayu saling berteman." adalah sebuah proposisi. Alasannya adalah pernyataan ini memiliki nilai kebenaran yang dapat dinilai. Jika Anita dan Bayu adalah teman satu sama lain, maka pernyataan ini benar. Jika salah satu di antara mereka tidak menganggap yang lain sebagai teman, maka pernyataan ini salah.

## Problem 2
Di dalam kuliah disinggung terkait operator
logika disjungsi ekslusif (_exclusive or_), yang disimbolkan $\oplus$.
Susunlah tabel kebenarannya dan berikan dua contoh
proposisi yang mewakili disjungsi ekslusif tersebut.

## Answer

Operator logika disjungsi eksklusif (exclusive or) biasanya disimbolkan dengan $\oplus$. Tabel kebenarannya adalah sebagai berikut:

|$p$ | $q$ | $p \oplus q$  |
|---|---|---------|
| T | T |   F     |
| T | F |   T     |
| F | T |   T     |
| F | F |   F     |

Contoh proposisi yang mewakili operasi $\oplus$ adalah:

1. Pernyataan 1: "Hari ini hujan" (P).
   Pernyataan 2: "Saya membawa payung" (Q).
   Pernyataan ini akan benar jika hari ini hujan dan saya membawa payung atau jika hari ini tidak hujan dan saya tidak membawa payung.

2. Pernyataan 1: "Angka yang saya pilih adalah ganjil" (P).
   Pernyataan 2: "Angka yang saya pilih adalah lebih dari 10" (Q).
   Pernyataan ini akan benar jika angka yang saya pilih adalah ganjil dan lebih dari 10, atau jika angka yang saya pilih bukan ganjil dan tidak lebih dari 10.


## Problem 3
Susunlah tabel kebenaran untuk proposisi majemuk berikut:
1. $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$
2. $((p \leftrightarrow \neg q) \oplus r) \vee r$


### Answer
1. $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$

|$p$ | $q$ | $ \neg p$ | $\neg q$| $\neg \neg q$ |$\neg p \wedge q$ | $\neg \neg q \rightarrow p$ | $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$ |
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

## Problem 4

Tentukan konvers, kontrapositive, dan invers dari pernyataan kondisional berikut

1. Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika   diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.

### Jawaban
1. Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika   diskrit.
   
   Konvers: Jika saya tidak akan datang ke kuliah matematika diskrit, maka hari ini pasti hujan.

   Kontrapositif: Jika saya datang ke kuliah matematika diskrit, maka tidak mungkin hari ini hujan.

   Invers: Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit
2. Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.
   
   Konvers: Jika hari kemarin saya lupa untuk belajar, maka saya akan belajar hingga jam dua dini hari.

   Kontrapositif: Jika saya tidak belajar hingga jam dua dini hari, maka saya tidak lupa belajar hari kemarin.

   Invers: jika saya hari kemarin saya tidak lupa belajar, maka saya tidak akan belajar hingga jam dua dini hari.


Tabel kebenaran soal 1
|$p$ | $q$ | $q \rightarrow p$| $\neg q \rightarrow \rightarrow p$ | $\neg p \rightarrow \rightarrow q$  |
|--|---|----|-----|------|
|T | T | T  |  T  |  T   |
|T | F | T  |  F  |  T   |
|F | T | F  |  T  |  F   |
|F | F | T  |  T  |  T   |

Tabel kebenaran soal 2                                                                                                                                                       
|$p$ | $q$ | $q \rightarrow p$| $\neg q \rightarrow \rightarrow p$ | $\neg p \rightarrow \rightarrow q$  |
|--|---|----|-----|------|
|T | T | T  | T   |  T   |
|T | F | T  | F   |  T   |
|F | T | F  | T   |  F   |
|F | F | T  | T   |  T   |

## Problem 5

Sebagai imbalan karena menyelamatkan putri seorang raja, seorang pemuda diberi kesempatan untuk memperoleh sejumlah koin emas yang tersimpan di salah satu tiga kotak yang ditawarkan oleh raja. Dua kotak diantara tiga kotak merupakan kotak kosong. Agar pemuda tersebut memperoleh koin emas, dia harus memilih kotak yang tepat. Di setiap kotak tertulis ukiran berikut:

- Kotak 1 dan Kotak 2 tertulis: "Kotak tidak berisi apa-apa".
- Kotak 3: "Koin emas berada di kotak 1".

Permaisuri yang tidak pernah berbohong membantu pemuda tersebut dengan mengatakan bahwa hanya ada satu ukiran yang sesuai dengan isi kotak, dan dua sisanya adalah palsu. Kotak manakah yang harus dipilih oleh pemuda tersebut?

### Answer

Diketahui informasi yang didapat adalah :
   - **Kotak 1** Tertulis "Kotak tidak berisi apa apa"
   - **Kotak 2** Tertulis "Kotak tidak berisi apa apa"
   - **Kotak 3** Tertulis "Koin Emas berada di *kotak 1*"
   - permaisuri tidak pernah berbohong
   - "Hanya ada 1 ukiran yang sesuai dengan isi kotak"

Proposi dari informasi tersebut bisa diartikan sebagai berikut:
   - **$p$** = (Kotak 1, Kotak 2, Kotak 3)
   - **$q$** = Permaisuri tidak pernah berbohong ( "Hanya ada 1 ukiran yang sesuai dengan isi kotak." )

Dalam proposi dari *$p$* dan *$q$* dapat dinyatakan sebagai berikut:
***Noted*** : "Hanya ada 1 ukiran yang sesuai dengan isi kotak

   - **Kotak 1** Tertulis "Kotak tidak berisi apa apa"
   *False*, Karena jika kotak 1 ssesuai dengan isi kotak, maka benar kotak tersebut tidak berisi apa apa.
   - **Kotak 2** Tertulis "Kotak tidak berisi apa apa"
   *False*, Karena jika kotak 2 ssesuai dengan isi kotak, maka benar kotak tersebut tidak berisi apa apa.
   - **Kotak 3** Tertulis "Koin Emas berada di *kotak 1*"
   *False*, Karena jika kotak 3 sesuai dengan yang tertulis di kotak, maka kotak 3 tidak berisi apa apa,

Kemungkinan terbesar terdapat pada Kotak 1 tetapi, kotak 1 pun sendiri tertulis "kotak tidak berisi apa apa" maka itu mengatakan kalo kotak 1 *False*

$(p \vee q)$,
Kesimpulan, Permaisuri Benar, Semua kotak kosong = tidak ada emas.