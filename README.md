# TUGAS-KE-6
Latihan 1
Saya diberikan tugas untuk membuat program perulangan bersarang/bertingkat (nested for) yang menghasilkan output berikut
output 1

Maka program yang saya buat sebagai berikut atau bisa dilihat di Source Code

baris = 10
kolom = baris

for bar in range(baris):
    for col in range(kolom):
        tab = bar+col
        print("{0:>5}".format(tab), end='')
    print()
Penjelasan

Pendeklarasian variable
baris = 10
kolom = baris
Untuk perulangan baris dan kolom menggunakan nested for
for bar in range(baris):
    for col in range(kolom):
        tab = bar+col        
Untuk menampikan hasil dari perulangan
Agar terlihat rapih menggunakan format string rata ke kanan sebanyak 5 karakter
Agar tidak membuat baris baru menggunakan end='' (baris)
Penggunaan print() untuk membuat baris baru (kolom)
  print("{0:>5}".format(tab), end='')
print()    


Latihan 2
Saya diberikan tugas untuk membuat program :
Tampilkan n bilangan acak yang lebih kecil dari 0.5
Nilai n diisi pada saat runtime
Seperti pada gambar berikut



import random
print(39*"=")
print("Bilangan acak yang lebih kecil dari 0,5")
print(39*"=")
jum = int( input("Masukan nilai n : "))
i = 0
for i in range(jum):
    i += 1
    angkaDec = random.uniform(0, 0.5)
    print("Data ke", i, " = ", angkaDec)
 
Penjelasan

Mengimport module random untuk membuat bilangan acak
import random
Untuk menentukan jumlah input yang diinginkan dan dikonversi ke dalam bilangan bulat (integer) yang dimasukan ke variable jum
jum = int( input("Masukan nilai n : "))
Untuk pengulangan range yang diinputkan oleh variable jum
for i in range(jum):
Untuk menampilkan urutan data sesuai jumlah inputan dengan hasil di bawah 0.5
angkaDec = random.uniform(0, 0.5)
    print("Data ke", i, " = ", angkaDec)
M
