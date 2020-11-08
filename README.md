# Pertemuan-7-labpy03

Repositiry ini dibuat untuk memenuhi tugas Pertemuan 7 - Bahasa Pemrograman (Module Praktikum 3)<br><br>
Nama : Mohamad Farizal Arifin <br>
NIM : 312010231<br>
Dosen : Agung Nugroho, M.Kom<br>
Matkul : Bahasa Pemrograman<br>
Kelas : TI.20.B.1<br>

Pada halaman ini (Tugas Pertemuan-7-Module Praktikum 3) Dosen memberi tugas sebagai berikut : <br>
![tugas](pict/soaltugas.PNG)<br>

# Latihan1
# Algoritma
**Menampilkan n bilangan acak yang lebih kecil dari 0,5**<br><br>
**Nilai n diisi pada saat runtime.**<br>
* Memasukan/ import fungsi RANDOM terlebih dahulu<br>
* Deklarasi integer , masukkan jumlah n :<br>
* Memasukan deskripsi kombinasi for untuk menyelesaikannya.<br>
* Memasukan nilai jumlah (n) : 5<br>
* Mencetak data ke 1 sampai 5 dengan hasil nilai kurang dari 0,5.<br>
* Selesai<br><br>
Berikut source code yang saya buat :<br>

```python
#latihan 1
print ("Masukan Jumlah N : 5 ")
import random
jumlah = 5
a = 0
for x in range (jumlah):
        i = random.uniform(.0,.5)
        a+=1
        print('data ke :',a,'==>', i)
print("---SELESAI---")
```
Berikut hasil run syntax diatas :<br>

![hasil running](pict/hasillatihan1.PNG)<br>

# Latihan2
# Algoritma
**Membuat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan**<br><br>
**Masukkan angka 0 untuk berhenti**<br>
* Mulai*<br>
* Mencetak "latihan 2"*<br>
* Mencetak "menampilkan bilangan, berhenti ketika bilangan 0, menampilkan bilangan terbesar"*<br>
* integer max = 0*<br>
* Menggunakan fungsi perulangan while true, hingga menampilkan perulangan sampai batas tertentu.*<br>
* Memasukan bilangan integer pada "a"*<br>
* Menggunakan fungsi if jika max kurang dari nilai a, maka max sama dengan a*<br>
* Mengunakan fungsi if jika nilai a adalah 0 maka fungsi break artinya perulangan berhenti jika menulis nilai 0.*<br>
* Mencetak nilai paling terbesarv setelah break, sehingga menampilkan nilai terbesar diantara bilangan tersebut dalam perulangan.*<br>
* Selesai*<br><br>
Berikut source code yang saya buat :<br>

```python
