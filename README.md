# 🐍 Python Basic Programs
A beginner-friendly collection of 20 essential Python programs complete with:
- 📖 Simple Hindi/Hinglish explanations
- 💻 Clean Python source code
- 🔄 Logic flowcharts (Mermaid Diagrams)
- 🧠 Step-by-step logic breakdown
- 🎤 Practical viva Q&A
- 📝 Example inputs & outputs
> **Target Audience:** Beginners, school/college practicals, lab assignments, and Python viva preparation.
---
## 📚 Programs Index

| No. | Program | Main Concept |
| :--- | :--- | :--- |
| 01 | Addition | Arithmetic Operators |
| 02 | Subtraction | Arithmetic Operators |
| 03 | Multiplication | Arithmetic Operators |
| 04 | Division | Arithmetic Operators & Zero Check |
| 05 | Even or Odd | Modulus Operator (`%`) |
| 06 | Positive, Negative or Zero | Conditional Statements (`if-elif-else`) |
| 07 | Largest of Three Numbers | Comparison Operators & Logical `and` |
| 08 | Prime Number | `for` Loop & Divisibility |
| 09 | Factorial | `for` Loop & Accumulator |
| 10 | Multiplication Table | `for` Loop & Iteration |
| 11 | Reverse a Number | `while` Loop, `%` & `//` |
| 12 | Palindrome Number | Number Extraction & Comparison |
| 13 | Sum of Digits | `while` Loop & Modulus |
| 14 | Fibonacci Series | Multiple Variable Assignment |
| 15 | Armstrong Number | Digit Extraction & Power Calculation |
| 16 | Swap Two Numbers | Tuple Unpacking / Direct Assignment |
| 17 | Leap Year | Compound Conditions (`and` / `or`) |
| 18 | Count Digits | Floor Division (`//`) & Counter |
| 19 | Maximum in a List | List Traversal & Linear Search |
| 20 | Count Vowels in a String | String Iteration & Membership Operator (`in`) |

---
## 📁 Project Structure
```text
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
```
---
## 🐍 Basic Python Concepts
* **`input()`**: User se console par string input lene ke liye use hota hai.
  ```python
  name = input("Enter your name: ")
  ```
* **`print()`**: Output screen par display karne ke liye use hota hai.
  ```python
  print("Hello Python")
  ```
* **`int()`**: String ya decimal input ko integer number mein convert karta hai.
  ```python
  age = int(input("Enter age: "))
  ```
* **`float()`**: Decimal values accept ya convert karne ke liye use hota hai.
  ```python
  price = float(input("Enter price: "))
  ```
* **`if, elif, else`**: Decision making aur conditions check karne ke liye use hote hain.
  ```python
  if age >= 18:
      print("Adult")
  else:
      print("Minor")
  ```
* **`for` Loop**: Kisi code block ko fixed number of times repeat karne ke liye.
  ```python
  for i in range(1, 6):
      print(i)
  ```
* **`while` Loop**: Jab tak condition `True` rahe, tab tak loop chalane ke liye.
  ```python
  while n > 0:
      print(n)
      n = n - 1
  ```
---
## 💻 20 Python Programs (Code & Explanation)
### 1️⃣ Addition of Two Numbers
* **📖 Description:** Do numbers ko add karke unka total calculate karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter A and B/]
      B --> C["Sum = A + B"]
      C --> D[/Print Sum/]
      D --> E([End])
  ```
* **💻 Source Code:**
  ```python
  a = int(input("Enter first number: "))
  b = int(input("Enter second number: "))
  sum = a + b
  print("Addition =", sum)
  ```
* **🧠 Explanation:** `+` operator dono input variables `a` aur `b` ko add karke result `sum` mein store karta hai.
* **📝 Example Output:**
  ```text
  Enter first number: 10
  Enter second number: 20
  Addition = 30
  ```
* **🎤 Viva Point:** Addition ke liye Python mein standard arithmetic operator `+` use hota hai.
---
### 2️⃣ Subtraction of Two Numbers
* **📖 Description:** Ek number mein se doosra number minus karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter A and B/]
      B --> C["Result = A - B"]
      C --> D[/Print Result/]
      D --> E([End])
  ```
