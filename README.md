# Readme.md
# Fatur Raflin
# 2309116056
while True :
    try:
        Nama = str(input("Masukkan Nama :"))
        Nim =  int(input("Masukkan Nim :"))
        Password = int(input("Password :"))

        if (Nim == int, Password == 123):
            print ("Anda telah berhasil login")

            print(20*"=")
            print("Selamat datang")
            print(20*"=")
            
            angka1 = float(input("Masukkan Berat dalam Satuan KG :"))
            
            print("\nPilih Konversi :")
            print("1. Kilogram --> Pounds")
            print("2. Kilogram --> Ounces")
            print("3. Kilogram --> Gram")
            print("4. Keluar")

            pilihan = input("Masukkan nomor konverter : ")
            if pilihan == '4' :
                break


            if pilihan == '1' :
                angka1 *= float(2.204623)
                print("Hasil perkalian : ", angka1, "Lbs")
            if pilihan == '2' :
                angka1 *= float(35.274)
                print("Hasil perkalian : ", angka1, "Ons")
            if pilihan == '3' :
                angka1 *= int(1000)
                print("Hasil perkalian : ", angka1, "Gram")

    except ValueError :
        print("Masukkan angka yang Benar")

    else : 
        print("Lakukan login ulang")

print("Terima Kasih")


<img width="458" alt="SS output konverter" src="https://github.com/faturraflin/Readme.md/assets/100887527/e365d9a7-05ed-4ecc-a0ad-2be6ed7f8393">


![WhatsApp Image 2023-09-26 at 05 57 26](https://github.com/faturraflin/Readme.md/assets/100887527/b521f00c-ebc9-4697-8f3f-e999222a1683)
