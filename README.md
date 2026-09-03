# muhamad Nurul Bayan_algoritma_Pemograman
Tugas algoritma pemograman

##  Menentukan Bilangan Genap dan Ganjil

## A. Deskripsi Masalah

Dalam pembelajaran matematika, khususnya materi bilangan, bilangan bulat dapat dibedakan menjadi bilangan genap dan bilangan ganjil.

Bilangan yang habis dibagi 2 termasuk bilangan genap. Sedangkan bilangan yang tidak habis dibagi 2 termasuk bilangan ganjil.

Program ini menerapkan logika matematika untuk menentukan jenis bilangan berdasarkan kondisi yang diberikan. Program akan menerima sebuah bilangan bulat sebagai input, kemudian mengevaluasi apakah bilangan tersebut habis dibagi 2 atau tidak.

Berdasarkan hasil evaluasi tersebut, program akan menentukan apakah bilangan tersebut merupakan bilangan genap atau bilangan ganjil.

##  Identifikasi Input, Proses, dan Output

| Komponen | Keterangan |
|---|---|
| **Input** | Sebuah bilangan bulat yang akan diperiksa. |
| **Proses** | Program memeriksa bilangan menggunakan operasi modulo (`MOD 2`). Jika sisa hasil pembagian dengan 2 adalah 0, maka bilangan tersebut genap. Jika sisanya bukan 0, maka bilangan tersebut ganjil. |
| **Output** | Jenis bilangan, yaitu **Bilangan Genap** atau **Bilangan Ganjil**. |

---


## D. Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[/Input Bilangan/]
    B --> C{Bilangan % 2 == 0?}
    C -->|Ya| D[Bilangan Genap]
    C -->|Tidak| E[Bilangan Ganjil]
    D --> F([End])
    E --> F
```













##  Flowchart

   mermaid
graph TD
    A[Start] --> B[Input Bilangan]
    B --> C{Bilangan % 2 == 0?}
    C -- Ya --> D[Bilangan Genap]
    C -- Tidak --> E[Bilangan Ganjil]
    D --> F[End]
    E --> F
```


##  Implementasi Python

Implementasi program dibuat menggunakan bahasa pemrograman Python dengan memanfaatkan operator modulo (`%`) dan percabangan `if-else` untuk menentukan apakah suatu bilangan termasuk bilangan genap atau ganjil.


   
