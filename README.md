# PERTEMUAN 7
### NAMA: DIYAN ARUM M
### KELAS: TI. 20. A. 1
### NIM: 312010133
___________________________________________________________________________________

 Pada pertemuan 7 tugas PPT ke-2 ini, saya diberikan beberapa tugas oleh dosen saya yaitu 

![Tugas Praktikum 2](https://user-images.githubusercontent.com/72906579/98377632-a5376480-2077-11eb-914b-7edfddf5d866.png)

untuk mencari sebuah nilai maksimal dari 3 data yang sebelumnya telah diinput, dan setelah mendapat nilai maksimalnya, dirubah menjadi dalam sebuah bentuk flowchart.

## TUGAS PRAKTIKUM 2
##### MENGINPUT DATA DAN MENCARI NILAI MAX
________________________________________________________________________________________
Pertama-tama disini saya akan mencoba untuk menginput 3 data dengan menggunakan syntax berikut terlebih dahulu.
```python
a = int(input("Masukkan bilangan 1: "))
b = int(input("Masukkan bilangan 2: "))
c = int(input("Masukkan bilangan 3: "))
```
Masukan syntax tersebut dengan angka yang kalian inginkan. 

<img width="159" alt="ppt2" src="https://user-images.githubusercontent.com/92860414/141230648-ec7ae448-ad28-4056-a0b4-1420f35f836d.png">


Jika sudah mendapat tampilan seperti gambar diatas, maka kalian sudah berhasil menginput ketiga data tersebut. <br>

Langkah selanjutnya adalah mencari tahu nilai terbesar (max) dari ketiga data tersebut. Sebelum memulainya kalian harus memasukan terlebih dahulu berapa jumlah data yang akan kalian kerjakan dari ketiga data tersebut dengan syntax <br>
```python
N=int(input("banyaknya data = "))
```
Karena disini saya diberi tugas mencari nilai max dari ketiga data maka saya akan menggunkan semua data diatas.

```python
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```
Selanjutnya kalian bisa langsung  memasukan syntax ini untuk melengkapi syntax diatas supaya bisa berjalan dengan baik seperti pada gambar dibawah ini.



Maka jika digabungkan, cara untuk mencari nilai max dari ketiga data yang diinputkan adalah dengan menggunakan syntax
```python
N=int(input("banyaknya data = "))
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```
Seperti inilah hasil akhirnya 


##### FLOWCHART
__________________________________________________________________________________
Setelah kalian mendapatkan semua data diatas langkah selanjutnya adalah mengubahnya menjadi dalam bentuk flowchart seperti ini

![Flowchart](https://user-images.githubusercontent.com/72906579/98388431-55f83080-2085-11eb-9e13-0adbdae25e4d.png)

