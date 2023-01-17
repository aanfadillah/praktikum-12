# praktikum-12

### Nama : Aan Fadillah Putra
### Nim : 312210327
### Kelas : TI.22.A.3

# Daftar Isi

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Python String|[Click Here](#Python-String)|
|2|Latihan 1|[Click Here](#Latihan1)|
|3|Latihan 2|[Click Here](#Latihan2)|

## Tali Python
•String adalah jenis yang paling populer di Python.

•Untuk membuatnya hanya dengan kekerasan karakter dalam tanda kutip.

•Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").

•Membuat string yang rusak memberi nilai pada sebuah variabel.

## Latihan 1

![209518488-643ebee6-ed6b-48af-bb5f-08c9196e24d4](https://user-images.githubusercontent.com/115763475/212794849-5493d5fc-be16-4a5e-8516-815e296fd246.png)

### Penjelasan Latihan 1

•Untuk menghitung jumlah karakter, gunakan fungsi len().

   #Menghitung jumlah karakternya
       print(len(txt))

•Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku [ ]dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan index [-1] . Sedangkan untuk mengambil karakter index ke-2 sampai ke-4 , gunakan index [2:5] .

#Mengambil karakter terakhir
print(txt[-1])

#Mengambil karakter index ke-2 sampai index ke-4 (llo)
print(txt[2:5])


•Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculannya.


•Di dalam method replace , kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", ""))dan yang kedua dengan cara (txt.replace(txt[5], "")).

#Menghilangkan spasi pada text tersebut (HelloWorld)
print(txt.replace(" ", ""))


•Untuk mengubah huruf menjadi besar, gunakan method upper(). Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method lower().

#Mengubah text menjadi huruf besar
print(txt.upper())
#Mengubah text menjadi huruf kecil
print(txt.lower())


•Untuk mengganti karakter 'H'dengan karakter 'J', gunakan method replace().

#Mengganti karakter H dengan karakter J
print(txt.replace("H", "J"))
print()


## Keluar Latihan 1


![IMG_20230117_092416](https://user-images.githubusercontent.com/115763475/212797852-e1e7d075-0c23-4bc1-87c9-1d722cc21e16.png)


## Latihan 2

![209519946-c3b1ec80-a683-48d6-a43b-0dbd2d716631](https://user-images.githubusercontent.com/115763475/212796464-00435014-df13-4022-a3bd-e64d55d1a439.png)

### Penjelasan Latihan 2

•Untuk memasukkan variabel ke dalam string, tambahkan kurung kurawal {}untuk menempatkan variabel sebelumnya.


  umur = 24
  txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

  print(txt.format(umur))

## Keluaran Latihan 2


![IMG_20230117_092355](https://user-images.githubusercontent.com/115763475/212796766-47d20a4f-6bd8-4242-b932-1c801829c854.png)
