# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
int main()
{
std::cout<<"Hello World!";
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
cout<<"Hello World!";
return 0;
}
```
----------------------------------------

# Question 2

### **Question:**

> ***Write a program to find the area of a circle.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
float r, area;
cout<<"Enter any number:";
cin>>r;
area = 3.14 * r * r;
cout<<"The area of the circle = "<< area;
return 0;
}
```
----------------------------------------

# Question 3

### **Question:**

> ***Write a program to find the sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
float a, b, sum;
cout<<"Enter any two numbers:";
cin>>a;
cin>>b;
sum = a+ b;
cout<<"The sum of a and b = "<< sum;
return 0;
}
```
----------------------------------------

# Question 4

### **Question:**

> ***Write a program to find the square of a number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int a, b;
a=2;
b = a * a;
cout<<"The square of a = "<< b;
return 0;
}
```
----------------------------------------

# Question 5

### **Question:**

> ***Write a program to find the greatest of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int a, b;
a = 2;
b = 3;
if(a>b)
{
cout<<"a is greater than b";
}
else
{
cout<<"b is greater than a";
}
return 0;
}
```
----------------------------------------

# Question 6

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i, avg, sum = 0;
int num [5] = {16, 18, 20, 25, 36};
for(i=0; i<5; i++)
sum = sum + num [i];
avg = sum/5;
cout<<"Sum of the Elements in the array = "<< sum <<endl;
cout<<"Average of the elements in the array= "<< avg<<endl;
return 0;
}
```
----------------------------------------

# Question 7

### **Question:**

> ***Write a program such that a Switch (case) allows to make a decision from the number of choices, i.e., from the number of cases.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
char ch;
cout<<"Enter any character:";
cin>>ch;
switch(ch)
{
case 'R':
cout<<"Red";
break;
case 'W':
cout<<"White";
break;
case 'Y':
cout<<"Yellow";
break;
case 'G':
cout<<"Green";
break;
default:
cout<<"Error";
break;
}
return 0;
}
```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program to find the greatest of two numbers using pointers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int x, y, *p, *q;
cout<<"Enter any integer:";
cin>> x;
cout<<"Enter any integer:";
cin>> y;
p = &x;
q = &y;
if(*p>*q)
{
cout<<"x is greater than y";
}
else
{
cout<<"y is greater than x";
}
return 0;
}
```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to print the address of x and the value assigned to x.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int x, *p;
cout<<"Enter any integer:";
cin>>x;
p = &x;
cout<<"The address of the variable x = "<< p<<endl;
cout<<"The value of the variable x = "<< *p<<endl;
return 0;
}
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to print the first 10 numbers starting from one together with their squares and cubes.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i;
for( i=1; i<=10; i++)
cout<<"number = "<< i <<" its square = "<< i*i <<" its cube = "<< i*i*i<< endl;
return 0;
}
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program:</br>
If you enter a character M</br>
Output must be: ch = M.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
char M;
cout<<"Enter any character:";
cin>>M;
cout<<"ch= "<< M;
return 0;
}
```
----------------------------------------

# Question 12

### **Question:**

> ***Write a program to print the multiplication table of a number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int n, i;
cout<<"Enter any number:";
cin>>n;
for( i=1; i<=5; i++)
cout<< n <<" * "<< i <<" = "<< n*i <<endl;
return 0;
}
```
----------------------------------------


# Question 13

### **Question:**

> ***Write a program to print the product of the first 10 digits.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i, product = 1;
for( i=1; i<=10; i++)
product = product * i;
cout<<"The product of the first 10 digits = " << product;
return 0;
}
```
----------------------------------------

# Question 14

### **Question:**

> ***Write a program to print whether the given number is positive or negative.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int a;
a = -35;
if(a>0)
{
cout<<"Number is positive";
}
else
{
cout<<"Number entered is negative";
}
return 0;
}
```
----------------------------------------

# Question 15

### **Question:**

