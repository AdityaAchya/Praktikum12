# Praktikum12
Repository ini dibuat untuk memenuhi tugas pertemuan 14 - Bahasa Pemrograman

Nama : Aditya Achya Ananta Nur

Nim : 312210714

Kelas : TI.22.C.9

# Latihan 1
txt = 'Hello World' 

* Hitung jumlah karakternya

* Ambil karakter terakhir

* Ambil karakter index ke-2 sampai index ke-4 (llo)

* Hilangkan spasi pada text tersebut (HelloWorld)

* Ubah text menjadi huruf besar

* Ubah text menjadi huruf kecil

* Ganti karakter H dengan karakter J

> Point 1 "Hitung Jumlah Karakternya" dengan mengetikkan :

print("Jumlah karakternya adalah", len(txt))

![1](https://user-images.githubusercontent.com/123864099/218290807-4b51571e-cfc4-4764-b64c-3122db4c6d98.PNG)



> Point 2 "Ambil Karakter Terakhir" dengan mengetikkan :
print("Karakter terakhir adalah", txt[-1])

![2](https://user-images.githubusercontent.com/123864099/218290885-b2a3463c-b2ff-4f1b-a436-d86a4a3f555b.PNG)


> Point 3 "Ambil karakter index ke-2 sampai index ke-4 (llo)" dengan mengetikkan :
print("Karakter index ke-2 sampai index ke-4 adalah", txt[2:5])

![3](https://user-images.githubusercontent.com/123864099/218290892-441aff54-8d0f-4011-9db8-54631cc99b2d.PNG)


> Point 4 "Hilangkan spasi pada text tersebut (HelloWorld)" dengan mengetikkan :
print("Text tanpa spasi adalah", txt.replace(" ", ""))

![4](https://user-images.githubusercontent.com/123864099/218290896-b614c96d-0a85-4cb6-9c28-66a7668b2209.PNG)


> Point 5 "Ubah text menjadi huruf besar" dengan mengetikkan :
print("Text menjadi huruf besar adalah", txt.upper())

![5](https://user-images.githubusercontent.com/123864099/218290902-19a0dedb-db4c-49a8-839c-4da17754e2f1.PNG)


> Point 6 "Ubah text menjadi huruf kecil" dengan mengetikkan :
print("Text menjadi huruf kecil adalah", txt.lower())

![6](https://user-images.githubusercontent.com/123864099/218290911-28849bf2-d746-4cf1-8a15-d204220dade6.PNG)


> Point 7 "Ganti karakter H dengan karakter J" dengan mengetikkan :
print("Text dengan mengganti karakter H dengan J adalah", txt.replace("H", "J")) dengan mengetikkan :

![7](https://user-images.githubusercontent.com/123864099/218290923-ff0464a9-6be5-4fa7-bb54-cae8ba90aa62.PNG)



# Latihan 2
• Lengkapi kode berikut:
umur = 24
txt = 'Hello, nama saya john, dan umur saya adalah
... tahun'
print(txt.format(umur))

maka kita tambahkan "{}" menjadi :

umur = 24
txt = 'Hello, nama saya john, dan umur saya adalah {} tahun'
print(txt.format(umur))

maka outputnya akan menjadi :

![Latihan](https://user-images.githubusercontent.com/123864099/218290938-dbd8999b-b211-4cf5-acab-979c597a2a2c.PNG)


