# 🐍 Python Basic Programs

A beginner-friendly collection of 20 important Python programs with:

📖 Simple Hindi/Hinglish explanation
💻 Python source code
🔄 Flow diagrams
🧠 Logic explanation
🎤 Viva answers
📝 Example outputs

Ye project beginners, school/college practicals, assignments aur Python viva preparation ke liye banaya gaya hai.

📚 Programs List
No.	Program	Main Concept
01	Addition	Arithmetic
02	Subtraction	Arithmetic
03	Multiplication	Arithmetic
04	Division	Arithmetic
05	Even or Odd	Modulus
06	Positive, Negative or Zero	Conditions
07	Largest of Three Numbers	Comparison
08	Prime Number	Loop
09	Factorial	Loop
10	Multiplication Table	Loop
11	Reverse Number	While Loop
12	Palindrome Number	Number Logic
13	Sum of Digits	Number Logic
14	Fibonacci Series	Loop
15	Armstrong Number	Power/Loop
16	Swap Two Numbers	Variables
17	Leap Year	Conditions
18	Count Digits	While Loop
19	Maximum in a List	List/Loop
20	Count Vowels	String/Loop
📁 Project Structure
python-basic-programs/
│
├── README.md
│
├── 01_addition.py
├── 02_subtraction.py
├── 03_multiplication.py
├── 04_division.py
├── 05_even_odd.py
├── 06_positive_negative.py
├── 07_largest_three.py
├── 08_prime_number.py
├── 09_factorial.py
├── 10_multiplication_table.py
├── 11_reverse_number.py
├── 12_palindrome.py
├── 13_sum_digits.py
├── 14_fibonacci.py
├── 15_armstrong.py
├── 16_swap_numbers.py
├── 17_leap_year.py
├── 18_count_digits.py
├── 19_maximum_list.py
└── 20_count_vowels.py

🐍 Basic Python Concepts
input()

User se input lene ke liye input() function use hota hai.

name = input("Enter your name: ")

print()

Output screen par display karne ke liye print() use hota hai.

print("Hello Python")

int()

Input ko integer number mein convert karne ke liye.

age = int(input("Enter age: "))

float()

Decimal number ke liye float() use hota hai.

price = float(input("Enter price: "))

if, elif, else

Conditions check karne ke liye use hote hain.

if age >= 18:
    print("Adult")
else:
    print("Minor")

for Loop

Kisi kaam ko fixed number of times repeat karne ke liye.

for i in range(1, 6):
    print(i)

while Loop

Jab tak condition true ho, tab tak loop chalta hai.

while n > 0:
    print(n)
    n = n - 1

1️⃣ Addition of Two Numbers
📖 Kya hai?

Do numbers ko add karke total nikalna addition kehlata hai.

Example:

10 + 20 = 30

🔄 Flow Diagram
[Start]
/Enter A and B/
Sum = A + B
/Print Sum/
[End]
💻 Code
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sum = a + b

print("Addition =", sum)

🧠 Explanation

a aur b mein do numbers store hote hain.

+ operator dono numbers ko add karta hai.

Result sum variable mein store hota hai.

📝 Example Output
Enter first number: 10
Enter second number: 20
Addition = 30

🎤 Viva

Addition mein do numbers ko plus + operator ki help se add kiya jata hai.

2️⃣ Subtraction of Two Numbers
📖 Kya hai?

Ek number mein se doosra number minus karna subtraction kehlata hai.

Example:

20 - 10 = 10

🔄 Flow Diagram
[Start]
/Enter A and B/
Result = A - B
/Print Result/
[End]
💻 Code
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sub = a - b

print("Subtraction =", sub)

🧠 Explanation

- subtraction operator hai.

a - b se b ko a se minus kiya jata hai.

🎤 Viva

Subtraction mein minus - operator ka use karke ek number mein se doosra number subtract karte hain.

3️⃣ Multiplication of Two Numbers
📖 Kya hai?

Do numbers ko multiply karna multiplication kehlata hai.

Example:

5 × 4 = 20

🔄 Flow Diagram
[Start]
/Enter A and B/
Result = A * B
/Print Result/
[End]
💻 Code
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

mul = a * b

print("Multiplication =", mul)

🧠 Explanation

Python mein multiplication ke liye * operator use hota hai.

🎤 Viva

Multiplication ke liye Python mein * operator use hota hai.

4️⃣ Division of Two Numbers
📖 Kya hai?

Ek number ko doosre number se divide karna division kehlata hai.

Example:

10 / 2 = 5

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter A and B/]
    B --> C{B == 0?}
    C -- Yes --> D[/Cannot Divide by Zero/]
    C -- No --> E[Result = A / B]
    E --> F[/Print Result/]
    D --> G([End])
    F --> G

💻 Code
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

if b != 0:
    print("Division =", a / b)
else:
    print("Cannot divide by zero")

🧠 Explanation

Division ke liye / operator use hota hai.

Zero se division possible nahi hota, isliye pehle check kiya gaya hai ki b zero nahi hai.

🎤 Viva

Division ke liye / operator use hota hai. Zero se kisi number ko divide nahi kar sakte.

5️⃣ Even or Odd
📖 Kya hai?

Jo number 2 se completely divisible ho, woh even number hota hai.

Examples:

2, 4, 6, 8, 10


Jo number 2 se completely divisible nahi ho, woh odd number hota hai.

Examples:

1, 3, 5, 7, 9

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter Number/]
    B --> C{Number % 2 == 0?}
    C -- Yes --> D[/Even Number/]
    C -- No --> E[/Odd Number/]
    D --> F([End])
    E --> F

💻 Code
n = int(input("Enter a number: "))

if n % 2 == 0:
    print("Even number")
else:
    print("Odd number")

🧠 Explanation

% modulus operator remainder deta hai.

Agar:

number % 2 == 0


to number even hai.

Otherwise number odd hai.

🎤 Viva

Even number 2 se completely divisible hota hai aur odd number 2 se completely divisible nahi hota. Hum % modulus operator se remainder check karte hain.

6️⃣ Positive, Negative or Zero
📖 Kya hai?
0 se bada number → Positive
0 se chhota number → Negative
0 ke equal → Zero
🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter Number/]
    B --> C{Number > 0?}
    C -- Yes --> D[/Positive/]
    C -- No --> E{Number < 0?}
    E -- Yes --> F[/Negative/]
    E -- No --> G[/Zero/]
    D --> H([End])
    F --> H
    G --> H

💻 Code
n = int(input("Enter a number: "))

if n > 0:
    print("Positive")
elif n < 0:
    print("Negative")
else:
    print("Zero")

🧠 Explanation

Pehle n > 0 check hota hai.

Agar false hai to n < 0 check hota hai.

Agar dono false hain, to number zero hai.

🎤 Viva

Is program mein if-elif-else statement ki help se number positive, negative ya zero check karte hain.

7️⃣ Largest of Three Numbers
📖 Kya hai?

Teen numbers mein se sabse bada number find karna.

Example:

10, 25, 15

Largest = 25

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter A B C/]
    B --> C{A >= B and A >= C?}
    C -- Yes --> D[/A is Largest/]
    C -- No --> E{B >= A and B >= C?}
    E -- Yes --> F[/B is Largest/]
    E -- No --> G[/C is Largest/]
    D --> H([End])
    F --> H
    G --> H

💻 Code
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print("Largest =", a)
elif b >= a and b >= c:
    print("Largest =", b)
else:
    print("Largest =", c)

🧠 Explanation

Program teen numbers ko compare karta hai.

and ka matlab hai dono conditions true honi chahiye.

🎤 Viva

Is program mein comparison operators aur if-elif-else ka use karke teen numbers mein se largest number find karte hain.

8️⃣ Prime Number
📖 Kya hai?

Prime number woh number hota hai jo sirf 1 aur khud se divisible hota hai.

Examples:

2, 3, 5, 7, 11


4 prime nahi hai kyunki 4 ko 2 se bhi divide kar sakte hain.

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter N/]
    B --> C{N <= 1?}
    C -- Yes --> D[/Not Prime/]
    C -- No --> E[Check divisibility]
    E --> F{Divisible?}
    F -- Yes --> G[/Not Prime/]
    F -- No --> H[/Prime/]
    D --> I([End])
    G --> I
    H --> I

💻 Code
n = int(input("Enter a number: "))

if n <= 1:
    print("Not a prime number")
else:
    prime = True

    for i in range(2, n):
        if n % i == 0:
            prime = False
            break

    if prime:
        print("Prime number")
    else:
        print("Not a prime number")

🧠 Explanation

for loop 2 se n-1 tak numbers check karta hai.

Agar kisi number se completely divide ho gaya, to number prime nahi hai.

break loop ko stop kar deta hai.

🎤 Viva

Prime number sirf 1 aur khud se divisible hota hai. Is program mein for loop aur modulus operator ka use kiya hai.

9️⃣ Factorial
📖 Kya hai?