> ***Write a program to check the equivalence of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int x, y;
cout<<"Enter any number:";
cin>>x;
cout<<"Enter any number:";
cin>>y;
if(x-y==0)
{
cout<<"The two numbers are equivalent";
}
else
{
cout<<"The two numbers are not equivalent";
}
return 0;
}
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program to print the remainder of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int a, b, c;
cout<<"Enter any number:";
cin>>a;
cout<<"Enter any number:";
cin>>b;
c = a % b;
cout<<"The remainder of a and b = "<< c;
return 0;
}
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to print the given number is even or odd.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int a;
cout<<"Enter any number:";
cin>>a;
if(a%2 = = 0)
{
cout<<"The number is even";
}
else
{
cout<<"The number is odd";
}
return 0;
}
```
----------------------------------------

# Question 18

### **Question:**

> ***Write a program to print the characters from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
char a = 'A';
while (a<='Z')
{
cout<<" \n"<< a++;
}
return 0;
}
```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to find the incremented and decremented values of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int a, b, c, d, e, f;
a = 10;
b=12;
c=a+1;
d=b+1;
e=a-1;
f=b-1;
cout<<"The incremented value of a = "<< c << endl;
cout<<"The incremented value of b = "<< d << endl;
cout<<"The decremented value of a = "<< e << endl;
cout<<"The decremented value of b = "<< f << endl;
return 0;
}
```
----------------------------------------

# Question 20

### **Question:**

> ***Write a program to calculate the simple interest.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int P,T, R, SI;
cout<<"Enter principal amount:";
cin>>P;
cout<<"Enter time:";
cin>>T;
cout<<"Enter rate of interest:";
cin>>R;
SI = P*T*R/100;
cout<<"the simple interest = "<<SI;
return 0;
}
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to Find the largest of three numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int a, b, c;
cout<<"Enter any number:";
cin>>a;
cout<<"Enter any number:";
cin>>b;
cout<<"Enter any number:";
cin>>c;
if(a>b&&a>c)
{
cout<< a<<" is greater than "<< b<<" and "<<c;
}
else if (b>a&&b>c)
{
cout<< b<<" is greater than "<< a <<" and "<<c;
}
else
{
cout<< c<<" is greater than "<< b<<" and "<< a;
}
return 0;
}
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to print the factorial of the entered number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i, n, fact=1 ;
cout<<"Enter any number:";
cin>>n;
for(i=1; i<=n; i++)
fact = fact *i;
cout<<"\n Entered number is: "<< n;
cout<<"\n The factorial of the entered number "<< n <<" is: "<< fact;
return 0;
}

```
----------------------------------------

# Question 23

### **Question:**

> ***Write a program to print the length of the entered string.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<iostream>
#include<string.h>
using namespace std;
int main()
{
char ch[4];
cout<<"Enter any word: ";
cin>>ch;
cout<<"The length of the string = "<< strlen(ch);
return 0;
}
```
----------------------------------------

# Question 24

### **Question:**

> ***Write a program to print the ASCII value of the entered character.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
int main()
{
 char c;
 cout << "Enter a character: ";
 cin >> c;
 cout << "ASCII Value of " << c << " is " << int(c);
 return 0;
}
```
----------------------------------------


# Question 25

### **Question:**

> ***Write a program to check whether the entered character is a lower case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
char ch = 'a';
if(islower(ch))
cout<<"you have entered the lower case letter";
else
cout<<"you have entered the upper case letter";
return 0;
}
```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to check whether the entered character is a upper case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
char ch = 'a';
if(isupper(ch))
cout<<"you have entered the upper case letter";
else
cout<<"you have entered the lower case letter";
return 0;
}
```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program to convert the lower case letter to upper case letter.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
char ch = 'a';
char b = toupper(ch);
cout<<" lower case letter "<<ch<<" is converted to upper case letter "<<b;
return 0;
}
```
----------------------------------------

# Question 28

### **Question:**

> ***Write a program to print the output:</br>
Einstein [0] = E</br>
Einstein [1] = I</br>
Einstein [2] = N</br>
Einstein [3] = S</br>
Einstein [4] = T</br>
Einstein [5] = E</br>
Einstein [6] = I</br>
Einstein [7] = N</br>***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i;
char name [8] = {'E' , 'I', 'N', 'S', 'T', 'E', 'I', 'N'};
for(i=0; i<8; i++)
cout<<"Element ["<< i <<" ] = "<< name[i] << endl;
return 0;
}
```
----------------------------------------

# Question 29

### **Question:**

> ***Write a program to print the output:</br>
Name of the book = B</br>
Price of the book = 135.00</br>
Number of pages = 300</br>
Edition = 8</br>
using structures.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
struct book {
char name;
float price;
int pages;
int edition;
};
struct book b1= {'B', 135.00, 300, 8};
cout<<"Name of the book = "<< b1.name<< endl;
cout<<"Price of the book = "<< b1.price<<endl;
cout<<"Number of pages = "<< b1.pages<<endl;
cout<<"Edition of the book = "<< b1.edition<< endl;
return 0;
}
```
----------------------------------------

# Question 30

### **Question:**

> ***Write a program to find square of a number using functions.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int square();
int main()
{
int answer;
answer = square();
cout<<"Square of the given number = "<< answer;
return 0;
}
int square()
{
int x;
cout<<"Enter any integer:";
cin>>x;
return x*x;
}
```
----------------------------------------

# Question 31

### **Question:**

> ***Write a program To print "hello world" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i;
for (i =1; i<=10; i ++)
cout<<"\n hello world";
return 0;
}
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to print first 5 numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i =1;
do
{
cout<<" \n i= "<< i++;
} while (i<=5);
return 0;
}
```
----------------------------------------

# Question 33

### **Question:**

> ***Write a program to print the output:</br>
body [b] = b</br>
body [o] = o</br>
body [d] = d</br>
body [y] = y</br>***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
int main()
{
char i;
char body [4] = {'b', 'o', 'd', 'y'};
for(i=0; i<4; i++)
cout<<"\n body ["<<body[i] <<" ] = "<< body[i] << endl;
return 0;
}
```
----------------------------------------


# Question 34

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```C++ language
#include <iostream>
using namespace std;
int main()
{
cout<<"linux\n";
exit (0);
cout<<"php\n";
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
linux
```
----------------------------------------

# Question 35

### **Question:**

> ***Write a program to check whether a character is an alphabet or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
int main()
{
int a =2;
if(isalpha(a))
{
   cout<<"The character a is an alphabet"; 
}
else
{
cout<<"The character a is not an alphabet"; 
}
return 0;
}
```
----------------------------------------

# Question 36

### **Question:**

> ***Write a program to calculate the discounted price and the total price after discount</br>
Given:</br>
If purchase value is greater than 1000, 10% discount</br>
If purchase value is greater than 5000, 20% discount</br>
If purchase value is greater than 10000, 30% discount.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
double PV;
cout<<"Enter purchased value:";
cin>>PV;
if(PV>1000)
{
cout<<"Discount = "<< PV* 0.1 << endl;
cout<<"Total= "<< PV - PV* 0.1 << endl;
}
else if(PV>5000)
{
cout<<"Discount = "<< PV* 0.2 << endl;
cout<<"Total= "<< PV - PV* 0.1 << endl;
}
else
{
cout<<"Discount = "<< PV* 0.3 << endl;
cout<<"Total= "<< PV - PV* 0.1 << endl;
}
return 0;
}
```
----------------------------------------

# Question 37

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i = 1;
while (i<=10)
{
cout<<"\n "<< i++;
}
return 0;
}
```
----------------------------------------

# Question 38

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```C++ language
#include <iostream>
using namespace std;
int main()
{
int i;
for (i=1; i<=5; i++)
{
if (i==3)
{
continue;
}
cout<<"\n "<< i;
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
1
2
4
5
```
----------------------------------------

# Question 39

### **Question:**

> ***Write a program to find the size of an array.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
int main()
{
   int num [] = {11, 22, 33, 44, 55, 66};
    int n;

    /* Calculating the size of the array with this formula.
     * n = sizeof(array_name) / sizeof(array_name[0])
     * This is a universal formula to find number of elements in
     * an array, which means it will work for arrays of all data
     * types such as int, char, float etc.
     */
    n = sizeof(num) / sizeof(num [0]);
    cout<<"Size of the array is:"<<n;
    return 0;
}
```
----------------------------------------

# Question 40

### **Question:**

> ***What would be the output of the following programs:***

----------------------------------------

```C++ language
#include <iostream>
using namespace std;
int main()
{
int i;
for (i=1; i<=5; i++)
{
if (i==3)
{
break;
}
cout<<"\n "<< i;
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
1
2
```
----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i;
for(i=1;i<=5;i++)
{
if(i==3)
{
goto HAI;
}
cout<<"\n "<< i;
}
HAI : cout<<"\n Linux";
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
1
2
Linux
```
----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i = 54;
int y = i<<1;
cout<<"The value of y = "<< y;
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
The value of y = 108
```
----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main()
{
int i = 54;
int y = i>>1;
cout<<"The value of y = "<< y;
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
The value of y = 27
```
----------------------------------------

```C++ language
#include<iostream>
#include<cmath>
using namespace std;
int main()
{
int a, b;
a= - 2;
b= abs(a);
cout<<" Absolute value = "<< b<< endl;
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
Absolute value = 2
```
----------------------------------------

```C++ language
#include <iostream>
using namespace std;
int main()
{
for( ; ; ) {
cout<<"This loop will run forever.\n";
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever. ......... 
```
----------------------------------------


```C++ language
#include<iostream>
using namespace std;
int main()
{
cout<<"Hello World!";
return 0;
cout<<"Hello World!";
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
Hello,world! 
```
----------------------------------------

# Question 41

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main()
{
int age;
age=20;
if(age > = 60)
{
cout<<"Senior citizen";
}
if(age<60)
{
cout<<"Not a senior citizen";
}
return 0;
}
```
----------------------------------------

# Question 42

### **Question:**

> ***Write a program to compute inverse of tan x.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<math.h>
using namespace std;
int main()
{
int x = 20;
cout<<"Inverse of tan x = "<< atan(x);
return 0;
}
```
----------------------------------------
 
 
# Question 43

### **Question:**

> ***Write a program to Find All Roots of a Quadratic Equation.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
#include <cmath>
using namespace std;

int main() {

    float a, b, c, x1, x2, discriminant, realPart, imaginaryPart;
    cout << "Enter coefficients a, b and c: ";
    cin >> a >> b >> c;
    discriminant = b*b - 4*a*c;
    
    if (discriminant > 0) {
        x1 = (-b + sqrt(discriminant)) / (2*a);
        x2 = (-b - sqrt(discriminant)) / (2*a);
        cout << "Roots are real and different." << endl;
        cout << "x1 = " << x1 << endl;
        cout << "x2 = " << x2 << endl;
    }
    
    else if (discriminant == 0) {
        cout << "Roots are real and same." << endl;
        x1 = -b/(2*a);
        cout << "x1 = x2 =" << x1 << endl;
    }

    else {
        realPart = -b/(2*a);
        imaginaryPart =sqrt(-discriminant)/(2*a);
        cout << "Roots are complex and different."  << endl;
        cout << "x1 = " << realPart << "+" << imaginaryPart << "i" << endl;
        cout << "x2 = " << realPart << "-" << imaginaryPart << "i" << endl;
    }

    return 0;
}
```
----------------------------------------

# Question 44

### **Question:**

> ***Write a program to Display Fibonacci Series.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

int main()
{
    int n, t1 = 0, t2 = 1, nextTerm = 0;

    cout << "Enter the number of terms: ";
    cin >> n;

    cout << "Fibonacci Series: ";

    for (int i = 1; i <= n; ++i)
    {
        // Prints the first two terms.
        if(i == 1)
        {
            cout << " " << t1;
            continue;
        }
        if(i == 2)
        {
            cout << t2 << " ";
            continue;
        }
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
        
        cout << nextTerm << " ";
    }
    return 0;
}
```
----------------------------------------

# Question 45

### **Question:**

> ***Write a program to Find GCD.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

int main()
{
    int n1, n2;

    cout << "Enter two numbers: ";
    cin >> n1 >> n2;
    
    while(n1 != n2)
    {
        if(n1 > n2)
            n1 -= n2;
        else
            n2 -= n1;
    }

    cout << "HCF = " << n1;
    return 0;
}
```
----------------------------------------

# Question 46

### **Question:**

> ***Write a program to Find LCM.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

int main()
{
    int n1, n2, max;

    cout << "Enter two numbers: ";
    cin >> n1 >> n2;
    
    // maximum value between n1 and n2 is stored in max
    max = (n1 > n2) ? n1 : n2;

    do
    {
        if (max % n1 == 0 && max % n2 == 0)
        {
            cout << "LCM = " << max;
            break;
        }
        else
            ++max;
    } while (true);
    
    return 0;
}
```
----------------------------------------

# Question 47

### **Question:**

> ***Write a program to Display Prime Numbers Between Two Intervals.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

int main() {
    int low, high, i;
    bool isPrime = true;

    cout << "Enter two numbers (intervals): ";
    cin >> low >> high;

    cout << "\nPrime numbers between " << low << " and " << high << " are: " << endl;

    while (low < high) {
        isPrime = true;
        if (low == 0 || low == 1) {
            isPrime = false;
        }
        else {
            for (i = 2; i <= low / 2; ++i) {
                if (low % i == 0) {
                    isPrime = false;
                    break;
                }
            }
        }
        
        if (isPrime)
            cout << low << " ";

        ++low;
    }

    return 0;
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program to Check Armstrong Number.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

int main() {
    int num, originalNum, remainder, result = 0;
    cout << "Enter a three-digit integer: ";
    cin >> num;
    originalNum = num;

    while (originalNum != 0) {
        // remainder contains the last digit
        remainder = originalNum % 10;
        
        result += remainder * remainder * remainder;
        
        // removing last digit from the orignal number
        originalNum /= 10;
    }

    if (result == num)
        cout << num << " is an Armstrong number.";
    else
        cout << num << " is not an Armstrong number.";

    return 0;
}
```
----------------------------------------

# Question 49

### **Question:**

> ***Write a program to print half pyramid using *.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

int main()
{
    int rows;

    cout << "Enter number of rows: ";
    cin >> rows;

    for(int i = 1; i <= rows; ++i)
    {
        for(int j = 1; j <= i; ++j)
        {
            cout << "* ";
        }
        cout << "\n";
    }
    return 0;
}
```
----------------------------------------



# Question 50

### **Question:**

> ***Write a program to print half pyramid using numbers.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

int main()
{
    int rows;

    cout << "Enter number of rows: ";
    cin >> rows;

    for(int i = 1; i <= rows; ++i)
    {
        for(int j = 1; j <= i; ++j)
        {
            cout << j << " ";
        }
        cout << "\n";
    }
    return 0;
}
```
----------------------------------------

# Question 51

### **Question:**

> ***Write a program to Find Sum of Natural Numbers using Recursion.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include<iostream>
using namespace std;

int add(int n);

int main()
{
    int n;

    cout << "Enter a positive integer: ";
    cin >> n;

    cout << "Sum =  " << add(n);

    return 0;
}

int add(int n)
{
    if(n != 0)
        return n + add(n - 1);
    return 0;
}
```
----------------------------------------

# Question 52

### **Question:**

> ***Write a program to Access Elements of an Array Using Pointer.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

int main()
{
   int data[5];
   cout << "Enter elements: ";

   for(int i = 0; i < 5; ++i)
      cin >> data[i];

   cout << "You entered: ";
   for(int i = 0; i < 5; ++i)
      cout << endl << *(data + i);

   return 0;
}
```
----------------------------------------

# Question 53

### **Question:**

> ***Write a program to Store Information of a Student in a Structure.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

struct student
{
    char name[50];
    int roll;
    float marks;
};

int main() 
{
    student s;
    cout << "Enter information," << endl;
    cout << "Enter name: ";
    cin >> s.name;
    cout << "Enter roll number: ";
    cin >> s.roll;
    cout << "Enter marks: ";
    cin >> s.marks;

    cout << "\nDisplaying Information," << endl;
    cout << "Name: " << s.name << endl;
    cout << "Roll: " << s.roll << endl;
    cout << "Marks: " << s.marks << endl;
    return 0;
}

```
----------------------------------------

# Question 54

### **Question:**

> ***Write a program to Store and Display Information Using Structure.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

struct student
{
    char name[50];
    int roll;
    float marks;
} s[10];

int main()
{
    cout << "Enter information of students: " << endl;

    // storing information
    for(int i = 0; i < 10; ++i)
    {
        s[i].roll = i+1;
        cout << "For roll number" << s[i].roll << "," << endl;

        cout << "Enter name: ";
        cin >> s[i].name;

        cout << "Enter marks: ";
        cin >> s[i].marks;

        cout << endl;
    }

    cout << "Displaying Information: " << endl;

    // Displaying information
    for(int i = 0; i < 10; ++i)
    {
        cout << "\nRoll number: " << i+1 << endl;
        cout << "Name: " << s[i].name << endl;
        cout << "Marks: " << s[i].marks << endl;
    }

    return 0;
}
```
----------------------------------------

# Question 55

### **Question:**

> ***Write a program to Add Complex Numbers by Passing Structure to a Function.***

---------------------------------------

<strong>Solution: </strong>

```c++
#include <iostream>
using namespace std;

typedef struct complex {
    float real;
    float imag;
} complexNumber;

complexNumber addComplexNumbers(complex, complex);

int main() {
    complexNumber num1, num2, complexSum;
    char signOfImag;

    cout << "For 1st complex number," << endl;
    cout << "Enter real and imaginary parts respectively:" << endl;
    cin >> num1.real >> num1.imag;

    cout << endl
         << "For 2nd complex number," << endl;
    cout << "Enter real and imaginary parts respectively:" << endl;
    cin >> num2.real >> num2.imag;

    // Call add function and store result in complexSum
    complexSum = addComplexNumbers(num1, num2);

    // Use Ternary Operator to check the sign of the imaginary number
    signOfImag = (complexSum.imag > 0) ? '+' : '-';

    // Use Ternary Operator to adjust the sign of the imaginary number
    complexSum.imag = (complexSum.imag > 0) ? complexSum.imag : -complexSum.imag;

    cout << "Sum = " << complexSum.real << signOfImag << complexSum.imag << "i";

    return 0;
}

complexNumber addComplexNumbers(complex num1, complex num2) {
    complex temp;
    temp.real = num1.real + num2.real;
    temp.imag = num1.imag + num2.imag;
    return (temp);
}
```
----------------------------------------

 
 
 
 
 </br>
 
 <h2> Papers  </h2>

<ul>

 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(1).pdf" style="text-decoration:none;">Programming
Abstractions in C++</a></li>


 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(2).pdf" style="text-decoration:none;">Introduction to C++ (and C) Programming</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(3).pdf" style="text-decoration:none;">Programming Languages — C++</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(4).pdf" style="text-decoration:none;">Parallel Scientific Computing in C++ and MPI</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(5).pdf" style="text-decoration:none;">Programming in C++: Introduction to the language standard C++14 (and a preview of C++17)</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(6).pdf" style="text-decoration:none;">OOP with C++</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(7).pdf" style="text-decoration:none;">Assessing Programming Language Impact on Development and Maintenance: A Study on C and C++</a></li>

 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(8).pdf" style="text-decoration:none;"> The C++ programming language in cheminformatics and computational chemistry</a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(9).pdf" style="text-decoration:none;">
Technical Report on C++ Performance </a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(10).pdf" style="text-decoration:none;">An Image Processing Library in Modern C++: Getting Simplicity and Efficiency with Generic Programming</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(11).pdf" style="text-decoration:none;">C++ lecture notes</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(12).pdf" style="text-decoration:none;">A profound reflection on C++ template mechanism</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(13).pdf" style="text-decoration:none;">Summary of C++ Data Structures</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(14).pdf" style="text-decoration:none;">Low-Cost Deterministic C++ Exceptions for Embedded Systems</a></li>
                              
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(15).pdf" style="text-decoration:none;">
Reversing C++ </a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(16).pdf" style="text-decoration:none;">Introduction to C++ Programming I</a></li>

  <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(17).pdf" style="text-decoration:none;">
A C++ Language Workbench</a></li>   
  
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(18).pdf" style="text-decoration:none;">Advanced Programming with C++</a></li> 

  
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(19).pdf" style="text-decoration:none;">The Game in C++</a></li> 

<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(20).pdf" style="text-decoration:none;"> The moderating effect of logic in the learning of C++ computer programming using screen casting</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(21).pdf" style="text-decoration:none;">
The Large Integer Case Study in C++ </a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(22).pdf" style="text-decoration:none;">Introducing Project-based Team Research into a C++ Programming Course</a></li> 
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(23).pdf" style="text-decoration:none;"> Fast Static Analysis of C++ Virtual Function Calls</a></li> 
 

   <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(24).pdf" style="text-decoration:none;">SAFEDISPATCH: Securing C++ Virtual Calls from Memory Corruption Attacks</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(25).pdf" style="text-decoration:none;">Object Model Construction for Inheritance in C++ and its Applications to Program Analysis</a></li>                              
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(26).pdf" style="text-decoration:none;">Inheritance and its type in Object Oriented Programming using C++</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(27).pdf" style="text-decoration:none;">Understanding Integer Overflow in C/C++</a></li>
   
 
   <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(28).pdf" style="text-decoration:none;">Comparative study of C, Objective C, C++ programming language</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(29).pdf" style="text-decoration:none;">A history of C++</a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(30).pdf" style="text-decoration:none;">
A Quick Introduction to C++</a></li>
 
   <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(31).pdf" style="text-decoration:none;">Function Overloading Implementation in C++</a></li> 
    <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(32).pdf" style="text-decoration:none;">Quantifying Behavioral Differences Between C and C++ Programs</a></li> 

   <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(33).pdf" style="text-decoration:none;">Using C++ Lambdas</a></li>                              

  <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(34).pdf" style="text-decoration:none;">C/C++ Thread Safety Analysis</a></li> 
 
  <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(35).pdf" style="text-decoration:none;">Abstraction and the C++ machine model</a></li> 

  <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(36).pdf" style="text-decoration:none;">An Overview of the C++ Programming Language</a></li> 
 
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(37).pdf" style="text-decoration:none;">Why C++ is not just an Object Oriented Programming Language</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(38).pdf" style="text-decoration:none;">Learning Standard C++ as a New Language</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(39).pdf" style="text-decoration:none;">Loop Recognition in C++/Java/Go/Scala</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/8cp(40).pdf" style="text-decoration:none;">C++ Programming</a></li>
</ul>
 
 </br>
 <h2> Source Codes </h2>
 <ul>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Airline Reservation System.rar" style="text-decoration:none;">Airline Reservation System</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Battle Ship Game.rar" style="text-decoration:none;">Battle Ship Game</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Daily Diary Management System.rar" style="text-decoration:none;">Daily Diary Management System</a></li>

 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Employee Database System.rar" style="text-decoration:none;"> Employee Database System</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Employee Management System.rar" style="text-decoration:none;"> Employee Management System</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Hospital Appointment System.rar" style="text-decoration:none;">Hospital Appointment System</a></li>
 
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Movie Ticket Booking System.rar" style="text-decoration:none;"> Movie Ticket Booking System</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Report Card Management System.rar" style="text-decoration:none;"> Report Card Management System</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Simple Role Playing Game.rar" style="text-decoration:none;">Simple Role Playing Game</a></li>
  <li><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/Student Detail Management  System.rar" style="text-decoration:none;">Student Detail Management  System</a></li>
 

</ul>
 </br>
<h3>Books:</h3>
<hr>

<ul>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(22).pdf" style="text-decoration:none;">A Tour of C++ </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(23).pdf" style="text-decoration:none;">Effective C++: 55 Specific Ways to Improve Your Programs and Designs</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(24).pdf" style="text-decoration:none;">Accelerated C++: Practical Programming by Example</a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(25).pdf" style="text-decoration:none;">C++ For Dummies </a></b></li>                              
<li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(26).pdf" style="text-decoration:none;">C++ FAQs </a></b></li>
                                
 <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(27).pdf" style="text-decoration:none;">C++ Concurrency in Action</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(28).pdf" style="text-decoration:none;">Modern C++ Design: Generic Programming and Design Patterns Applied </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(29).pdf" style="text-decoration:none;">Sams Teach Yourself C++ in One Hour a Day</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(30).pdf" style="text-decoration:none;">The C++ Programming Language</a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/pb(31).pdf" style="text-decoration:none;">Thinking in C++</a></b></li>


<li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(11).pdf" style="text-decoration:none;">Object Oriented Programming with C++ </a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(12).pdf" style="text-decoration:none;">Beginning C++ Through Game Programming </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(13).pdf" style="text-decoration:none;">C++ network programming</a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(14).pdf" style="text-decoration:none;">C++ Programming for the Absolute Beginner </a></b></li>                              
<li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(15).pdf" style="text-decoration:none;">Hands-On System Programming with C++</a></b></li>
                                
 <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(16).pdf" style="text-decoration:none;">Learn C++ Programming Language: Become A Complete C++ Programmer</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(17).pdf" style="text-decoration:none;">Moving From C to C++</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(18).pdf" style="text-decoration:none;">Fundamentals of Programming C++</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(19).pdf" style="text-decoration:none;">Real-Time C++</a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/CPlusPlus-Exercises-for-Beginners/blob/master/avc(20).pdf" style="text-decoration:none;">Schaum's outline of theory and problems of programming with C++</a></b></li> 










 </ul>
	
