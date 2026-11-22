# MATERI 4
# METHOD DALAM PEMROGRAMAN BERORIENTASI OBJEK

## A. Pengertian Method

Method adalah fungsi yang dibuat di dalam sebuah class dan digunakan untuk menentukan tindakan atau perilaku suatu objek.

Method dapat menjalankan perintah tertentu sesuai dengan kebutuhan program.

## B. Fungsi Method

1. Menentukan tindakan yang dapat dilakukan objek.
2. Mengatur perilaku suatu objek.
3. Membantu membuat program lebih terstruktur.
4. Mengurangi penulisan kode yang berulang.
5. Mempermudah pengelolaan program.

## C. Contoh Coding Python

class Orang:
    def __init__(self, nama):
        self.nama = nama

    def perkenalan(self):
        print("Halo, nama aku", self.nama)

alia = Orang("Alia")
cila = Orang("Cila")

alia.perkenalan()
cila.perkenalan()

## D. Hasil Program

Halo, nama aku Alia
Halo, nama aku Cila

## E. Penjelasan Coding

1. class Orang: membuat class bernama Orang.
2. __init__(): merupakan constructor.
3. self.nama: merupakan attribute untuk menyimpan nama.
4. perkenalan(): merupakan method untuk memperkenalkan nama.
5. alia.perkenalan(): menjalankan method pada objek Alia.
6. cila.perkenalan(): menjalankan method pada objek Cila.

## F. Kesimpulan

Method merupakan fungsi yang berada di dalam class dan digunakan untuk menentukan tindakan atau perilaku suatu objek. Dengan adanya method, program menjadi lebih terstruktur dan mudah dipahami.
