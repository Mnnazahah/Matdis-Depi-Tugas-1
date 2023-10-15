 # Tugas 01

## **Anggota kelompok**
- Salsabila Putri Zahrani (10231086) (1)
- Djaky Abbyyu Fauzan Timumum (10231032) (2)
- Nazwa Amelia Zahra (10231068) (3)
- Andini Permata Dewanti (10231014) (4)
- Krishandy Dhanysa Pratama (10231050) (5)

---

## Soal 1

Manakah pernyataan berikut yang merupakan proposisi? Berikan juga alasannya
1. Jangan keluar dari ruangan kelas!
2. Berapa kali mahasiswa harus mengikuti kelas Matematika diskrit?
3. 3 + y = 14
4. 34 ≡ 1 (mod 11)
5. Anita dan Bayu saling berteman.

### Jawaban
1. Bukan proposisi, karna kalimat tersebut adalah kalimat perintah jadi tidak memiliki nilai benar atau salah.

2. Bukan proposisi, karena kalimat tersebut adalah kalimat pertanyaan yang meminta informasi lebih lanjut sehingga tidak memiliki nilai benar atau salah.

3. Bukan proposisi, karma persamaan tersebut memiliki nilai x yang tidak diketahui sehingga tidak bisa disebut sebagai proposisi sebab tidak memiliki nilai benar atau salah.

4. Proposisi, karna (34-1) habis dibagi 11. Jadi, merupakan proposisi bernilai benar.

5. Proposisi, karna kalimat tersebut memiliki nilai benar.

---

## Soal 2
Di dalam kuliah disinggung terkait operator logika disjungsi ekslusif (exclusive or), yang disimbolkan 
. Susunlah tabel kebenarannya dan berikan dua contoh proposisi yang mewakili disjungsi ekslusif tersebut.

JAWAB


| P | Q | P ⊻ Q |
|---|---|-------|
| F | F |    F  |
| F | T |   T   |
| T | F |   T   |
| T | T |    F  |

1.Pernyataan 1: "Saya akan pergi ke pantai atau ke pegunungan,tapi tidak keduanya"
Pernyataan 1: "Saya akan pergi ke pantai atau ke pegunungan, tapi tidak keduanya."

P: Saya akan pergi ke pantai (T jika benar, F jika salah)
Q: Saya akan pergi ke pegunungan (T jika benar, F jika salah)
Dengan menggunakan XOR, pernyataan ini akan menjadi: "Saya akan pergi ke pantai atau ke pegunungan, tapi tidak keduanya."
Pernyataan 2: "Lampu ruang tamu berwarna merah atau hijau, tapi tidak keduanya pada saat yang bersamaan."

P: Lampu ruang tamu berwarna merah (T jika benar, F jika salah)
Q: Lampu ruang tamu berwarna hijau (T jika benar, F jika salah)
Dengan menggunakan XOR, pernyataan ini akan menjadi: "Lampu ruang tamu berwarna merah atau hijau, tapi tidak keduanya pada saat yang bersamaan."

---

## Soal 3
Susunlah tabel kebenaran untuk proposisi majemuk berikut :
1. $(\neg p \wedge q) \rightarrow (\neg\neg q \rightarrow p)$
2. $((p \leftrightarrow \neg q) \oplus r) \vee r$

### Jabawan



1. $(\neg p \wedge q) \rightarrow (\neg q \rightarrow p)$


|  $p$  |  $q$  | $\neg p$ | $\neg q$  |     $\neg\neg q$  | $\neg p\wedge q$  | $\neg\neg q \rightarrow p$ | $(\neg p \wedge q) \rightarrow (\neg q \rightarrow p)$ |
|:-----:|:-----:|:--------:|:---------:|:-----------------:|:-----------------:|:----------------------:|:----------------------:| 
|   T   |   T   |     F    |     F     |         T          |        F          |           T            |             T         |
|   T   |   F   |     F    |     T     |         F          |        F          |           T            |             T         |
|   F   |   T   |     T    |     F     |         T          |        T          |           F            |             F         |
|   F   |   F   |     T    |     T     |         F          |        F          |           T            |             T         |

2. $((p \leftrightarrow \neg q) \oplus r) \vee r$