Kisi number se lekar 1 tak sabhi numbers ko multiply karna factorial kehlata hai.

Example:

5! = 5 × 4 × 3 × 2 × 1
   = 120

🔄 Flow Diagram
[Start]
/Enter N/
Fact = 1
Loop from 1 to N
Fact = Fact * i
/Print Factorial/
[End]
💻 Code
n = int(input("Enter a number: "))

fact = 1

for i in range(1, n + 1):
    fact = fact * i

print("Factorial =", fact)

🧠 Explanation

fact ki initial value 1 hoti hai.

Loop mein har number ko fact ke saath multiply kiya jata hai.

🎤 Viva

Factorial mein given number se 1 tak ke numbers ko multiply kiya jata hai. Iske liye for loop use kiya hai.

🔟 Multiplication Table
📖 Kya hai?

Kisi number ka multiplication table print karna.

Example:

5 × 1 = 5
5 × 2 = 10
5 × 3 = 15
...
5 × 10 = 50

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter N/]
    B --> C[Set i = 1]
    C --> D{i <= 10?}
    D -- Yes --> E[/Print N * i/]
    E --> F[i = i + 1]
    F --> D
    D -- No --> G([End])

💻 Code
n = int(input("Enter a number: "))

for i in range(1, 11):
    print(n, "x", i, "=", n * i)

🧠 Explanation

range(1, 11) ka matlab 1 se 10 tak.

Har iteration mein n * i calculate hota hai.

🎤 Viva

Is program mein for loop ka use karke given number ka 1 se 10 tak multiplication table print karte hain.

1️⃣1️⃣ Reverse a Number
📖 Kya hai?

Number ke digits ko ulta karna reverse number kehlata hai.

Example:

1234 → 4321

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter N/]
    B --> C[Reverse = 0]
    C --> D{N > 0?}
    D -- Yes --> E[Digit = N % 10]
    E --> F[Reverse = Reverse * 10 + Digit]
    F --> G[N = N // 10]
    G --> D
    D -- No --> H[/Print Reverse/]
    H --> I([End])

💻 Code
n = int(input("Enter a number: "))

reverse = 0

while n > 0:
    digit = n % 10
    reverse = reverse * 10 + digit
    n = n // 10

print("Reverse =", reverse)

🧠 Explanation

% 10 se last digit nikalta hai.

// 10 se last digit remove hota hai.

reverse * 10 + digit reverse number banata hai.

🎤 Viva

Is program mein % 10 se last digit nikalte hain aur // 10 se last digit remove karte hain.

1️⃣2️⃣ Palindrome Number
📖 Kya hai?

Jo number reverse karne ke baad bhi same rahe, use palindrome number kehte hain.

Examples:

121 → 121 ✅
1331 → 1331 ✅
123 → 321 ❌

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter N/]
    B --> C[Store Original]
    C --> D[Find Reverse]
    D --> E{Original == Reverse?}
    E -- Yes --> F[/Palindrome/]
    E -- No --> G[/Not Palindrome/]
    F --> H([End])
    G --> H

💻 Code
n = int(input("Enter a number: "))

original = n
reverse = 0

while n > 0:
    digit = n % 10
    reverse = reverse * 10 + digit
    n = n // 10

if original == reverse:
    print("Palindrome")
else:
    print("Not Palindrome")

🧠 Explanation

Pehle original number store kiya jata hai.

Phir uska reverse nikala jata hai.

Finally original aur reverse compare hote hain.

🎤 Viva

Palindrome number reverse karne ke baad bhi same rehta hai. Hum original aur reverse number ko compare karte hain.

1️⃣3️⃣ Sum of Digits
📖 Kya hai?

Number ke sabhi digits ko add karna sum of digits kehlata hai.

Example:

1234

1 + 2 + 3 + 4 = 10

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter N/]
    B --> C[Sum = 0]
    C --> D{N > 0?}
    D -- Yes --> E[Digit = N % 10]
    E --> F[Sum = Sum + Digit]
    F --> G[N = N // 10]
    G --> D
    D -- No --> H[/Print Sum/]
    H --> I([End])

💻 Code
n = int(input("Enter a number: "))

sum = 0

while n > 0:
    digit = n % 10
    sum = sum + digit
    n = n // 10

print("Sum of digits =", sum)

🧠 Explanation

Har baar % 10 se last digit nikalta hai.

Us digit ko sum mein add karte hain.

// 10 se last digit remove karte hain.

🎤 Viva

Is program mein number ke har digit ko extract karke sum variable mein add kiya jata hai.

1️⃣4️⃣ Fibonacci Series
📖 Kya hai?

Fibonacci series mein next number previous two numbers ka sum hota hai.

Example:

0 1 1 2 3 5 8 13


Example calculation:

0 + 1 = 1
1 + 1 = 2
1 + 2 = 3
2 + 3 = 5

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter Number of Terms/]
    B --> C[Set A = 0, B = 1]
    C --> D[Print A]
    D --> E[Next = A + B]
    E --> F[A = B, B = Next]
    F --> G{More Terms?}
    G -- Yes --> D
    G -- No --> H([End])

