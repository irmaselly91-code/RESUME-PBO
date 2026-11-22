
# MATERI 2
# CLASS DAN OBJECT

## A. Pengertian Class

Class adalah cetakan atau rancangan yang digunakan untuk membuat objek dalam pemrograman berorientasi objek.

Class berisi atribut dan method yang akan dimiliki oleh objek.

Contoh:
class Orang:
    pass

## B. Pengertian Object

Object adalah hasil nyata dari sebuah class. Setiap objek dapat memiliki data atau nilai yang berbeda meskipun berasal dari class yang sama.

Contoh:
alia = Orang()
cila = Orang()

Alia dan Cila merupakan dua objek dari class Orang.

## C. Contoh dalam Kehidupan Sehari-hari

Misalnya terdapat class Orang yang digunakan untuk membuat objek manusia.

- Class: Orang
- Object pertama: Alia
- Object kedua: Cila
- Attribute: Nama

## D. Contoh Program Python

class Orang:
    def __init__(self, nama):
        self.nama = nama

alia = Orang("Alia")
cila = Orang("Cila")

print(alia.nama)
print(cila.nama)

## E. Hasil Program

Alia
Cila

## F. Kesimpulan

Class merupakan cetakan untuk membuat objek, sedangkan object merupakan hasil dari class tersebut. Class dan object adalah konsep dasar dalam Pemrograman Berorientasi Objek.
