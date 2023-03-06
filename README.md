# simple-calculator-in-python
print("calculator\n")
print("Enter choice\n1.add\n2.sub\n3.multiply\n4.divide\n5.exponent")
a=int(input("enter first number:"))
b=int(input("enter second number:"))
c=int(input("Enter choice :"))
if(c==1):
    print(a+b)
elif(c==2):
     print(a-b)
elif(c==3):
     print(a*b)
elif(c==4):
     print( "quetiont is",a//b,"remainder is",a%b)
elif(c==5):
     print(a**b)
else:
    print("Wrong choice")
