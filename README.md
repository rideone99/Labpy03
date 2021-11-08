# TUGAS PERTEMUAN 7 LABPY3

# Soal Labpy3

![img](gambar/labpy3.png)

# Latihan 1
pada latihan 1 saya diberi soal sebagai berikut

![img](gambar/latihan1.png)
 
 untuk mengerjakannya , saya memasukan syntax dibawah

    import random
    print(40*"=")
    print("Bilangan acak yang lebih kecil dari 0,5")
    print(40*"=")
    jum = int( input("Masukan nilai n : "))
    i = 0
    for i in range(jum):
        i += 1
        angkaDec = random.uniform(0, 0.5)
        print("Data ke", i, " = ", angkaDec)

Dan saya mendapatkan output :

![img](gambar/output3.png)

# Latihan 2

Pada latihan 2 saya diberi soal sebagai berikut :

![img](gambar/latihan2.png)

Untuk mengerjakan saya memasukan syntax seperti dibawah :

    print("menampilkan bilangan berhenti ketika bilangan 0 dan menampilkan bilangan terbesar")

    max=0
    while True:
        a=int(input("masukan bilangan : "))
        if max < a :
            max = a
        if a==0:
            break
    print("bilangan terbesar adalah = ",max)

    Dan saya mendapatkan output :

Dan saya mendapatkan output :

![img](gambar/output1.png)

# Program 1

Pada program 1 saya diberi soal sebagai berikut :

![img](gambar/program1.png)

Untuk mengerjakan saya menggunakan syntax sebagai berikut :

    print("******* PROGRAM 1*******")
    print("Program menghitung laba dengan modal 100.000.000")
    print("")
    print("Note:")
    print("Bulan pertama dan ke 2 = 0%")
    print("Pada bulan ke 3 = 1%")
    print("Pada bulan ke 5 = 5%")
    print("pada bulan ke 8 = 2%")
    print("")
    #variable
    a = 100000000
    for x in range(1,9):
        if(x>=1 and x<=2):
            b = a*0
            print("Laba bulan ke-",x," : ",b)
        if(x>=3 and x<=4):
            c = a*0.1
            print("Laba bulan ke-",x," : ",c)
        if(x>5 and x<=7):
            d = a*0.5
            print("Laba bulan ke-",x," : ",d)
        if(x==8):
            e = a*0.5
            print("Laba bulan ke-",x," : ",e)
    total=b+b+c+c+d+d+d+e
    print("\Total : ",total)

Dan saya mendapatkan output :

![img](gambar/output2.png)

Terima kasih