* **💻 Source Code:**
  ```python
  a = int(input("Enter first number: "))
  b = int(input("Enter second number: "))
  sub = a - b
  print("Subtraction =", sub)
  ```
* **🧠 Explanation:** `-` operator first variable `a` mein se second variable `b` ko subtract karta hai.
* **🎤 Viva Point:** Subtraction arithmetic operator `-` se perform hota hai.
---
### 3️⃣ Multiplication of Two Numbers
* **📖 Description:** Do numbers ka product calculate karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter A and B/]
      B --> C["Result = A * B"]
      C --> D[/Print Result/]
      D --> E([End])
  ```
* **💻 Source Code:**
  ```python
  a = int(input("Enter first number: "))
  b = int(input("Enter second number: "))
  mul = a * b
  print("Multiplication =", mul)
  ```
* **🧠 Explanation:** Python mein multiplication ke liye asterisk `*` operator ka use kiya jata hai.
* **🎤 Viva Point:** `*` operator product calculation ke liye use hota hai.
---
### 4️⃣ Division of Two Numbers
* **📖 Description:** Ek number ko doosre number se divide karna, sath hi zero check lagana.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter A and B/]
      B --> C{"B == 0 ?"}
      C -- Yes --> D[/Cannot Divide by Zero/]
      C -- No --> E["Result = A / B"]
      E --> F[/Print Result/]
      D --> G([End])
      F --> G
  ```
* **💻 Source Code:**
  ```python
  a = float(input("Enter first number: "))
  b = float(input("Enter second number: "))
  if b != 0:
      print("Division =", a / b)
  else:
      print("Cannot divide by zero")
  ```
* **🧠 Explanation:** `/` operator floating-point division deta hai. Zero se divide karne par `ZeroDivisionError` aata hai, isliye conditional check zaroori hai.
* **🎤 Viva Point:** Python mein standard division `/` hamesha float return karta hai.
---
### 5️⃣ Even or Odd
* **📖 Description:** Check karna ki given number even (sam) hai ya odd (visham).
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter Number/]
      B --> C{"Number % 2 == 0 ?"}
      C -- Yes --> D[/Even Number/]
      C -- No --> E[/Odd Number/]
      D --> F([End])
      E --> F
  ```
* **💻 Source Code:**
  ```python
  n = int(input("Enter a number: "))
  if n % 2 == 0:
      print("Even number")
  else:
      print("Odd number")
  ```
* **🧠 Explanation:** Modulus operator `%` remainder return karta hai. Agar `n % 2 == 0` hai, to number completely 2 se divisible hai.
* **🎤 Viva Point:** `%` remainder nikalta hai; even numbers ka remainder 2 se divide karne par `0` hota hai.
---
### 6️⃣ Positive, Negative or Zero
* **📖 Description:** Check karna ki number zero se bada hai, chhota hai ya zero hai.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter Number/]
      B --> C{"Number > 0 ?"}
      C -- Yes --> D[/Positive/]
      C -- No --> E{"Number < 0 ?"}
      E -- Yes --> F[/Negative/]
      E -- No --> G[/Zero/]
      D --> H([End])
      F --> H
      G --> H
  ```
* **💻 Source Code:**
  ```python
  n = int(input("Enter a number: "))
  if n > 0:
      print("Positive")
  elif n < 0:
      print("Negative")
  else:
      print("Zero")
  ```