💻 Code
n = int(input("Enter number of terms: "))

a = 0
b = 1

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b

🧠 Explanation

Starting values:

a = 0
b = 1


Next value a + b se calculate hoti hai.

🎤 Viva

Fibonacci series mein har next term previous two terms ka sum hoti hai.

1️⃣5️⃣ Armstrong Number
📖 Kya hai?

Armstrong number mein har digit ki power total number of digits ke equal hoti hai aur unka sum original number ke equal hota hai.

Example:

153


Calculation:

1³ + 5³ + 3³
= 1 + 125 + 27
= 153


Isliye 153 Armstrong number hai.

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter N/]
    B --> C[Count Digits]
    C --> D[Extract Digit]
    D --> E[Add Digit ^ Digits]
    E --> F{More Digits?}
    F -- Yes --> D
    F -- No --> G{Total == Original?}
    G -- Yes --> H[/Armstrong/]
    G -- No --> I[/Not Armstrong/]
    H --> J([End])
    I --> J

💻 Code
n = int(input("Enter a number: "))

original = n
digits = len(str(n))
total = 0

while n > 0:
    digit = n % 10
    total = total + digit ** digits
    n = n // 10

if total == original:
    print("Armstrong number")
else:
    print("Not an Armstrong number")

🧠 Explanation
len(str(n)) digits count karta hai.
% 10 se digit nikalta hai.
** power calculate karta hai.
Total ko original number se compare kiya jata hai.
🎤 Viva

Armstrong number mein har digit ki power total digits ke equal hoti hai. Powers ka sum original number ke equal ho to number Armstrong hota hai.

1️⃣6️⃣ Swap Two Numbers
📖 Kya hai?

Do variables ki values exchange karna swapping kehlata hai.

Example:

Before:
a = 10
b = 20

After:
a = 20
b = 10

🔄 Flow Diagram
[Start]
/Enter A and B/
Swap A and B
/Print A and B/
[End]
💻 Code
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

a, b = b, a

print("After swapping:")
print("a =", a)
print("b =", b)

🧠 Explanation

Python mein:

a, b = b, a


se bina third variable ke values exchange ho jaati hain.

🎤 Viva

Swapping ka matlab do variables ki values exchange karna hai. Python mein multiple assignment ki help se direct swapping kar sakte hain.

1️⃣7️⃣ Leap Year
📖 Kya hai?

Leap year mein February ke 29 days hote hain.

Example:

2024 → Leap Year
2025 → Not Leap Year

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter Year/]
    B --> C{Year % 400 == 0?}
    C -- Yes --> D[/Leap Year/]
    C -- No --> E{Year % 4 == 0 and Year % 100 != 0?}
    E -- Yes --> D
    E -- No --> F[/Not Leap Year/]
    D --> G([End])
    F --> G

💻 Code
year = int(input("Enter year: "))

if year % 400 == 0 or (year % 4 == 0 and year % 100 != 0):
    print("Leap year")
else:
    print("Not a leap year")

🧠 Explanation

Leap year check karne ke liye divisibility conditions use hoti hain.

400 se divisible → Leap Year
Ya 4 se divisible aur 100 se divisible nahi → Leap Year
🎤 Viva

Leap year mein February ke 29 days hote hain. Is program mein modulus operator se year ki divisibility check karte hain.

1️⃣8️⃣ Count Digits
📖 Kya hai?

Kisi number mein total kitne digits hain, ye find karna.

Example:

