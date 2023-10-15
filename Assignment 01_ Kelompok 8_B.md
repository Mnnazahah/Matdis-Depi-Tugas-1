# Assignment 01

**Anggota kelompok**
- Anjas Geofany Diamare_10231016  (Soal 1)
- Dzakwan Fatih Fadhilah_10231034  (Soal 2)
- Meiske Handayani_10231052  (Soal 3)
- Nilam Ayu NandaStari Romdoni_10231070  (Soal 4)
- Tiya Mitra Ayu Purwanti_10231088  (Soal 5)

## Soal 1
Manakah pernyataan berikut yang merupakan proposisi? Berikan juga alasannya

1. Jangan keluar dari ruangan kelas!
2. Berapa kali mahasiswa harus mengikuti kelas Matematika diskrit?
3. $3 + y = 14$
4. $34 \equiv 1 \quad (\text{mod } 11)$
5. Anita dan Bayu saling berteman

### Jawaban
1. Bukan termasuk proposisi, karena kalimat ini lebih ke kalimat perintah, sehingga tidak dapat dilihat nilai benar atau salahnya.
2. Bukan termasuk proposisi, karena kalimat ini lebih ke kalimat pertanyaan terbuka, dan tidak memiliki nilai kebenaran yang jelas benar atau salah.
3. Bukan termasuk proposisi , karena kita tidak mengetahui nilai y ,sehingga tidak memiliki nilai benar atau salah.
4. Termasuk kalimat proposisi , karena dalam operasi modulo 34 = 1 (mod 11) atau bisa ditulis 34 mod 11 = 1 merupakan perhitungan yang benar. Sehingga kalimat ini merupakan kalimat proposisi dengan nilai benar.
5. Termasuk kalimat proposisi , karena kalimat ini memiliki nilai benar atau salah. Jika Anita dan Bayu benar-benar saling berteman maka kalimat ini merupakan kalimat proposisi yang benar. Dan jika Anita dan Bayu tidak benar-benar berteman maka kalimat ini merupakan kalimat proposisi yang salah.


## Soal 2
Di dalam kuliah disinggung terkait operator logika disjungsi ekslusif (_exclusive or_), yang disimbolkan $\oplus$. Susunlah tabel kebenarannya dan berikan dua contoh proposisi yang mewakili disjungsi ekslusif tersebut.

### Jawaban 
$$-{Operator Exclusive Or}-$$

Operator biner _exclusive-or_ "$\oplus$" (_XOR_) menggabungkan dua proposisi untuk membentuk logika "exclusive or"-nya.

Diberikan 2 buah proposisi $p$ dan $q$, disimbolkan dengan $p$ $\oplus$ $q$ berarti $p$ benar, atau $q$ benar tapi **tidak dua - duanya benar!**
Disebut _exclusive or_, karena tidak memungkinkan $p$ dan $q$ keduanya benar.

**_Tabel Kebenaran Exclusive OR_**

|$p$ | $q$ | $p \oplus q$  |
|---|---|----|
| F | F | F  | 
| F | T | T  | 
| T | F | T  | 
| T | T | F  | 

Contoh Proposisinya :

1. $p$ = "Saya menang lomba sepeda."
   
   $q$ = "Saya akan berhenti bersepeda"

   $p \oplus q$ = "Saya menang lomba sepeda atau saya akan berhenti bersepeda (**tapi tidak dua - duanya benar!**)".

2. $p$ = "Kamu membeli tiket pesawat"

   $q$ = "Kamu akan pergi"
   
   $p \oplus q$ = "Kamu membeli tiket pesawat atau kamu akan pergi (**tapi tidak dua - duanya benar!**)".

## Soal 3
Susunlah tabel kebenaran untuk proposisi majemuk berikut:
1. $(\neg p \wedge q) \rightarrow (\neg \neg q \rightarrow p)$
2. $((p \leftrightarrow \neg q) \oplus r) \vee r$

### Jawaban
tabel kebenaran dari ($\neg$ p $\wedge$ q) $\rightarrow$ ($\neg$ $\neg$ q $\rightarrow$ p)

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

## Soal 4
Tentukan konvers, kontrapositive, dan invers dari pernyataan kondisional berikut

1. Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.
    