* **🧠 Explanation:** Multiple conditions ko check karne ke liye `if-elif-else` ladder ka upayog hota hai.
* **🎤 Viva Point:** Multi-way branching ke liye `elif` keyword ka use hota hai.
---
### 7️⃣ Largest of Three Numbers
* **📖 Description:** Teen input numbers mein se sabse bada number find karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter A, B, C/]
      B --> C{"A >= B and A >= C ?"}
      C -- Yes --> D[/A is Largest/]
      C -- No --> E{"B >= A and B >= C ?"}
      E -- Yes --> F[/B is Largest/]
      E -- No --> G[/C is Largest/]
      D --> H([End])
      F --> H
      G --> H
  ```
* **💻 Source Code:**
  ```python
  a = int(input("Enter first number: "))
  b = int(input("Enter second number: "))
  c = int(input("Enter third number: "))
  if a >= b and a >= c:
      print("Largest =", a)
  elif b >= a and b >= c:
      print("Largest =", b)
  else:
      print("Largest =", c)
  ```
* **🧠 Explanation:** `and` operator ensure karta hai ki dono relational sub-conditions simultaneously satisfy hon.
* **🎤 Viva Point:** Comparison operators (`>=`) aur logical `and` ke combination se multiple numbers compare hote hain.
---
### 8️⃣ Prime Number
* **📖 Description:** Check karna ki number prime (avibhājya) hai ya nahi.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter N/]
      B --> C{"N <= 1 ?"}
      C -- Yes --> D[/Not Prime/]
      C -- No --> E["Check Divisibility (2 to N-1)"]
      E --> F{"Any Divisor Found?"}
      F -- Yes --> G[/Not Prime/]
      F -- No --> H[/Prime/]
      D --> I([End])
      G --> I
      H --> I
  ```
* **💻 Source Code:**
  ```python
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
  ```
* **🧠 Explanation:** 2 se lekar $n-1$ tak loop chala kar divisibility check ki jaati hai. Agar koi divisor mil jaye to `break` se loop terminate kar diya jata hai.
* **🎤 Viva Point:** Prime number ke strictly 2 factors hote hain: 1 aur number khud.
---
### 9️⃣ Factorial
* **📖 Description:** Kisi number ka factorial ($n! = n \times (n-1) \times \dots \times 1$) find karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter N/]
      B --> C["Fact = 1"]
      C --> D["Loop 1 to N: Fact = Fact * i"]
      D --> E[/Print Fact/]
      E --> F([End])
  ```
* **💻 Source Code:**
  ```python
  n = int(input("Enter a number: "))
  fact = 1
  for i in range(1, n + 1):
      fact = fact * i
  print("Factorial =", fact)
  ```
* **🧠 Explanation:** `fact` ko 1 se initialize kiya jata hai aur range 1 se $n$ tak iteratively multiply kiya jata hai.
* **🎤 Viva Point:** Factorial loop aur recursion dono se calculate kiya ja sakta hai.
---
### 🔟 Multiplication Table
* **📖 Description:** Kisi bhi given number ka 1 se 10 tak table generate karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter N/]
      B --> C["Set i = 1"]
      C --> D{"i <= 10 ?"}
      D -- Yes --> E[/"Print N * i"/]
      E --> F["i = i + 1"]
      F --> D
      D -- No --> G([End])
  ```
* **💻 Source Code:**
  ```python
  n = int(input("Enter a number: "))
  for i in range(1, 11):
      print(n, "x", i, "=", n * i)
  ```
