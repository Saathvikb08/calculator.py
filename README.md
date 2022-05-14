# calculator.py
print ("addition") 

def add_numbers(n1,n2):

    result1=n1+n2

    return result1

number1=int(input ("Enter the first number: "))

number2=int(input ("Enter the second number: "))

result1=add_numbers(number1, number2)

print(number1,"+", number2,"=", result1)

print("subtraction")

def sub_numbers(n3,n4):

    result2=n3-n4

    return result2

number3=int(input ("Enter the first number: "))

number4=int(input ("Enter the second number: "))

result2=sub_numbers(number3,number4)

print(number3,"-", number4,"=", result2)

print ("multiplication")

def mult_numbers(n5,n6):

    result3=n5*n6

    return result3

number5=int(input ("Enter the first number: "))

number6=int(input ("Enter the second number: "))

result3=mult_numbers(number5, number6)

print (number5,"×",number6,"=", result3)

print("Division")

def div_numbers(d1,d2):

    result4=d1/d2

    return result4

dividend=int(input ("Enter the dividend number: "))

divisor=int(input ("Enter the divisor number: "))

result4=div_numbers(dividend, divisor)

print(dividend,"÷",divisor,"=", result4)