### Jawaban
1. Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika diskrit.
    - Konvers $( q \rightarrow p )$ : Jika saya tidak akan datang ke kuliah matematika diskrit, maka hari ini pasti hujan.
    - Kontrapositive $(\neg q \rightarrow \neg p)$ : Jika saya datang ke kuliah matematika diskrit, maka hari ini tidak hujan.
    - Invers $(\neg p \rightarrow \neg q)$ : Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.
    - Konvers $( q \rightarrow p )$ : Jika hari kemarin saya lupa untuk belajar, maka saya akan belajar hingga jam dua dini hari.
    - Kontrapositive $(\neg q \rightarrow \neg p)$ : Jika saya tidak belajar hingga jam dua dini hari, maka saya tidak lupa belajar hari kemarin.
    - Invers $(\neg p \rightarrow \neg q)$ : Jika hari kemarin saya tidak lupa belajar, maka saya tidak akan belajar hingga jam dua dini hari.

Tabel Kebenaran 1
|$p$ | $q$ | $\neg$ p | $\neg$ q | $q \rightarrow p$  | $(\neg q \rightarrow \neg p)$ | $(\neg p \rightarrow \neg q)$ |
|--|---|----|-----|------|-------|--------|
|T | T |  F |  F  |  T   |   T   |    T   |
|T | F |  F |  T  |  T   |   F   |    T  |
|F | T |  T |  F  |  F   |   T   |    F   |
|F | F |  T |  T  |  T   |   T   |    T   |

Tabel Kebenaran 2
|$p$ | $q$ | $\neg$ p | $\neg$ q | $q \rightarrow p$  | $(\neg q \rightarrow \neg p)$ | $(\neg p \rightarrow \neg q)$ |
|--|---|----|-----|------|-------|--------|
|T | T |  F |  F  |  T   |   T   |    T   |
|T | F |  F |  T  |  T   |   F   |    T  |
|F | T |  T |  F  |  F   |   T   |    F   |
|F | F |  T |  T  |  T   |   T   |    T   |

## Soal 5
Sebagai imbalan karena menyelamatkan putri seorang raja, seorang pemuda diberi kesempatan untuk memperoleh sejumlah koin emas yang tersimpan di salah satu tiga kotak yang ditawarkan oleh raja. Dua kotak diantara tiga kotak merupakan kotak kosong. Agar pemuda tersebut memperoleh koin emas, dia harus memilih kotak yang tepat. Di setiap kotak tertulis ukiran berikut:
- Kotak 1 dan Kotak 2 tertulis: "Kotak tidak berisi apa-apa".
- Kotak 3: "Koin emas berada di kotak 1".  

Permaisuri yang tidak pernah berbohong membantu pemuda  tersebut dengan mengatakan bahwa hanya ada satu ukiran yang sesuai dengan isi kotak, dan dua sisanya adalah palsu. Kotak manakah yang harus dipilih oleh pemuda tersebut?

### Jawaban
Jika kotak 1 dan kotak 2 tertulis: "Kotak tidak berisi apa-apa".
dan Kotak 3: "Koin emas berada di kotak 1".

misal :
- p adalah proposisi kotak 1 adalah kotak tidak berisi apa-apa
- q adalah proposisi 3 adalah kotak berisi koin emas
- $\neg$ p adalah kotak 1 dan 2 adalah kotak berisi koin emas
- $\neg$ q adalah kotak berisi koin emas

Kemungkinan pertama

Kotak 1 dan 2 adalah tidak berisi koin
1. Setara denagn p benar
2. Kotak 1 dan 2 benar : 
    - "kotak tidak berisi apa-apa"
    - q benar
3. Kotak 3 benar : "koin emas berada di kotak 1"

karena kontradiksi, asumsi diawal diawal permaisuri tidak pernah berbohong dan berkata "hanya ada satu ukiran yang sesuai dengan isi kotak, dan sisanya adalah palsu.

Kemungkinan kedua

Kotak 1 dan 2 berisi koin

1. Kotak 1 dan 2 salah 
    - "Kotak berisi koin emas"
    - q adalah salah 
    - Kotak 1 dan 2 berisi koin emas
2. kotak 3 salah 
    - Kotak 1 berisi koin emas

#### Kesimpulan :

- Kotak 1 berisi koin emas
- Kotak 2 berisi koin emas
- Kotak 3 benar koin emas ada dikotak 1