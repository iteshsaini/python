# python
#vary easy calculator using python without defining or while use 

str=("Calculator")
print(str)

A=float(input("Enter tha first number = "))
B=float(input("Enter tha second number = "))
select = input("Choose one symbole (+,-,*,/):\n")

if select == "+":
 result = A+B
 print("The addition of two number is ",result)

elif select == "*":
 result = A*B
 print("The Multiplication of two number is ",result)
 
elif select == "-":
 result = A-B
 print("The Subtraction of two number is ",result)
 
elif select == "/":
   if B == 0:
      print("It can't divided by zero ")
      
   else:
        result = A/B
        print("The Division of two number is ",result)
else:
    print("##INVALID OPERATOR##")

 