|  $p$  |  $q$  |  $r$  | $\neg q$ | $P \leftrightarrow \neg q$ |  $((P \leftrightarrow \neg q) \oplus r)$  | $((p \leftrightarrow \neg q) \oplus r) \vee r$ |
|:-----:|:-----:|:-----:|:--------:|:--------------------------:|:-----------------------------------------:|:--------------------------------------------:| 
|   T   |   T   |   T   |    F     |             F              |                   T                       |          T          |
|   T   |   T   |   F   |    F     |             F              |                   F                       |          F          |
|   T   |   F   |   T   |    T     |             T              |                   F                       |          T          |
|   T   |   F   |   F   |    T     |             T              |                   T                       |          T          |
|   F   |   T   |   T   |    F     |             T              |                   F                       |          T          |
|   F   |   T   |   F   |    F     |             T              |                   T                       |          T          |
|   F   |   F   |   T   |    T     |             F              |                   T                       |          T          |
|   F   |   F   |   F   |    T     |             F              |                   F                       |          F          |

---

## Soal 4
Tentukan konvers, kontrapositive, dan invers dari
pernyataan kondisional berikut

1. Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika diskrit.
2. Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.


### Jawaban
1. Jika hari ini hujan, maka saya tidak akan datang ke kuliah matematika diskrit.

Konvers : Jika saya tidak datang ke kuliah matematika diskrit, maka hari ini pasti hujan.

Kontrapositive : Jika saya datang ke kuliah matematika diskrit, maka tidak mungkin hari ini hujan.

Invers : Jika hari ini tidak hujan, maka saya akan datang ke kuliah matematika diskrit.

 Tabel Kebenaran 1
|$p$ | $q$ | $q \rightarrow p$  | $\neg q \rightarrow \rightarrow p$  | $\neg p \rightarrow \rightarrow q$  |
|--|---|----|-----|------|
|T | T | T  | T   | T    |
|T | F | T  | F   | T    |
|F | T | F  | T   | F    |
|F | F | T  | T   | T    |


2. Saya akan belajar hingga jam dua dini hari, jika hari kemarin saya lupa untuk belajar.

Konvers : jika hari kemarin saya lupa untuk belajar, maka saya akan belajar hingga jam dua dini hari.

Kontrapositive : jika hari kemarin saya belajar, maka saya tidak akan belajar hingga jam dua dini hari.

Invers : saya tidak akan belajar hingga jam dua dini hari, jika hari kemarin saya tidak lupa untuk belajar.


Tabel Kebenaran 2
|$p$ | $q$ | $q \rightarrow p$  | $\neg q \rightarrow \rightarrow p$  | $\neg p \rightarrow \rightarrow q$  |
|--|---|----|-----|------|
|T | T | T  | T   | T    |
|T | F | T  | F   | T    |
|F | T | F  | T   | F    |
|F | F | T  | T   | T    |

---

## Soal 5
Sebagai imbalan karena menyelamatkan putri seorang raja, seorang pemuda diberi kesempatan untuk memperoleh sejumlah koin emas yang tersimpan di salah satu tiga kotak yang ditawarkan oleh raja. Dua kotak diantara tiga kotak merupakan kotak kosong. Agar pemuda tersebut memperoleh koin emas, dia harus memilih kotak yang tepat.Di setiap kotak tertulis ukiran berikut:

- Kotak 1 dan Kotak 2 tertulis: "Kotak tidak berisi apa-apa".
- Kotak 3: "Koin emas berada di kotak 1".

Permaisuri yang tidak pernah berbohong membantu pemuda tersebut dengan mengatakan bahwa hanya ada satu ukiran yang sesuai dengan isi kotak, dan dua sisanya adalah palsu. Kotak manakah yang harus dipilih oleh pemuda tersebut?

### Jawaban
Jika permaisuri tidak pernah berbohong dan hanya ada satu ukiran yang benar, maka ada dua kemungkinan:

1. Jika Kotak 1 berisi koin emas, maka pernyataan di Kotak 3 adalah salah, karena Kotak 3 mengatakan koin emas ada di Kotak 1.
2. Jika Kotak 1 kosong, maka pernyataan di Kotak 3 adalah benar, karena memang koin emas ada di Kotak 1.

Dengan demikian, kita dapat menyimpulkan bahwa Kotak 1 tidak mungkin berisi koin emas. Jika Kotak 1 kosong, maka Kotak 2 harus berisi koin emas sesuai dengan pernyataan bahwa hanya ada satu ukiran yang benar.

Jadi, pemuda tersebut harus memilih Kotak 2.