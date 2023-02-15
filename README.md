# KOro
15.02/2023
Задание 1
a, b, c = int(input()), int(input()), int(input())
if a > b:
    print(a) if a > c else print(c)
else:
    print(b) if b > c else print(c)
 Задание 3
 n = input()
34568
print(len(n))
Задание 4
a = int(input())
b = int(input())

while a !=0 and b !=0:
    if a > b:
        
        else:
            b = b % a
            
gsd = a + b
print(gsd)
Задание 5
a, b = 7, 5
i = min(a, b)
while True:
    if i%a==0 and i%b==0:
        break
    i += 1
print(i)
