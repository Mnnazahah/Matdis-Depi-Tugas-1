# Assignment 01

**Anggota kelompok**
- Alfiani Dwiyuniarti (10231010) (no 2)
- David Ramadhani Pangestu (10231028) (no 5)
- Irwan Maulana (10231046) (no 4)
- Muhammad Irvany Saputra (10231064) (no 3)
- Riqqah Khalda Karina (10231082) (no 1)

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
1. bukan proposisi, sebab kalimat tersebut merupakan kalimat perintah dan tidak diketahui nilai benar salahnya.
2. bukan proposisi, sebab kalimat tersebut merupakan kalimat pertanyaan dan tidak diketahui nilai benar salahnya.
3. bukan proposisi, sebab 'y' adalah kalimat variabel(peubah) sehingga tidak bisa ditentukan nilai benar salahnya.
4. proposisi, sebab pernyataan bernilai benar karena 34 - 1 habis dibagi 11.
5. proposisi, sebab anita dan bayu tidak diketahui pasti siapa mereka maka kalimat tersebut bisa bernilai benar atau salah.


## Problem 2
Di dalam kuliah disinggung terkait operator
logika disjungsi ekslusif (_exclusive or_), yang disimbolkan $\oplus$.
Susunlah tabel kebenarannya dan berikan dua contoh
proposisi yang mewakili disjungsi ekslusif tersebut.

### Answer
Operator logika disjungsi eksklusif (exclusive or) biasanya disimbolkan dengan $\oplus$. Tabel kebenarannya adalah sebagai berikut:

|$p$ | $q$ | $p \oplus q$  |
|---|---|---------|
| T | T |   F     |
| T | F |   T     |
| F | T |   T     |
| F | F |   F     |

Contoh proposisi yang mewakili operasi $\oplus$ adalah:
Pernyataan 1: “Saya akan pergi ke pesta atau saya akan pergi ke bioskop, tetapi tidak keduanya.”
Dalam konteks ini, proposisi A mewakili pergi ke pesta, dan proposisi B mewakili pergi ke bioskop. Jika salah satu dari dua proposisi tersebut benar (misalnya, saya memutuskan untuk pergi ke pesta), tetapi tidak keduanya benar (saya tidak pergi ke pesta dan ke bioskop), maka pernyataan tersebut mewakili disjungsi eksklusif.
Pernyataan 2: “Lampu akan menyala jika ada gerakan atau suara, tetapi tidak keduanya.”
Dalam konteks ini, proposisi A mewakili keberadaan gerakan, dan proposisi B mewakili keberadaan suara. Jika ada gerakan di sekitar lampu atau ada suara, tetapi tidak keduanya (misalnya, ada gerakan tetapi tidak ada suara), maka pernyataan tersebut mewakili disjungsi eksklusif.

## Problem 3

Susunlah tabel kebenaran untuk proposii majemuk berikut
1. $(\neg p \wedge q)\rightarrow (\neg\neg q\rightarrow p)$
2. $((p\leftrightarrow\neg q)\oplus r)\vee r$

### Answer

1. **Tabel Kebenaran $(\neg p \wedge q)\rightarrow (\neg\neg q\rightarrow p)$**

|$p$ |$q$ |$\neg p$ |$\neg\neg q$ |$\neg p \wedge q$  |$\neg\neg q\rightarrow p$ |$(\neg p\wedge q)\rightarrow(\neg\neg q\rightarrow P)$ |
|---|---|----|-----|--------|--------|------------|
| T | T |  F |  F  |    T   |   T    |      T     |
| T | F |  F |  T  |    F   |   T    |      T     |
| F | T |  T |  F  |    T   |   T    |      T     | 
| F | F |  T |  T  |    T   |   F    |      F     |  


2. **Tabel Kebenaran $((p\leftrightarrow\neg q)\oplus r)\vee r$**

