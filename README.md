a=[ i for i in range(2000,3201) if i%7==0 and i%5!=0]
print(*a, sep=',')



num = int(input("enter a number whose factorial isto be found: "))
factorial = 1 
if num < 0:
    print("factorialdoes not exit for native numbers")
elif num ==0:
    print("the factorial of 0o is 1")
else:
    for i in range(1,num +1):
        factorial = factorial*i
    print("the factorial of",num,"is",factorial)

    

number = int(input("Type a number:"))

numberDict = {}
for i in range(1,number+1):
    numberDict[i] = i*i 

print(numberDict)



a=input('enter first string :')
b=input('entre second string ;')
if len(a)>len(b):
    print (a)
elif len(b)>len(a):
    print(b)
else:
    print()




l=int(input("enter the limit :"))
d = dict()
for x in range (1,l+1):
    d[x]=x**2
    print(d)




def printram():
    l = list()
    for i in range(1, 21):
        l.append(i**2)
    print(l)
    
printram()




 def circle():
    l = list()
    for i in range (1, 20):
        l.append(i**2)
    print(l[:5])
    
circle()



c=float(input('enter value in celsius:'))
f=c*(9/5)+55
print('The value in fahrenheit is', f)




my_numbers = [7, 2, 4, 11, 19, 24, 66, 1, 42, 22, 37, 5, 3, 92, 73]

user_input = input("Please enter a string (even/odd): ").lower()

if user_input == "even":
    print("Even numbers from the list are:", [num for num in my_numbers if num % 2 == 0])
elif user_input == "odd":
    print("Odd numbers from the list are:", [num for num in my_numbers if num % 2 != 0])
else:
    print("Unknown Input!")








x=1
for i in range(1,20):
    if i%3==0 and i%5!=0:
        print("Buzz")
    elif i%5==0 and i%3!=0:
        print("fizz")
    elif i%3==0 and i%5==0:
        print("buzz fizz")
    else:
        print(i)




