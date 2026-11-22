# MATERI 3
# CONSTRUCTOR DAN ATTRIBUTE

## A. Pengertian Constructor

Constructor adalah bagian khusus dalam class yang digunakan untuk memberikan nilai awal ketika sebuah objek dibuat.

Dalam Python, constructor ditulis menggunakan fungsi __init__().

## B. Pengertian Attribute

Attribute adalah data atau karakteristik yang dimiliki oleh sebuah objek.

Contohnya adalah nama, umur, alamat, dan jenis kelamin.

## C. Contoh Coding Python

class Orang:
    def __init__(self, nama, umur):
        self.nama = nama
        self.umur = umur

alia = Orang("Alia", 20)
cila = Orang("Cila", 21)

print("Nama:", alia.nama)
print("Umur:", alia.umur)

print("Nama:", cila.nama)
print("Umur:", cila.umur)

## D. Hasil Program

Nama: Alia
Umur: 20
Nama: Cila
Umur: 21

## E. Penjelasan Coding

1. class Orang: membuat class bernama Orang.
2. __init__(): merupakan constructor.
3. self.nama: attribute untuk menyimpan nama.
4. self.umur: attribute untuk menyimpan umur.
5. alia dan cila: merupakan objek dari class Orang.
6. print(): menampilkan data objek.

## F. Kesimpulan

Constructor digunakan untuk memberikan nilai awal pada objek, sedangkan attribute digunakan untuk menyimpan data atau karakteristik objek.