| $p$ | $q$ | $r$ | $\neg q$ | $p \leftrightarrow \neg q$ | $( p \leftrightarrow \neg q)\oplus r$ | $((p\leftrightarrow\neg q)\oplus r)\vee r$ |
|---|---|---|----|------|---------|-----------------|
| T | T | T | F  |  T   |    F    |        T        |
| T | T | F | F  |  F   |    F    |        F        |
| T | F | T | T  |  T   |    F    |        T        |
| T | F | F | T  |  T   |    T    |        T        |
| F | T | T | F  |  T   |    F    |        T        |
| F | T | F | F  |  T   |    T    |        T        |
| F | F | T | T  |  F   |    T    |        T        |
| F | F | F | T  |  F   |    F    |        F        |

## Problem 4
Tentukan konvers, kontrapositive, dan invers dari
pernyataan kondisional berikut
1. Jika hari ini hujan, maka saya tidak akan datang ke
   kuliah matematika diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika
   hari kemarin saya lupa untuk belajar.


### Answer 
Berikut adalah konvers, kontrapositive, dan invers dari pernyataan kondisional yang diberikan:

1. Pernyataan kondisional: Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika diskrit.
    - Konvers: Jika saya tidak akan datang ke kuliah matematika diskrit, maka hari ini hujan.
    - Kontrapositif: Jika saya akan datang ke kuliah matematika diskrit, maka hari ini tidak hujan.
    - Invers: Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit.

2. Pernyataan kondisional: Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.
    - Konvers: Jika saya lupa untuk belajar, maka saya akan belajar hingga jam dua dini hari.
    - Kontrapositif: Jika saya tidak akan belajar hingga jam dua dini hari, maka saya tidak lupa untuk belajar.
    - Invers: Jika saya tidak lupa untuk belajar, maka saya tidak akan belajar hingga jam dua dini hari.


 # problem 5

Sebagai imbalan karena menyelamatkan putri seorang raja, seorang pemuda diberi kesempatan untuk memperoleh sejumlah koin emas yang tersimpan di salah satu tiga kotak yang ditawarkan oleh raja. Dua kotak diantara tiga kotak merupakan kotak kosong. Agar pemuda tersebut memperoleh koin emas, dia harus memilih kotak yang tepat. Di setiap kotak tertulis ukiran berikut:

    Kotak 1 dan Kotak 2 tertulis: "Kotak tidak berisi apa-apa".
    Kotak 3: "Koin emas berada di kotak 1".

Permaisuri yang tidak pernah berbohong membantu pemuda tersebut dengan mengatakan bahwa hanya ada satu ukiran yang sesuai dengan isi kotak, dan dua sisanya adalah palsu. Kotak manakah yang harus dipilih oleh pemuda tersebut?

## answer

Kotak ke 3 adalah kotak yang harus dipilih pemuda tersebut, karena kotak ke 3 hanya bertulisan "koin emas berada di kotak 1" yang padahal di kotak 1 tersebut sudah tertulis ukiran "kotak tidak berisi apa apa", dibanding kotak ke 3 yang tertulis ukiran yang memberi petunjuk ke kotak lain namun tidak ada petunjuk untuk kotak itu sendiri. 
sebagai perbandingan :

seperti yang permaisuri katakan bahwa hanya ada satu ukiran yang sesuai dengan isi kotak;
kesempatan yang dimiliki kotak 1 adalah 0%, karena sudah terukir tulisan "tidak berisi apa apa"
kesempatan yang dimiliki kotak 2 adalah 0%, karena terukir tulisan yang sama dengan kotak 1
kesempatan yang dimiliki kotak 3 adalah 50% yang berarti berisi koin dan 50% masih belum diketahui ketepatannya. mengapa? karena kotak ketiga memberi petunjuk yang merujuk ke kotak 1 dan tidak ada petunjuk untuk kotak itu sendiri.

kesimpulannya, kotak ke 3 masih beroleh kesempatan berisi koin dibanding dengan kotak lainnya dengan perolehan 50% berisi koin dan 50% belum diketahui isi kotak tersebut, jadi pemuda tersebut harus memilih kotak ke 3.
