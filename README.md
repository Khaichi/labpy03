# labpy03
# LATIHAN 1

![](https://github.com/Khaichi/labpy03/blob/master/gambarcodinglatihan1.png)

Codingan
```print('==== Bilangan Acak yang lebih kecil dari 0.5 ====')
print(' ')
import random
N = int(input("Masukan nilai N : "))
a = 0
for x in range(N):
    a += 1
    b = random.uniform(.0,.5)
    print('Data ke:',a,'==>',b)
print('Selesai')
print(' ')
jawab = 'lanjutkan'
hitung = 0
while jawab == "lanjutkan":
    hitung += 1
    jawab = input('Ingin Mengulang ? (yes/no) : ')
    if jawab == "Lanjutkan":
        break
print('Total perulangan : ' + str (hitung))

# Latihan2
