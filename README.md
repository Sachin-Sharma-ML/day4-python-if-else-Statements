# day4-python-if-else-Statements
 Python if else Statements practice Question code
# if else question
# even or odd

x=int(input("Enter a number :"))
if(x%2==0):
    print(x,"is even number")
else:
    print(x,"is odd number")

# find the  positive and negative number
num=int(input("Enter a number :"))
if num > 0:
    print(num,"is Positive Number")
else:
    print(num,"is Negative Number")
# find the leap year
x=int(input("Enter a year :"))
if (x % 400 == 0) and (x % 100 == 0):
    print(x,"is leap year")
elif (x % 4 == 0) and (x % 100 != 0):
    print(x,"is leap year")
else:
    print(x,"is not leap lear")
    
# find the grade
marks=int(input("Enter a marks :"))
if marks>=90:
    print("O grade")
elif marks>=80:
    print("A grade")
elif marks >=70:
    print("B grade")
elif marks>=50:
    print("C grade")
else:
    print("F grade")

# find the greater and less than value
num=int(input("Enter a number:"))
num_1=int(input("Enter a number:"))
if (num > num_1):
    print(num,"is a greaterthan")
elif (num==num_1):
    print("is equal")
else:
    print(num_1,"is lessthan")

# eligible to vote or not
age=int(input("Enter a age:"))
if age >= 18:
    print("you can give vote")
else:
    print("you can not vote")
# divisible by 5 
x=int(input("Enter a number:"))
if x%5==0:
    print(x,"is Divisible by 5")
else:
    print(x,"is not Divisible by 5")
