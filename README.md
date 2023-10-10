import random

password = []

a = 'abcdefghijklmnopqrstuvwxyz'
b = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
c = '1234567890'
symbol = '!@#&*'

strongpassword = a+c+symbol+b

for i in range(8):
    a = random.choice(strongpassword)
    password.append(a)

for i in range(len(password)):
    a = password[i]

generatedpassword = ''.join(password)
print("Username : Shruti Kule")
print(f"Password {generatedpassword}")
print()
