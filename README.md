# program kasir jika mendapatkan diskon

jumlah = int (input("Masukkan total harga pembelian: "))

if (jumlah >= 100000) and (jumlah<200000):
    A = jumlah*10/100
    print ("kamu Mendapatkan Diskon Sebesar 10 persen =", int(A))
elif (jumlah >= 200000) and (jumlah <= 500000):
    A = jumlah*15/100
    print ("kamu Mendapatkan Diskon Sebesar 15 persen =", int(A))
elif jumlah >= 500000:
    A = jumlah*25/100
    print ("kamu Mendapatkan Diskon Sebesar 25 persen =", int(A))
else:
    A = jumlah*0
    print ("kamu Tidak Mendapatkan Diskon =", int(A))
B = jumlah-A
print ("jumlah yang harus dibayar =", int(B))
