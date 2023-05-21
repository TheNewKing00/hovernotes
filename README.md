# Hover Notes
    This Notes provides Overview to all laguages an their fundamentals.
**Table of Contents**
- [Hover Notes](#hover-notes)
  - [Dunders and Boiler Plates](#dunders-and-boiler-plates)
    - [python](#python)
    - [Java](#java)
    - [C](#c)
    - [C++](#c-1)
  - [Data types and variable declarations](#data-types-and-variable-declarations)
    - [python](#python-1)
    - [java](#java-1)
    - [C](#c-2)
    - [C++](#c-3)
  - [Logic and Operation](#logic-and-operation)
    - [python](#python-2)
    - [java](#java-2)
    - [C](#c-4)
    - [C++](#c-5)
  - [Arrays](#arrays)
    - [Python](#python-3)
    - [Java](#java-3)
    - [C](#c-6)
    - [C++](#c-7)
  - [If Else Conditionals](#if-else-conditionals)
    - [Python](#python-4)
    - [Java](#java-4)
    - [C](#c-8)
    - [C++](#c-9)
  - [for and while Loops](#for-and-while-loops)
    - [Python](#python-5)
    - [Java](#java-5)
    - [C](#c-10)
    - [C++](#c-11)
  - [Functions or Methods](#functions-or-methods)
    - [Python](#python-6)
    - [Java](#java-6)
    - [C](#c-12)
    - [C++](#c-13)
  - [User Inputs](#user-inputs)
    - [Python](#python-7)
    - [Java](#java-7)
    - [C](#c-14)
    - [C++](#c-15)

## Dunders and Boiler Plates
### python
```
def main():
    print("Hello World")

if __name__ == '__main__':
    main()
```
### Java
```
public class _____ {
    public static void main(String[] args) {
        System.out.println("Hello World")
    }
}
```
### C
```
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```
### C++
```
#include <iostream>
using namespace std;

int main() {
    cout << "Hello World" << endl;>>
    return 0;
}
```
## Data types and variable declarations
### python
```
#no need variables are automatically defined upon creation
```
### java
```
int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";
```
### C
```
int myNum = 15;
float myFloatNum = 5.99;
char myLetter = 'D';
```
### C++
```
int myNum = 5;
double myFloatNum = 5.99;
char myLetter = 'D';
string myText = "Hello";
bool myBoolean = true;
```
## Logic and Operation
### python

| **Operator**      | **Name**           |
|:----------------- |:------------------ |
| +                 | Addition           |
| -                 | Subtraction        |
| *                 | Multiplication     |
| /                 | Division           |
| %                 | Modulus            |
| **                | Exponent           |
| //                | Floor Division     |

| **Comparators**   | **Name**           |
|:----------------- |:------------------ |
| ==                | Equal              |
| !=                | Not Equal          |
| >                 | Greater Than       |
| <                 | Less Than          |
| >=                | Greater Than or Eq |
| <=                | Less Than or Eq to |

| **Logics**        | **Name**           |
|:----------------- |:------------------ |
| &                 | AND                |
| \|                | OR                 |
| ^                 | XOR                |
| ~                 | NOT                |
### java
| **Operator**      | **Name**           |
|:----------------- |:------------------ |
| +                 | Addition           |
| -                 | Subtraction        |
| *                 | Multiplication     |
| /                 | Division           |
| %                 | Modulus            |
| ++                | Increment          |
| --                | Decrement          |

| **Comparators**   | **Name**           |
|:----------------- |:------------------ |
| ==                | Equal              |
| !=                | Not Equal          |
| >                 | Greater Than       |
| <                 | Less Than          |
| >=                | Greater Than or Eq |
| <=                | Less Than or Eq to |

| **Logics**        | **Name**           |
|:----------------- |:------------------ |
| &&                | AND                |
| \|\|              | OR                 |
| !                 | NOT                |
### C
>Same as Java
### C++
>Same as Java
## Arrays
### Python
`MyArray = ["Item 1", "Item 2", "Item 3"]`
*index array* `myArray[n]`
*insert to array* `.append()`
*remove from index numner* `.pop(n)`
*remove by value* `.remove("Item 1")`
### Java
`String[] myArray = ["Item 1", "Item 2", "Item 3"]`
*index array* `myArray[n]`
### C
>Same as Java
### C++
>Same as Java
## If Else Conditionals
### Python
```
if __ Comparator __ :
    # Do something
elif __ Comparator __ :
    # Do something
else:
    # Do something
```
### Java
```
if (__ Comparator __) {
    // Do Something
}
else if (__ Comparator __) {
    // Do Something
}
else {
    // Do Something
}
```
### C
>Same as Java
### C++
>Same as Java
## for and while Loops
### Python
use range
```
for i in range(*n ,n ,n ):
    # Do something
```
use variables
```
for i in myVars:
    # Do Something
```
While Loops
```
while __ Comparator __:
    # Do Something
```
### Java
>For Loops in java are quite different
for (statement 1; statement 2; statement 3) { // Do Something }

>Where 1st Statement sets the initial Value
2nd makes the Condition Limit
3rd increments it
```
for (int i = 0; i < 5; i++) {
  // Do Something
}
```
While loops 
```
while (__ Comparator __) {
    // Do Something
}
```
Do While loops
> just like for loops just restructured

>Statement 1;
do {
    // Do something
    Statement 3;
}
while (statement 2);
```
int i = 0;
do {
  System.out.println(i);
  i++;
}
while (i < 5);
```
### C
>Same as Java
### C++
>Same as Java
## Functions or Methods
### Python
```
def my_Func(): 
    # Do something
```
### Java
```
static void my_Method() {
    // Do something
}
```
### C
```
void my_Func() {
    // Do something
}
```
### C++
> Same as C

## User Inputs
### Python
`myVariable = input()`
### Java
```
import java.util.Scanner;

Scanner scannerObj = new Scanner(System.in);
String myVariable = scannerObj.nextline();
```
### C
datatype coef's 
| **coef** | **datatype** |
|:-|:-
| "%d | int |
| "%c | char |

```
scanf( coef , &myVariable);
printf( coef , myVariable);
```
### C++
`cin >> myVariable;`
