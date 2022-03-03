# SAMPLE-CODES-IN-PYTHON
**A simple code example for calculating factorial**
```sql
print("""
****************************
  FACTORIAL FINDING PROGRAM

Press 'q' to exit.

****************************
""")

while True:
     number = input("number:")

     if (number == "q"):
         print("The program is terminating.")
         break

     else:
         number = int(number)

         factorial = 1

         for i in range(2,number+1):
             print("factorial",factorial,"i",i)
             factorial*=i
         print("factorial",factorial)
```
**Example of code that prints part of the fibonacci sequence to calculate the golden ratio**
```sql
a=1
b=1

fibonacci= [a,b]

for i in range(10):
    a, b = b, a + b
    print("a:", a, "b:", b)
    fibonacci.append(b)

print(fibonacci)
```
**A basic code for user login program**
```sql
print("""
*******************
USER LOGIN PROGRAM
*******************
""")

sys_user_name="tuyan"

sys_password="12345"
login_right=3

while True:
     username = input("username:")
     password = input("password:")
     if(user_name != sys_user_name and password == sys_password):
         print("The username is incorrect.")
         entry_right-=1
     elif (user_name == sys_user_name and password != sys_password):
         print("Password is incorrect.")
         entry_right-=1
     elif (user_name != sys_user_name and password != sys_password):
         print("The username and password are incorrect.")
         entry_right-=1
     else:
         print("Successfully logged in.")
         break

     if (login_right==0):
         print("Your login has expired.")
         break
 ```
 **A turtle race for fun :)**
 ```sql
import turtle
import random
wn=turtle.Screen()
wn.bgcolor("lightblue")

A=turtle.Turtle()
B=turtle.Turtle()
C=turtle.Turtle()

A.shape("turtle")
B.shape("turtle")
C.shape("turtle")
A.color("red")
B.color("blue")
C.color("green")

A.up()
B.up()
C.up()
A.goto(-100,20)
B.goto(-100,-20)
C.goto(-100,60)
A.speed(1)
B.speed(1)
C.speed(1)

for i in range(100):
    a = random.randrange(100)
    A.forward(a)
    b = random.randrange(100)
    B.forward(b)
    c = random.randrange(100)
    C.forward(c)
wn.exitonclick()
```
**The code I wrote to find out if the number received from the user is a prime number**
```sql
def prime_mi(number):
     if (number==1):
         return False
     elif (number ==2 ):
         return True
     else:
         for i in range(2,number):
             if ( number %i == 0):
                 return False
         return True
while True:
     number = input("number:")

     if (number== "q"):
         break
     else:
         number = int(number)

         if (prime_is(number)):
             print(number is a "prime number")
         else:
             print(number, "not a prime number.")
while range(1,10001):
     for i in range(2,number):

         if (number % i== 0):
             full_bolens.append(i)
             if full_bolens%2!=0:
                 count=0
                 count+=1
         for i in range(2, number1):

             if (number1 %i == 0):
                 full_bolens.append(i)
                 if full_bolens % 2 != 0:
                     count1 = 0
                     count1+= 1
     if count==count1 :
         print(number,number1,"are bff")
 ```
**A game of guessing a randomly chosen number between 1 and 100**
```sql
import random
import time

print("""*****************
number guessing game

Guess the number between 1 and 100.
***************

""")

random_num= random.randint(1,100)
guess_right=7

while True:
     guess= int(input("enter your guess:"))
     if (guess<random_number):
         print("querying information.")
         time.sleep(1)

         print("say a higher number")

         guess_right-=1
     elif (guess > random_number):
         print("querying information....")
         time.sleep(1)

         print("say a smaller number")

         guess_right -=1

     else:
         print("querying information...")
         time.sleep(1)
         print("congratulations",random_number)
         break
     if(guess_right==0):
         print("Your guessed..")
         print(random_number,"program terminating...")
         break

```
