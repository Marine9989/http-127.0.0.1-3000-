# http-127.0.0.1-3000-


a = int(input("Պարզ թիվ "))
k = 0
for i in (2, a // 2+1):
    if (a % i == 0):
        k = k+1
if (k <= 0):
    print("Պարզ է")
else:
    print("Պարզ չէ")
