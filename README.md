<h1> Program Sederhana Python Penambahan Data Ke Dalam List </h1>

Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut :
1. Program meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)
2. Tampilkan pertanyaan untuk menambah data(y/t?), apabila jawaban **t**(Tidak), maka program akan menampilkan daftar datanya.
3. Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
4. Buat flowchart dan penjelasan programnya pada README.md
5. Commit dan Push ke repository github

***Tampilan Program***
![Screenshot (51)](https://user-images.githubusercontent.com/46983614/68989708-f3f35980-087c-11ea-969d-449c588d6115.png)

![Screenshot (52)](https://user-images.githubusercontent.com/46983614/68989717-07062980-087d-11ea-894c-5e3b7dc004cf.png)

***Coding***

    nama = input("Masukan Nama:")
    nim = input("Masukan NIM:")
    uts = input("Masukan Nilai UTS:")
    uas = input("Masukan Nilai UAS:")
    tugas = input("Masukan Nilai Tugas:")

    akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)

    print("\nNama               :",nama)
    print("\nNIM                :",nim)
    print("Nilai UTS            :",uts)
    print("Nilai UAS            :",uas)
    print("Nilai Tugas          :",tugas)
    print("Nilai Akhir          :",akhir)

    print ('')
    print ('Tambah Data? (ya/tidak)')
    x=input()

***Note:Projects Belum Selesai***
