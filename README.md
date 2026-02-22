name=input('enter the name')
age=int(input('enter your age'))
print("your name is "+name+"and your age is "+str(age))


name=input('enter the name')
print("your name has "+str(len(name))+"character")


name=input('enter the name')
print("your name in upper case ",name.upper())


fname=input('enter the name')
lname=input('enter the name')
print(fname+lname)


num=[1,2,3,4,5,]
print(num)


num=input('enter the numbers')
if len(num) % 2 == 0:
     print("even length")
else:
     print("odd length")#space also counts


num=input('enter the numbers')
number=list(map(int, num.split()))
print(sum(number))