12345 → 5 digits

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter N/]
    B --> C[Count = 0]
    C --> D{N > 0?}
    D -- Yes --> E[N = N // 10]
    E --> F[Count = Count + 1]
    F --> D
    D -- No --> G[/Print Count/]
    G --> H([End])

💻 Code
n = int(input("Enter a number: "))

count = 0

while n > 0:
    n = n // 10
    count = count + 1

print("Number of digits =", count)

🧠 Explanation

Har baar:

n // 10


karne se ek digit remove hota hai.

Har removal par count one se increase hota hai.

🎤 Viva

Is program mein // 10 se ek-ek digit remove karke total digits count karte hain.

1️⃣9️⃣ Maximum Number in a List
📖 Kya hai?

List mein se sabse bada number find karna.

Example:

[10, 25, 7, 45, 18]

Maximum = 45

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[Create List]
    B --> C[Maximum = First Element]
    C --> D[Take Next Element]
    D --> E{Element > Maximum?}
    E -- Yes --> F[Maximum = Element]
    E -- No --> G[Continue]
    F --> G
    G --> H{More Elements?}
    H -- Yes --> D
    H -- No --> I[/Print Maximum/]
    I --> J([End])

💻 Code
numbers = [10, 25, 7, 45, 18]

maximum = numbers[0]

for num in numbers:
    if num > maximum:
        maximum = num

print("Maximum =", maximum)

🧠 Explanation

Pehle list ka first element maximum maana jata hai.

Phir baaki elements compare kiye jate hain.

Agar koi number current maximum se bada hai, to maximum update hota hai.

🎤 Viva

Is program mein list ke first element ko maximum maan kar baaki elements ke saath compare karte hain.

2️⃣0️⃣ Count Vowels in a String
📖 Kya hai?

String mein total vowels count karna.

Vowels:

a, e, i, o, u


Example:

Hello

Vowels = e, o

Count = 2

🔄 Flow Diagram
flowchart TD
    A([Start]) --> B[/Enter String/]
    B --> C[Count = 0]
    C --> D[Take Character]
    D --> E{Character is Vowel?}
    E -- Yes --> F[Count = Count + 1]
    E -- No --> G[Continue]
    F --> G
    G --> H{More Characters?}
    H -- Yes --> D
    H -- No --> I[/Print Count/]
    I --> J([End])

💻 Code
text = input("Enter a string: ")

count = 0

for ch in text:
    if ch.lower() in "aeiou":
        count = count + 1

print("Number of vowels =", count)

🧠 Explanation

for loop string ke har character ko check karta hai.

lower() character ko lowercase mein convert karta hai.

Agar character aeiou mein hai, to count increase hota hai.

🎤 Viva

Is program mein string ke har character ko check karte hain. Agar character vowel hai to count ko one se increase karte hain.

🧮 Important Python Operators
Arithmetic Operators
Operator	Meaning	Example
+	Addition	5 + 2
-	Subtraction	5 - 2
*	Multiplication	5 * 2
/	Division	5 / 2
%	Remainder	5 % 2
//	Floor Division	5 // 2
**	Power	5 ** 2
🔍 Comparison Operators
Operator	Meaning
==	Equal
!=	Not Equal
>	Greater Than
<	Less Than
>=	Greater Than or Equal
<=	Less Than or Equal
🧠 Logical Operators
Operator	Meaning
and	Dono conditions true
or	Koi ek condition true
not	Condition ko reverse karta hai

Example:

age = 20

if age >= 18 and age <= 60:
    print("Eligible")

🔁 Loops
For Loop

Jab repeat count pata ho tab for loop use karna convenient hota hai.

for i in range(1, 6):
    print(i)


Output:

1
2
3
4
5

While Loop

Jab condition ke basis par repeat karna ho.

n = 5

while n > 0:
    print(n)
    n = n - 1


Output:

5
4
3
2
1

🎤 Important Viva Questions
Q1. Python kya hai?

Answer:

Python ek high-level, interpreted aur beginner-friendly programming language hai.

Q2. Python mein comment kaise likhte hain?

Answer:

# symbol ka use karke.

# This is a comment

Q3. % operator kya karta hai?

Answer:

% modulus operator hai. Ye division ke baad remainder return karta hai.

Example:

10 % 3


Output:

1

Q4. // kya karta hai?

Answer:

// floor division operator hai. Ye floor/integer result deta hai.

Example:

10 // 3


Output:

3

Q5. break kya karta hai?

Answer:

break loop ko immediately stop kar deta hai.

Q6. if-else kya hai?

Answer:

if-else ka use condition ke basis par decision lene ke liye hota hai.

Q7. List kya hoti hai?

Answer:

List Python mein multiple values ko ek single variable mein store karne ke liye use hoti hai.

Example:

numbers = [10, 20, 30, 40]

🏆 Quick Revision
Addition       → +
Subtraction    → -
Multiplication → *
Division       → /
Even/Odd       → %
Prime          → for + %
Factorial      → for loop
Table          → for loo
