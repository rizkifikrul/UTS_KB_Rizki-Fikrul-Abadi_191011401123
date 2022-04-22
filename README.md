# UTS_KB_Rizki-Fikrul-Abadi_191011401123
UTS_KB_Rizki Fikrul Abadi_191011401123
#Nama :Rizki Fikrul Abadi 
#NIM : 191011401123
#LOOPING

#Ini Contoh Looping di Python secara umum dari list array
print("Ini Contoh Looping di Python secara umum dari list array")
nama_mobil = ["toyota", "honda", "mercedes"]
for x in nama_mobil:
  print(x)

print("\n")

#Fungsi range() mengembalikan urutan angka, mulai dari 0 secara default, dan bertambah 1 (secara default), dan berakhir pada nomor tertentu
print("Ini Contoh Hasil Looping dengan Fungsi Range()")
for x in range(4):
    print(x)

print("\n")

#Fungsi range() default ke 0 sebagai nilai awal, namun dimungkinkan untuk menentukan nilai awal dengan menambahkan parameter: range(2, 6), yang berarti nilai dari 2 hingga 6 (tetapi tidak termasuk 6):
print("Ini Contoh Hasil Looping dengan Fungsi Range() dengan 2 parameter")
for x in range(2, 6):
  print(x)

print("\n")

#Fungsi range() default untuk meningkatkan urutan dengan 1, namun dimungkinkan untuk menentukan nilai kenaikan dengan menambahkan parameter ketiga: range(2, 30, 3):
print("Ini Contoh Hasil Looping dengan Fungsi Range() dengan 3 parameter")
for x in range(2, 30, 3):
  print(x)

print("\n")

#Loop bersarang 
#Looping bersarang adalah loop di dalam loop. "Loop dalam" akan dieksekusi satu kali untuk setiap iterasi "loop luar":
print("Ini Contoh Hasil Looping bersarang")
adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
  for y in fruits:
    print(x, y)

print("\n")

#Ini adalah cara looping dan akan berhenti pada kondisi tertentu, perulangan akan berhenti ketika variabel x berisi kata "oppo"
print("Ini Contoh Hasil Looping dengan break")
hp = ["xiaomi", "oppo", "vivo"]
for x in hp:
  print(x)
  if x == "oppo":
    break