* **🧠 Explanation:** `range(1, 11)` loop ko 10 bar execute karta hai, jahan har step par $n \times i$ compute hota hai.
* **🎤 Viva Point:** `range(start, stop)` function `stop` value ko include nahi karta (stop - 1 tak chalta hai).
---
### 1️⃣1️⃣ Reverse a Number
* **📖 Description:** Kisi integer ke digits ko reverse order mein arrange karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter N/]
      B --> C["Reverse = 0"]
      C --> D{"N > 0 ?"}
      D -- Yes --> E["Digit = N % 10"]
      E --> F["Reverse = Reverse * 10 + Digit"]
      F --> G["N = N // 10"]
      G --> D
      D -- No --> H[/Print Reverse/]
      H --> I([End])
  ```
* **💻 Source Code:**
  ```python
  n = int(input("Enter a number: "))
  reverse = 0
  while n > 0:
      digit = n % 10
      reverse = reverse * 10 + digit
      n = n // 10
  print("Reverse =", reverse)
  ```
* **🧠 Explanation:** `% 10` se last digit fetch hota hai aur `// 10` se last digit drop ho jata hai.
* **🎤 Viva Point:** `//` floor division operator decimal drop karke pure integer return karta hai.
---
### 1️⃣2️⃣ Palindrome Number
* **📖 Description:** Check karna ki number seedha aur ulta padhne par barabar hai ya nahi.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter N/]
      B --> C["Store Original = N, Find Reverse"]
      C --> D{"Original == Reverse ?"}
      D -- Yes --> E[/Palindrome/]
      D -- No --> F[/Not Palindrome/]
      E --> G([End])
      F --> G
  ```
* **💻 Source Code:**
  ```python
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
  ```
* **🧠 Explanation:** Number ko mutate karne se pehle `original` variable mein preserve kiya jata hai aur generated `reverse` se compare kiya jata hai.
* **🎤 Viva Point:** Agar reverse value original value ke identical ho, toh wo palindrome number kehlata hai.
---
### 1️⃣3️⃣ Sum of Digits
* **📖 Description:** Kisi number ke sabhi individual digits ka sum calculate karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter N/]
      B --> C["Sum = 0"]
      C --> D{"N > 0 ?"}
      D -- Yes --> E["Digit = N % 10"]
      E --> F["Sum = Sum + Digit"]
      F --> G["N = N // 10"]
      G --> D
      D -- No --> H[/Print Sum/]
      H --> I([End])
  ```
* **💻 Source Code:**
  ```python
  n = int(input("Enter a number: "))
  sum = 0
  while n > 0:
      digit = n % 10
      sum = sum + digit
      n = n // 10
  print("Sum of digits =", sum)
  ```
* **🧠 Explanation:** While loop step-by-step single digit extract karke accumulator `sum` mein add karta hai.
* **🎤 Viva Point:** Loop termination condition `n > 0` ensure karti hai ki sare digits process ho chuke hain.
---
### 1️⃣4️⃣ Fibonacci Series
* **📖 Description:** $N$ terms tak Fibonacci sequence generate karna ($0, 1, 1, 2, 3, 5, \dots$).
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter Number of Terms/]
      B --> C["Set A = 0, B = 1"]
      C --> D[/Print A/]
      D --> E["Next = A + B"]
      E --> F["A = B, B = Next"]
      F --> G{"More Terms?"}
      G -- Yes --> D
      G -- No --> H([End])
  ```
* **💻 Source Code:**
  ```python
  n = int(input("Enter number of terms: "))
  a = 0
  b = 1
  for i in range(n):
      print(a, end=" ")
      a, b = b, a + b
  ```
* **🧠 Explanation:** Python ke simultaneous assignment (`a, b = b, a + b`) se previous do terms ka sum automatically update ho jata hai.
* **🎤 Viva Point:** Fibonacci series ka har agla number pichhle do numbers ka addition hota hai.
---
### 1️⃣5️⃣ Armstrong Number
* **📖 Description:** Check karna ki digits ki power ka sum original number ke equal hai ya nahi.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter N/]
      B --> C["Count Digits = D"]
      C --> D["Extract Digit & Add Digit^D to Total"]
      D --> E{"More Digits Left?"}
      E -- Yes --> D
      E -- No --> F{"Total == Original ?"}
      F -- Yes --> G[/Armstrong/]
      F -- No --> H[/Not Armstrong/]
      G --> I([End])
      H --> I
  ```
* **💻 Source Code:**
  ```python
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
  ```
* **🧠 Explanation:** `**` exponentiation operator se digit ki power calculate ki jaati hai jahan exponent = total number of digits.
* **🎤 Viva Point:** Armstrong number example: $153 = 1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153$.
---
### 1️⃣6️⃣ Swap Two Numbers
* **📖 Description:** Do variables ki values ko aapas mein exchange karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter A and B/]
      B --> C["a, b = b, a"]
      C --> D[/Print A and B/]
      D --> E([End])
  ```
* **💻 Source Code:**
  ```python
  a = int(input("Enter first number: "))
  b = int(input("Enter second number: "))
  a, b = b, a
  print("After swapping:")
  print("a =", a)
  print("b =", b)
  ```
* **🧠 Explanation:** Python tuple packing/unpacking mechanism use karta hai, jisse third temporary variable ki zaroorat nahi padti.
* **🎤 Viva Point:** Python mein bina third variable ke direct swapping `a, b = b, a` syntax se hoti hai.
---
### 1️⃣7️⃣ Leap Year
* **📖 Description:** Check karna ki given year leap year hai ya standard year.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter Year/]
      B --> C{"Year % 400 == 0 ?"}
      C -- Yes --> D[/Leap Year/]
      C -- No --> E{"Year % 4 == 0 and Year % 100 != 0 ?"}
      E -- Yes --> D
      E -- No --> F[/Not Leap Year/]
      D --> G([End])
      F --> G
  ```
