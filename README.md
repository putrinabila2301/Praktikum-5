# Praktikum-5

# Pada praktikum kali ini saya akan membuat program sederhana tentang menambahkan sebuah data kedalam sebuah list:
 Berikut Source Code & Penjelasanya:

jihan = []                                              (Membuat list nilai kosong)

nomor = 1            

while True:                                             (Looping)

    Nama = input("Masukan nama:")                       (Membuat variable nama untuk list dan menginputkan data)
    NIM  = input("Masukan nim:")                        (Membuat variable nim untuk list dan menginputkan data)
    NilaiTugas = int(input("Masukan tugas: "))          (Membuat variable tugas untuk list dan menginputkan data)
    NilaiUTS = int(input("Masukan uts: "))              (Membuat variable uts untuk list dan menginputkan data)
    NilaiUAS = int(input("Masukan uas: "))              (Membuat variable uas untuk list dan menginputkan data)
    a = NilaiTugas*30/100                           
    b = NilaiUTS*35/100
    c = NilaiUAS *35/100
    NilaiAkhir = a+b+c                                 (Membuat variable nilaiAkhir untuk list dan menggabungkan sesuai dengan variable                                                           dan data yang di inginkan)
    putri = input("tambah data t/y")                  
    
    jihan.append([Nama,NIM,NilaiTugas,                (Menambahkan semua list nama sampai nilaiAkhir ke list nilai.)
                  NilaiUTS,NilaiUAS,
                  NilaiAkhir, nomor])
    nomor = nomor + 1
    if putri == "t":
        break
        
#print("=====================================================")
#print("| No |    Nama    |  NIM  | Tugas | UTS |  UAS | Akhir|")
#print("======================================================")
for ammarr in jihan:

    print("| {nomor:2} | {Nama:2} "                     (Mengatur posisi tabel)
          "| {NIM:2} | {NilaiTugas:2} "
          "| {NilaiUTS:2} | {NilaiUAS:2} "
          "| {NilaiAkhir:2.2f} |"
          .format(Nama=ammarr[0],NIM=ammarr[1],         (Mengambil list yang sudah diinputkan didalam list nilai)
                  NilaiTugas=ammarr[2],
                  NilaiUTS=ammarr[3],
                  NilaiUAS=ammarr[4],
                  NilaiAkhir =ammarr[5],
                  nomor=ammarr[6]))
#print("======================================================")

# Berikut adalah Inputnya :

![daftar](

![daftar](

# Berikut adalah Outputnya:

![daftar](

# Berikut adalah Flowchartnya:

![daftar](

