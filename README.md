import random

caracteres = ("+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890")

longitud = int(input("Introdusca la longitud de su contraseña"))

contraseña = ""

for i in range(longitud):
    contraseña += random.choice(caracteres)
print(contraseña)
