# Flowcharts & Pseudocode

## Flowchart

A flowchart is a graphical representation of the steps required to solve a problem.
It uses different symbols to represent different types of operations.

### Common Flowchart Symbols

| Symbol | Purpose |
|---|---|
| Oval | Start / End |
| Rectangle | Process / Calculation |
| Parallelogram | Input / Output |
| Diamond | Decision / Condition |
| Arrow | Flow / Direction |

---

## Pseudocode

Pseudocode is a simple, informal way of writing the steps of a solution before converting them into actual code. 
It uses normal language instead of the syntax of a specific programming language, to help Developers in understanding the code.

### Example

**Problem:** Write an algorithm to calculate the area of a square.

Formula:

**Area = side × side**

### Pseudocode

1. Start
2. Input the side of the square
3. Calculate area = side × side
4. Display the area
5. End

### Flowchart

Start
↓
Input side
↓
Calculate area = side × side
↓
Display area
↓
End

## Practice Problem: Minimum of Two Numbers

### Pseudocode

1. Start
2. Input two numbers a and b
3. If a < b, then minimum = a
4. Else, minimum = b
5. Display the minimum
6. End
 

### Flowchart:

Start
  ↓
Input a, b
  ↓
Is a < b?
 ↙       ↘
Yes       No
 ↓         ↓
min = a   min = b
  ↘       ↙
   Display min
       ↓
      End

## Sum of Numbers from 1 to N

Given a number N, calculate the sum of all numbers from 1 to N.
Example:
N = 5
1 + 2 + 3 + 4 + 5 = 15

### 2. Logic
We use two variables:
- count → keeps track of the current number.
- sum → stores the total calculated so far.

### 3. Dry Run
For N = 5:
Count	Sum before	Operation	Sum after
1	     0	            0 + 1	   1
2	     1          	1 + 2	   3
3	     3	            3 + 3	   6
4	     6	            6 + 4	   10
5	     10	            10 + 5	   15
After this, count = 6.
Since:
6 <= 5 → false
the loop stops.
Output:
15

### 4. Pseudocode
START
Input N
count = 1
sum = 0
While count <= N
    sum += count
    count += 1
Print sum
END

### 5. Flowchart Structure
START
  ↓
Input N
  ↓
count = 1, sum = 0
  ↓
count <= N
 ↙          ↘
YES          NO
 ↓            ↓
sum += count  Print sum
 ↓            ↓
count += 1   END
 ↓
 └──→ Check condition again


 ## Prime Numbers
Write an algorithm to check whether a given number is prime or non-prime.