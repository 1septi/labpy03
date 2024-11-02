# labpy03

Nama : Ika Septianingrum

Kelas : IE.23.C12

NIM : 352310873


LATIHAN 1 

Intruksi :
1. Tampilkan nilai n bilangan acak yang lebih kecil dari 0.5
2. Nilai n diisi saat run time
3. Menggunakan while atau for
4. Menggunakan fungsi random
   
Screenshot Hasil Program yang dibuat
![Capture 1](https://github.com/user-attachments/assets/70099e90-a896-4017-97eb-ac71216e9af3)
Algoritma dan penjelasan
1. Pertama kita buat program terlebih dahulu menggunakan Idle
2. Saat membuat program, yang pertama kita buat sistem input terlebih dahulu agar kita bisa menginput suatu bilangan saat di runtime dengan rumus n = int(input("Masukkan jumlah bilangan acak yang ingin ditampilkan: "))
3. Nisialisasi variabel untuk menghitung jumlah bilangan yang telah ditampilkan dengan rumus count = 0
4. Gunakan while untuk terus menghasilkan bilangan acak sampai mencapai n, dengan rumus while count < n:
5. Menghasilkan bilangan acak sampai mencapai n, dengan rumus while count < n:
6. Selanjutya akan menghasilkan bilangan acak dengan a = random()
7. Priksa apakah bilangan acak kurang dari 0.5, rumus: if a < 0.5: count += 1 # Menambah hitungan bilangan yang ditampilkan print(f"Data ke : {count} => {a}")
8. Menampilkan bilangan acak dengan format yang diinginkan
9. Selesai
    

    
LATIHAN 2 

Intruksi  : Buat program untuk menampilkan bilangan terbesar dari n buah data yang diinputkan. Masukkan angka 0 untuk berhenti.

Screenshot Hasil Dari Program yang dibuat
![Capture 2](https://github.com/user-attachments/assets/7b7fe3a5-3808-449f-8112-36f35bfc80e4)
Algoritma dan penjelasan
1. Membuat program terlebih dahulu menggunakan Idle
2. Inisialisasi variabel untuk menyimpan bilangan terbesar dengan rumus max_number = None
3. Selanjutnya buatlah while true : Mengambil input dari pengguna,
4. Memeriksa apakah pengguna memasukkan 0, Memperbarui bilangan terbesar jika diperlukan
5. Menamplkan bilangan terbesarnya dengan rumus, if max_number is not None: print("Bilangan terbesar adalah:", max_number) else: ("Tidak ada angka yang dimasukkan.")
6. Selesai



Latihan 3 

Intruksi : Seorang pengusaha menginvestasikan uangnya untuk memulai usahanya dengan modal awal 100 juta, pada bulan pertama dan kedua belum mendapatkan laba. pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%. Hitung total keuntungan selama 8 bulan berjalan usahanya.

Screenshot Hasil Dari Program yang dibuat
![Capture 3](https://github.com/user-attachments/assets/af84ecdf-06b7-40af-a723-7764d76c2857)
Algoritma dan penjelasan
1. Buatlah program terlebih dahulu menggunakan Idle
2. Buat print modal awal,rumus :modal_awal = 100_000_000
3. Nisialisasi list untuk menyimpan laba setiap bulan dengan menggunakan statement for, in, If, elif
4. Menghitung total laba dengan rumus SUM
5. Menampilkan hasil dengan rumus For 1 in
6. Selesai