* **💻 Source Code:**
  ```python
  year = int(input("Enter year: "))
  if year % 400 == 0 or (year % 4 == 0 and year % 100 != 0):
      print("Leap year")
  else:
      print("Not a leap year")
  ```
* **🧠 Explanation:** Leap year rule: Century years must be divisible by 400, while non-century years must be divisible by 4.
* **🎤 Viva Point:** Har 4th year leap year nahi hota agar wo century year ho jab tak wo 400 se divisible na ho.
---
### 1️⃣8️⃣ Count Digits
* **📖 Description:** Kisi number mein total number of digits count karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter N/]
      B --> C["Count = 0"]
      C --> D{"N > 0 ?"}
      D -- Yes --> E["N = N // 10"]
      E --> F["Count = Count + 1"]
      F --> D
      D -- No --> G[/Print Count/]
      G --> H([End])
  ```
* **💻 Source Code:**
  ```python
  n = int(input("Enter a number: "))
  count = 0
  while n > 0:
      n = n // 10
      count = count + 1
  print("Number of digits =", count)
  ```
* **🧠 Explanation:** Har iteration mein `n // 10` se ek digit truncate hoti hai aur counter increment hota hai.
* **🎤 Viva Point:** Digit counting mathematical division ya string conversion (`len(str(n))`) dono tareeqon se ho sakti hai.
---
### 1️⃣9️⃣ Maximum Number in a List
* **📖 Description:** Ek predefined ya dynamic list mein se highest element trace karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B["Create List"]
      B --> C["Maximum = First Element"]
      C --> D["Take Next Element"]
      D --> E{"Element > Maximum ?"}
      E -- Yes --> F["Maximum = Element"]
      E -- No --> G["Continue"]
      F --> G
      G --> H{"More Elements?"}
      H -- Yes --> D
      H -- No --> I[/Print Maximum/]
      I --> J([End])
  ```
* **💻 Source Code:**
  ```python
  numbers = [10, 25, 7, 45, 18]
  maximum = numbers[0]
  for num in numbers:
      if num > maximum:
          maximum = num
  print("Maximum =", maximum)
  ```
* **🧠 Explanation:** Pehle element ko benchmark (`maximum`) assign karte hain, phir poori list iterate karke compare aur update karte hain.
* **🎤 Viva Point:** Built-in function `max(numbers)` bhi same task perform karta hai.
---
### 2️⃣0️⃣ Count Vowels in a String
* **📖 Description:** String ke andar total vowels (`a, e, i, o, u`) ki frequency count karna.
* **🔄 Flow Diagram:**
  ```mermaid
  flowchart TD
      A([Start]) --> B[/Enter String/]
      B --> C["Count = 0"]
      C --> D["Take Character"]
      D --> E{"Is Character a Vowel?"}
      E -- Yes --> F["Count = Count + 1"]
      E -- No --> G["Continue"]
      F --> G
      G --> H{"More Characters?"}
      H -- Yes --> D
      H -- No --> I[/Print Count/]
      I --> J([End])
  ```
* **💻 Source Code:**
  ```python
  text = input("Enter a string: ")
  count = 0
  for ch in text:
      if ch.lower() in "aeiou":
          count = count + 1
  print("Number of vowels =", count)
  ```
* **🧠 Explanation:** `.lower()` case sensitivity handle karta hai aur `in` operator vowel set membership verify karta hai.
* **🎤 Viva Point:** `in` Python ka membership operator hai jo check karta hai k
