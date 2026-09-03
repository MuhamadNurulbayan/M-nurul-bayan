# muhamad Nurul Bayan_algoritma_Pemograman
Tugas algoritma pemograman

##  Menentukan Bilangan Genap dan Ganjil

## A. Deskripsi Masalah

Dalam pembelajaran matematika, khususnya materi bilangan, bilangan bulat dapat dibedakan menjadi bilangan genap dan bilangan ganjil.

Bilangan yang habis dibagi 2 termasuk bilangan genap. Sedangkan bilangan yang tidak habis dibagi 2 termasuk bilangan ganjil.

Program ini menerapkan logika matematika untuk menentukan jenis bilangan berdasarkan kondisi yang diberikan. Program akan menerima sebuah bilangan bulat sebagai input, kemudian mengevaluasi apakah bilangan tersebut habis dibagi 2 atau tidak.

Berdasarkan hasil evaluasi tersebut, program akan menentukan apakah bilangan tersebut merupakan bilangan genap atau bilangan ganjil.

## 📥 Identifikasi Input, Proses, dan Output

| Komponen | Keterangan |
|---|---|
| **Input** | Sebuah bilangan bulat yang akan diperiksa. |
| **Proses** | Program memeriksa bilangan menggunakan operasi modulo (`MOD 2`). Jika sisa hasil pembagian dengan 2 adalah 0, maka bilangan tersebut genap. Jika sisanya bukan 0, maka bilangan tersebut ganjil. |
| **Output** | Jenis bilangan, yaitu **Bilangan Genap** atau **Bilangan Ganjil**. |

---


##  Pseudocode

```text
INPUT bilangan

IF bilangan MOD 2 = 0 THEN
    OUTPUT "Bilangan Genap"
ELSE
    OUTPUT "Bilangan Ganjil"
END IF


##  Flowchart

```text
+---------+
|  START  |
+---------+
     |
     v
+------------------+
| Input Bilangan   |
+------------------+
     |
     v
+------------------+
| Bilangan % 2 = 0?|
+------------------+
    /        \
  Ya          Tidak
  /              \
 v                v
+----------+  +-----------+
|  Genap   |  |  Ganjil   |
+----------+  +-----------+
      \        /
       \      /
        v    v
     +-------+
     |  END  |
     +-------+
```


