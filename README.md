# Labspy4
Labspy04 is a trial code for list in python


## Latihan 1

Latihan yang pertama adalah membuat list dengan menulis:
```python
list=[] 
```
(keterangan: list dapat diubah dengan nilai lainnya misal list1, atau nama lainnya)

berikut penulisan dalam python:
![Screenshot (98)](https://user-images.githubusercontent.com/92356397/143443204-3ea6e365-9175-4591-9649-61f96de6ea04.png)

dengan keterangan:
```python
list=["a", "b", "c", "d", "e"]
```
- diatas adalah isi list nya

```python
print("Tampilkan Element ke 3:", list[2])
```
- diatas adalah perintah untuk menampilkan elemen ke 3 dalam list, karena elemen ke 3 ada di index 2, maka didalam list pakai kurung siku[2]

```python
print("ambil Element ke 2 sampai 4:", list[1:4]) 
```
- diatas untuk perintah untuk mengambil elemn ke 2 sampai ke 4 dengan index elemen ada di index 1 sampai 4

```python
print("ambil elemen terakhir:", list[5-1])
```
- sedangkan diatas ini adalah perintah untuk mengambil elemen terakhir, karena di dalam list ada 5 elemen, maka digunakan -1 untuk mengambil elemen terakhir


### merubah elemen ke 4 dengan nilai lain
```python
list[3] = "f" 
```
- sedangkan ini untuk merubah elemen ke 4 dengan nilai F, karena elemen ke 4 ada di index 3, maka ditulis list[3]

```python
print("merubah elemen ke 4 dengan nilai lain:", list)
```
- merubah elemen ke 4 sampai terakhir

```python
list[3:] = "f", "g" 
```
- ini untuk merubah elemen ke 4 sampai terakhir dengan string "f" dan "g". maka ditulis list[3:]

```python
print("merubah elemen ke 4 sampai elemen terakhir:", list)
```
berikut hasil pemogramannya:
![Screenshot (100)](https://user-images.githubusercontent.com/92356397/143443520-5e59f61d-14dc-4380-a4a5-2f4feb4484b4.png)

### Latihan untuk menambahkan elemen dalam list:

berikut gambar program nya:

![Screenshot (101)](https://user-images.githubusercontent.com/92356397/143449717-4f28c7ae-e82c-4d90-a686-56493f7aa90c.png)

### tambah elemen list
```python
a=[1,2,3,4,5]
b=[6,7,8,9,10]
```
- diatas adalah untuk membuat 2 list


### Ambil 2 bagian list A ke list B

```python
b.append(a[1:3])
print("2 bagian List A dijadikan List B:", b)
```
- diatas adalah code untuk menambahkan list A kedalam list B dengan menggunakan perintah append

### tambah list b dengan string
```python
b.append("saya")
print("Tambah B dengan Sring:", b)
```
- diatas adalah untuk menambahkan list B dengan string menggunakan append

### tambah list b dengan 3 nilai
```python
print("Tambah list b dengan 3 nilai:", b+[11,12,13])
```
- diatas adalah untuk menambahkan list b dengan 3 nilai dengan menggunakan arithmatic +

### Gabungan List B dan A
```python
c=b+a
print("Gabungan list B dan A:", c)
```
- dan yang di atas ini adalah untuk menggabungkan list B dan list A, menjadi list C

Berikut hasil programnya:
