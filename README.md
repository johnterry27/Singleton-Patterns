# Tugas 2 - Pemrograman Berorientasi Objek (PBO)

## Kelompok: Singleton (Java)
**Anggota:**
- John Terry (23100010)
- Oktria Taranasta (23100011)
- Jenie Josphin (23100016)

## Definisi Pola Desain Singleton
Singleton adalah kelas yang hanya dapat memiliki satu objek (kelas) pada satu waktu. Setelah pertama kali, jika mencoba membuat contoh kelas Java Singleton, variabel baru juga menunjuk ke contoh pertama yang dibuat. Jadi, modifikasi apa pun yang dilakukan pada variabel apa pun di dalam kelas melalui contoh apa pun, dapat memengaruhi variabel dari contoh tunggal yang dibuat dan terlihat jika mengakses variabel itu melalui variabel apa pun dari tipe kelas yang ditentukan. Singleton Design pattern termasuk ke dalam jenis creational Design Pattern. Pola desain ini digunakan dalam konteks pembuatan sebuah instansiasi dari kelas objek. 

## Tujuan Design Pattern Singleton
Singleton Design pattern bertujuan agar sebuah class hanya mempunyai satu instansiasi yang menyediakan akses global pada instansiasi tersebut. Pola desain ini membatasi sebuah kelas dan memastikan sebuah kelas hanya mengembalikan satu instansiasi saja atau instansiasi tunggal. Penggunaan singleton ini didasari pada sebuah masalah pada pembuatan sebuah objek di mana sebuah class dapat membuat banyak instansiasi. Padahal, instansiasi tersebut cuma dibutuhkan satu saja, atau sebenarnya hanya perlu satu instansiasi saja untuk melakukan sebuah aksi pada program. 

## Penggunaan Design Pattern Singleton



## Hubungan Design Pattern Singleton dengan Pola Lainnya
Hubungan dengan kelas Facade seringkali dapat diubah menjadi Singleton karena satu objek facade saja sudah dapat mencukupi dalam kebanyakan kasus. Flyweight akan menyerupai Singleton jika berhasil mengurangi semua status bersama objek menjadi hanya satu objek flyweight. Namun, ada dua perbedaan mendasar antara pola-pola berikut. Seharusnya hanya ada satu instansi Singleton, sedangkan kelas Flyweight dapat memiliki beberapa instansi dengan status intrinsik yang berbeda.
Objek Singleton dapat berubah. Objek Flyweight tidak dapat diubah.
Pabrik Abstrak, Pembangun dan Prototipe semuanya dapat diimplementasikan sebagai Singleton .

## Kelebihan dan Kekurangan Singleton
| **Kelebihan** | **Kekurangan** |
|---------------|--------------|
| Hanya memiliki satu instance. | Perlu perlakuan khusus jika dalam kondisi multithread. |
| Membuat akses fungsi global. | Kesulitan ketika membuat unit test karena instance bersifat private. |
| Objek hanya diinisialisasi untuk pertama kali saja. |

## Sumber
- [Refactoring Guru - Command Pattern](https://informatics.uii.ac.id/2023/02/06/berkenalan-dengan-singleton-design-pattern/)
- [Refactoring Guru - Command Pattern](https://www.santekno.com/cara-implementasi-singleton-design-pattern-golang/)
