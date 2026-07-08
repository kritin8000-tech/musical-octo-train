# musical-octo-train
print("*")
print("**")
print("***")
print("****")
print("*****")
print("******")
print("*******")


name=input()
print('Привет,',name)


a=input()
b=input()
c=input()
print(a)
print(b)
print(c)



num1 = 2 + 3 * 4
num2 = (2 + 3) * 4

print(num1)
print(num2)


x = 3 
y = 4 
z = x + y 
z = z + 1 
x = y 
y = 5
x = z + y + 7

print(x)


monitor = int(input())
comp = int(input())
maus = int(input())
kay = int(input())
print((monitor+comp+maus+kay)*3)


a = int(input())
b = int(input())
print((3*(a+b)**3)+(275*(b**2))-(127*a)-41)



a = int(input())
b = a + 1
c = a - 1
print("Следующее за числом", a, "число:", b)
print("Для числа", a, "предыдущее число:", c)





b1 = int(input())
q = int(input())
n = int(input())
print((q**(n-1))*b1)




num = int(input())
c = num%10
b = (num%100)//10
a = (num%1000)//100
print(a, b, c, sep='')
print(a, c, b, sep='')
print(b, a, c, sep='')
print(b, c, a, sep='')
print(c, a, b, sep='')
print(c, b, a, sep='')



num=int(input())
d = num%10
c = (num%100)//10
b = (num%1000)//100
a = (num%10000)//1000
print('Цифра в позиции тысяч равна', a)
print('Цифра в позиции сотен равна', b)
print('Цифра в позиции десятков равна', c)
print('Цифра в позиции единиц равна', d)



a = int(input())
b = int(input())
c = int(input())
if ( b - a) + b == c:
    print('YES')
else:
    print('NO')


num = int(input())
a1 = (num % 10000) // 1000 
a2 = (num % 1000) // 100 
a3 = (num % 100) // 10 
a4 = num % 10 
if ( a1 + a4 ) == ( a2 - a3 ):
    print('ДА')
else:
    print('НЕТ')
    
