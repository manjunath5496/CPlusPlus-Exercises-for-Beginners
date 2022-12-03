# Question 1

### **Question:**

> ***Write a program to print Hello, World!.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
int main() {
std::cout<<"Hello, World!";
return 0;
}

```
----------------------------------------


# Question 2

### **Question:**

> ***Write a program to compute the perimeter and area of a rectangle.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int height = 8;
int width = 5;
int perimeter = 2*(height + width);
cout<<"Perimeter of the rectangle is: " << perimeter << " cm\n";
int area = height * width;
cout<<"Area of the rectangle is: "<< area << " square cm\n";
return 0;
}
```
----------------------------------------


# Question 3

### **Question:**

> ***Write a program to compute the perimeter and area of a circle.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int radius = 4;
float perimeter = 2*3.14*radius;
cout<<"Perimeter of the circle is: " << perimeter << " cm\n";
float area = 3.14*radius*radius;
cout<<"Area of the circle is: "<< area << " square cm\n";
return 0;
}

```
----------------------------------------


# Question 4

### **Question:**

> ***Write a program that accepts two numbers from the user and calculate the sum of the two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language

#include<iostream>
using namespace std;
int main() {
float a, b, sum;
cout<<"\nEnter the first number: "; 
cin>>a;
cout<<"\nEnter the second number: ";
cin>>b;
sum = a+ b;
cout<<"\nSum of the above two numbers is: "<< sum;
return 0;
}


```
----------------------------------------


# Question 5

### **Question:**

> ***Write a program that accepts two numbers from the user and calculate the product of the two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a, b, mult;
cout<<"\nEnter the first number: "; 
cin>>a;
cout<<"\nEnter the second number: ";
cin>>b;
mult = a * b;
cout<<"\nProduct of the above two numbers is: " << mult;
return 0;
}

```
----------------------------------------


# Question 6

### **Question:**

> ***Write a program that accepts three numbers and find the largest of three.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y, z;
cout<<"\nEnter the first number: "; 
cin>>x;
cout<<"\nEnter the second number: ";
cin>>y;
cout<<"\nEnter the third number: ";
cin>>z;

// if x is greater than both y and z, x is the largest
if (x >= y && x >= z)
cout<<x<<" is the largest number.";

// if y is greater than both x and z, y is the largest
if (y >= x && y >= z)
cout<<y<<" is the largest number.";

// if z is greater than both x and y, z is the largest
if (z >= x && z >= y)
cout<<z<<" is the largest number.";
    
return 0;
}
```
----------------------------------------

# Question 7

### **Question:**

> ***Write a program that reads three floating values and check if it is possible to make a triangle with them. Also calculate the perimeter of the triangle if the entered values are valid.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float x, y, z;
cout<<"\nEnter the first number: "; 
cin>>x;
cout<<"\nEnter the second number: ";
cin>>y;
cout<<"\nEnter the third number: ";
cin>>z;

if(x < (y+z) && y < (x+z) && z < (y+x)) {  
cout<<"\nPerimeter of the triangle is: " << x+y+z;	 
}
else {
cout<<"\nIt is impossible to form a triangle.";
}

return 0;
}
```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program that reads an integer between 1 and 7 and print the day of the week in English.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int day;
cout<<"\nEnter a number between 1 to 7 to get the day name: ";
cin>>day;
switch(day) {
case 1 : cout<<"Monday\n"; break;
case 2 : cout<<"Tuesday\n"; break;
case 3 : cout<<"Wednesday\n"; break;
case 4 : cout<<"Thursday\n"; break;
case 5 : cout<<"Friday\n"; break;
case 6 : cout<<"Saturday\n"; break;
case 7 : cout<<"Sunday\n"; break;
default : cout<<"Enter a number between 1 to 7.";
}
return 0;
}
```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to find the sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a, b, sum;
a=1;
b=2;
sum = a + b;
cout<<"The sum of a and b is: " << sum;
return 0;
}
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to find the square of a number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<cmath>
using namespace std;
int main() {
int a, b;
a=2;
b = pow((a), 2);
cout<<"The square of a is: "<< b;
return 0;
}
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program to find the greatest of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a, b;
a = 2;
b = 3;
if(a>b) {
cout<<"a is greater than b";
}
else {
cout<<"b is greater than a";
}
return 0;
}
```
----------------------------------------

# Question 12

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i, avg, sum = 0;
int num [5] = {16, 18, 20, 25, 36};
for(i=0; i<5; i++) {
sum = sum + num [i];
avg = sum/5;
}
cout<<"\nSum of the Elements in the array is: "<< sum;
cout<<"\nAverage of the elements in the array is: " << avg;
return 0;
}
```
----------------------------------------

# Question 13

### **Question:**

> ***Write a program that prints all even numbers between 1 and 25.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
cout<<"Even numbers between 1 to 25:\n";
for(int i = 1; i <= 25; i++) {
if(i%2 == 0) {
cout<< i << endl;
}
}
return 0;
}
```
----------------------------------------


# Question 14

### **Question:**

> ***Write a program that prints all odd numbers between 1 and 50.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
int main() {
cout<<"Odd numbers between 1 to 50:\n";
for(int i = 1; i <= 50; i++) {
if(i%2 != 0) {
cout<<i<<endl;
}
}
return 0;
}
```
----------------------------------------


# Question 15

### **Question:**

> ***Write a program to print the first 10 numbers starting from one together with their squares and cubes.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
for(int i=1; i<=10; i++) {
cout<<"Number = " << i << " its square = " << i*i << " its cube = " << i*i*i <<endl;
}
return 0;
}  
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program:</br>
If you enter a character M</br>
Output must be: ch = M.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char M;
cout<<"Enter any character: ";
cin>>M;
cout<<"ch = "<< M;
return 0;
} 
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to print the multiplication table of a number entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int n, i;
cout<<"Enter any number: ";
cin>>n;
for( i=1; i<=5; i++)
cout<< n <<" * "<< i <<" = "<< n*i <<endl;
return 0;
}
```
----------------------------------------


# Question 18

### **Question:**

> ***Write a program to print the product of the first 10 digits.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i, product = 1;
for(i=1; i<=10; i++) {
product = product * i;
}
cout<<"The product of the first 10 digits is: " << product;
return 0;
}
```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to print whether the given number is positive or negative.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a;
a = -35;
if(a>0) {
cout<<"Number is positive";
}
else {
cout<<"Number is negative";
}
return 0;
}
```
----------------------------------------

# Question 20

### **Question:**

> ***Write a program to check the equivalence of two numbers entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y;
cout<<"Enter the first number: ";
cin>>x;
cout<<"Enter the second number: ";
cin>>y;
if(x-y==0) {
cout<<"The two numbers are equivalent";
}
else {
cout<<"The two numbers are not equivalent";
}
return 0;
}
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to print the remainder of two numbers entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a, b, c;
cout<<"Enter the first number: ";
cin>>a;
cout<<"Enter the second number: ";
cin>>b;
c = a % b;
cout<<"The remainder of " << a << " and " << b << " = " << c;
return 0;
}
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to print the characters from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char i;
for(i='A'; i<='Z'; i++) {
cout << i << endl;
}
return 0;
}
```
----------------------------------------


# Question 23

### **Question:**

> ***Write a program to print the length of the entered string.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<string.h>
using namespace std;
int main() {
char str[1000];
cout<<"Enter a string to calculate its length: ";
cin>>str;
cout<<"The length of the entered string is: "<< strlen(str);
return 0;
}
```
----------------------------------------


# Question 24

### **Question:**

> ***Write a program to check whether the given character is a lower case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char ch = 'a';
if(islower(ch))
cout<<"The given character is a lower case letter";
else
cout<<"The given character is a upper case letter";
return 0;
}
```
----------------------------------------


# Question 25

### **Question:**

> ***Write a program to check whether the given character is a upper case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char ch = 'A';
if(isupper(ch))
cout<<"The given character is a upper case letter";
else
cout<<"The given character is a lower case letter";
return 0;
}

```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to convert the lower case letter to upper case letter.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char ch = 'a';
char b = toupper(ch);
cout<<"Lower case letter "<<ch<<" is converted to Upper case letter "<<b;
return 0;
}

```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program that takes a distance in centimeters and outputs the corresponding value in inches.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
#define x 2.54
int main() {
double inch, cm;
cout<<"Enter the distance in cm: ";
cin>>cm;
inch = cm / x;
cout<<"\nDistance of "<< cm << " cms is equal to " << inch << " inches";
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
int main() {
int i;
char name [8] = {'E' , 'I', 'N', 'S', 'T', 'E', 'I', 'N'};
for(i=0; i<8; i++)
cout<<"Einstein ["<< i <<" ] = "<< name[i] << endl;
return 0;
}
```
----------------------------------------


# Question 29

### **Question:**

> ***Write a program to print "Hello World" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
for(int i=1; i<=10; i++) {
cout<< "Hello World"<< endl;
}
return 0;
}
```
----------------------------------------


# Question 30

### **Question:**

> ***Write a program to print first 5 numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i =1;
do {
cout<<" \ni = "<< i++;
} while(i<=5);
return 0;
}
```
----------------------------------------



# Question 31

### **Question:**

> ***Write a program to check whether a character is an alphabet or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a = 2;
if(isalpha(a)) {
cout<<"The character a is an alphabet"; 
}
else {
cout<<"The character a is not an alphabet"; 
}
return 0;
}
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to check whether a entered number is even or odd.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a;
cout<<"Enter any number: ";
cin>>a;
if(a%2 == 0) {
cout<<"The entered number is even";
}
else {
cout<<"The entered number is odd";
}
return 0;
}
```
----------------------------------------


# Question 33

### **Question:**

> ***Write a program to print the ASCII value of the entered character.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char c;
cout << "Enter a character: ";
cin >> c;
cout << "The ASCII Value of " << c << " is " << int(c);
return 0;
}
```
----------------------------------------


# Question 34

### **Question:**

> ***Write a program that will print all numbers between 1 to 50 which divided by a specified number and the remainder will be 2.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, i;
cout<<"Enter a number: ";
cin>>x;
for(i=1; i<=50; i++) {
   if((i%x)==2) {
    cout<<i<<endl;
	 }
}
return 0;
}
```
----------------------------------------


# Question 35

### **Question:**

> ***Write a program to determine whether two numbers in a pair are in ascending or descending order.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a, b;
cout<<"\nEnter a pair of numbers (for example 22,12 | 12,22): ";
cout<<"\nEnter the first number: ";
cin>>a;
cout<<"\nEnter the second number: ";
cin>>b;
if (a>b) {
cout<<"\nThe two numbers in a pair are in descending order.";
}
else {
cout<<"\nThe two numbers in a pair are in ascending order.";
}
return 0;
} 
```
----------------------------------------



# Question 36

### **Question:**

> ***Write a program that reads two numbers and divides one by the other. Specify "Division not possible" if that is not possible.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a, b;
float c;
cout<<"\nEnter the first number: ";
cin>>a;
cout<<"\nEnter the second number: ";
cin>>b;
if(b != 0) {
   	c = (float)a/(float)b;
	cout<<a<<"/"<<b<<" = "<< c;
} 
else {
	 cout<<"\nDivision not possible.\n";
}
return 0;
}
```
----------------------------------------

# Question 37

### **Question:**

> ***Write a program that will print all numbers between 1 to 50 which divided by a specified number and the remainder is equal to 2 or 3.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, i;
cout<<"Enter a number: ";
cin>>x;
for(i=1; i<=50; i++) {
   if((i%x)==2 || (i%x) == 3) {
    cout<<i<<endl;
	 }
}
return 0;
}
```
----------------------------------------



# Question 38

### **Question:**

> ***Write a program that adds up all numbers between 1 and 100 that are not divisible by 12.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x =12, i, sum = 0;
for(i=1; i<=100; i++) {
   if((i%x)!= 0) {
    sum += i;
	 }
}
cout<<"\nSum: "<<sum;
return 0;
}
```
----------------------------------------


# Question 39

### **Question:**

> ***Write a program to calculate the value of x where x = 1 + 1/2 + 1/3 + … + 1/50.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float x = 0;
for(int i=1; i<=50; i++) {
   x += (float)1/i;
}
cout<<"Value of x: "<< x;
return 0;
}
```
----------------------------------------


# Question 40

### **Question:**

> ***Write a program that reads a number and find all its divisor.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, i;
cout<<"\nEnter a number: ";
cin>>x;
cout<<"All the divisor of "<<x<<" are: \n";
for(i = 1; i <= x; i++) {
    if((x%i) == 0) {
	cout<<i<<endl;
    }
}	
return 0;
}
```
----------------------------------------


# Question 41

### **Question:**

> ***Write a program to find the incremented and decremented values of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
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


# Question 42

### **Question:**

> ***Write a program to find square of a entered number using functions.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int square();
int main() {
int answer;
answer = square();
cout<<"The square of the entered number is: "<< answer;
return 0;
}
int square() {
int x;
cout<<"Enter any number: ";
cin>>x;
return x*x;
}
```
----------------------------------------


# Question 43

### **Question:**

> ***Write a program that accepts principal amount, rate of interest, time and compute the simple interest.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int P,T, R, SI;
cout<<"Enter the principal amount: ";
cin>>P;
cout<<"Enter the time: ";
cin>>T;
cout<<"Enter the rate of interest: ";
cin>>R;
SI = P*T*R/100;
cout<<"The simple interest is: "<<SI;
return 0;
}
```
----------------------------------------


# Question 44

### **Question:**

> ***Write a program that swaps two numbers without using third variable.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a, b;
cout<<"\nEnter the value for a: ";
cin>>a;
cout<<"\nEnter the value for b: ";
cin>>b;
cout<<"\nBefore swapping: " <<a <<" "<<b;
a=a+b;
b=a-b;
a=a-b;
cout<<"\nAfter swapping: " <<a<<" "<<b;
return 0;
}
```
----------------------------------------

# Question 45

### **Question:**

> ***Write a program to find the greatest of two entered numbers using pointers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y, *p, *q;
cout<<"Enter the value for x: ";
cin>> x;
cout<<"Enter the value for y: ";
cin>> y;
p = &x;
q = &y;
if(*p>*q) {
cout<<"x is greater than y";
}
else {
cout<<"y is greater than x";
}
return 0;
}
```
----------------------------------------

# Question 46

### **Question:**

> ***Write a program to print the output:</br>
body [b] = b</br>
body [o] = o</br>
body [d] = d</br>
body [y] = y</br>***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char i;
char body [4] = {'b', 'o', 'd', 'y'};
for(i=0; i<4; i++)
cout<<"\n body ["<<body[i] <<" ] = "<< body[i] << endl;
return 0;
}

```
----------------------------------------

# Question 47

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
int main() {
double PV;
cout<<"Enter purchased value: ";
cin>>PV;
if(PV>1000) {
cout<<"Discount = "<< PV * 0.1 << endl;
cout<<"Total= "<< PV - PV * 0.1 << endl;
}
else if(PV>5000) {
cout<<"Discount = "<< PV * 0.2 << endl;
cout<<"Total= "<< PV - PV * 0.2 << endl;
}
else {
cout<<"Discount = "<< PV * 0.3 << endl;
cout<<"Total= "<< PV - PV * 0.3 << endl;
}
return 0;
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i = 1;
while(i<=10) {
cout<<"\n" << i++;
}
return 0;
}
```
----------------------------------------


# Question 49

### **Question:**

> ***Write a program to shift inputted data by two bits to the left.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x;
cout<<"Enter the integer from keyboard: ";
cin>>x;
cout<<"\nEntered value: "<< x;
cout<<"\nThe left shifted data is: " << (x<<=2);
return 0;
}
```
----------------------------------------

# Question 50

### **Question:**

> ***Write a program to shift inputted data by two bits to the Right.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x;
cout<<"Enter the integer from keyboard: ";
cin>>x;
cout<<"\nEntered value: "<< x;
cout<<"\nThe right shifted data is: " << (x>>=2);
return 0;
}
```
----------------------------------------



# Question 51

### **Question:**

> ***Write a program to calculate the exact difference between x and 21. Return three times the absolute difference if x is greater than 21.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x;
cout<<"Enter the value for x: ";
cin>>x;
if(x<=21){
    cout<<abs(x-21);
 }
else if(x>=21) {
    cout<<abs(x-21)*3;
}
return 0;
}
```
----------------------------------------


# Question 52

### **Question:**

> ***Write a program that reads in two numbers and determine whether the first number is a multiple of the second number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y;
cout<<"\nEnter the first number: ";
cin>>x;
cout<<"\nEnter the second number: ";
cin>>y;
if(x % y == 0) {
cout<<x<<" is a multiple of " <<y;
}
else {
cout<<x<<" is not a multiple of " <<y;    
}
return 0;
}
```
----------------------------------------


# Question 53

### **Question:**

> ***Write a program to print the output:</br>
Name of the book = B</br>
Price of the book = 135.00</br>
Number of pages = 300</br>
Edition of the book = 8</br>
using structures.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
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


# Question 54

### **Question:**

> ***Write a program to convert Celsius into Fahrenheit.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {   
float fahrenheit, celsius;  
celsius = 36;  
fahrenheit = ((celsius*9)/5)+32;  
cout<<"\nTemperature in fahrenheit is: "<<fahrenheit;  
return 0;  
} 
```
----------------------------------------


# Question 55

### **Question:**

> ***Write a program that will examine two inputted integers and return true if either of them is 50 or if their sum is 50.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y; 
cout<<"\nEnter the value for x: ";
cin>>x;
cout<<"\nEnter the value for y: ";
cin>>y;
if(x == 50 || y == 50 || (x + y == 50)) {
    cout<<"\nTrue";
} 
else {
    cout<<"\nFalse";
}    
return 0;
}
```
----------------------------------------


# Question 56

### **Question:**

> ***Write a program that counts the even, odd, positive, and negative values among eighteen integer inputs.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main () {
int x, even = 0, odd = 0, positive = 0, negative = 0;
cout<<"\nPlease enter 18 numbers: \n";
for(int i = 0; i < 18; i++) {
cin>>x;
if (x > 0) {
    positive++;
}
if(x < 0) {
    negative++;
}
if(x % 2 == 0) {
    even++;
}
if(x % 2 != 0) {
    odd++;
}
}
cout<<"\nNumber of even values: "<<even;
cout<<"\nNumber of odd values: "<<odd;
cout<<"\nNumber of positive values: "<<positive;
cout<<"\nNumber of negative values: "<<negative;
return 0;
}
```
----------------------------------------


# Question 57

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int age;
cout<<"Enter age: ";
cin>>age;
if(age>=60) {
cout<<"Senior citizen";
}
else {
cout<<"Not a senior citizen";
}
return 0;
}
```
----------------------------------------


# Question 58

### **Question:**

> ***Write a program that reads a student's three subject scores (0-100) and computes the average of those scores.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float score, total_score = 0;
int subject = 0;
cout<<"Enter three subject scores (0-100):\n";
while (subject != 3) {
cin>>score;
if(score < 0 || score > 100) {
cout<<"Please enter a valid score.\n";
}
else {
total_score += score;
subject++;
  }
}
cout<<"Average score = "<< (total_score/3);
return 0;
} 
```
----------------------------------------


# Question 59

### **Question:**

> ***What results would the following programs produce?***

----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main() {
for(int i=1; i<=5; i++) {
if(i==3) {
break;
}
cout<<"\n"<< i;
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
1
2
```
----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main() {
for(int i=1;i<=5;i++) {
if(i==3) {
goto HAI;
}
cout<<"\n "<<i;
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
int main() {
for( ; ; ) {
cout<<"This loop will run forever.\n";
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
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
int main() {
cout<<"Hello,world!";
return 0;
cout<<"Hello,world!";
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
Hello,world! 
```
----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main () {
cout<<"linux\n";
exit (0);
cout<<"php\n";
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
linux
```
----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main() {
for(int i=1; i<=5; i++) {
if(i==3) {
continue;
}
cout<<"\n "<<i;
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
1
2
4
5
```
----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main() {
int a = 10, b = 20, c;
c = (a < b) ? a : b;
cout<<c;
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
10

```

----------------------------------------

```C++ language
#include<iostream>
using namespace std;
#define A 15
int main() {
int x;
x=A;
cout<<x;
return 0;
}

```
----------------------------------------

<strong>Solution: </strong>

```C++ language
15

```

----------------------------------------


```C++ language
#include<iostream>
#include<cmath>
using namespace std;
int main() {
int x = 20;
cout<<"Inverse of tan x = "<< atan(x);
return 0;
}

```
----------------------------------------

<strong>Solution: </strong>

```C++ language

Inverse of tan x = 1.52084

```

----------------------------------------


```C++ language
#include<iostream>
#include<cmath>
using namespace std;
int main() {
double a, b;
a = -2.5;
b = fabs(a);
cout<<"|"<<a<<"|" << " = "<<b;
return 0;
}

```
----------------------------------------

<strong>Solution: </strong>

```C++ language
|-2.5| = 2.5

```

----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main() {
int x=12, y =3;
cout<<abs(-x-y);
return 0;
}

```
----------------------------------------

<strong>Solution: </strong>

```C++ language
15

```

----------------------------------------

```C++ language
#include<iostream>
using namespace std;
int main() {
int x=12, y =3;
cout<<-(-x-y);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
15

```

----------------------------------------

```C++ language
#include <iostream>
using namespace std;
int main() {
int x=12, y =3;
cout<< x-(-y);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C++ language
15

```

----------------------------------------



# Question 60

### **Question:**

> ***Write a program to find the size of an array.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int num [] = {11, 22, 33, 44, 55, 66};
int n = sizeof(num) / sizeof(num [0]);
cout<<"Size of the array is: " << n;
return 0;
}
```
----------------------------------------

# Question 61

### **Question:**

> ***Write a program that prints a sequence from 1 to a given integer, inserts a plus sign between these numbers, and then removes the plus sign at the end of the sequence.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main () {
int x, i;
cout<<"\nEnter a integer: \n";
cin>>x;
if(x>0) {
cout<<"Sequence from 1 to "<< x << ":\n";
for(i=1; i<x; i++)  {
cout<<i<<"+";
}
cout<<i<<"\n";
}
return 0;
}
```
----------------------------------------

# Question 62

### **Question:**

> ***Write a program to verify whether a triangle's three sides form a right angled triangle or not.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a,b,c;
cout<<"Enter the three sides of a triangle: \n";
cin>>a;
cin>>b;
cin>>c;  
if((a*a)+(b*b)==(c*c) || (a*a)+(c*c)==(b*b) || (b*b)+(c*c)==(a*a)) {  
cout<<"Triangle's three sides form a right angled triangle.\n";  
}
else { 
cout<<"Triangle's three sides does not form a right angled triangle.\n"; 
}
return 0;
}
```
----------------------------------------

# Question 63

### **Question:**

> ***Write a program that will find the second-largest number among the user's input of three numbers.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a, b, c;
cout<<"\nEnter the first number: ";
cin>>a;
cout<<"\nEnter the second number: ";
cin>>b;
cout<<"\nEnter the third number: ";
cin>>c;
if(a>b && a>c) {
    if(b>c)
            cout<<b<<" is second largest number among three numbers";
        else
            cout<<c<<" is second largest number among three numbers";
}
else if(b>c && b>a) {
    if(c>a)
            cout<<c<<" is second largest number among three numbers";
        else
            cout<<a<<" is second largest number among three numbers";
}
else if(a>b)
            cout<<a<<" is second largest number among three numbers";
        else
            cout<<b<<" is second largest number among three numbers";
    return 0;
}
```
----------------------------------------

# Question 64

### **Question:**

> ***Write a program to calculate the sum of the two given integer values. Return three times the sum of the two values if they are equal.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int myfunc();
int myfunc(int a, int b) {
return a == b ? (a + b)*3 : a + b;
}
int main() {
cout<<""<<myfunc(3, 5);
cout<<"\n"<<myfunc(6, 6);
return 0;
}    

```
----------------------------------------

# Question 65

### **Question:**

> ***Write a program that accepts minutes as input, and display the total number of hours and minutes.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int mins, hrs;
cout<<"Input minutes: ";
cin>>mins;
hrs=mins/60;
mins=mins%60;
cout<<hrs<<" Hours,"<<mins<< " Minutes.\n";
return 0;
}
```
----------------------------------------


# Question 66

### **Question:**

> ***Write a program to determine whether a positive number entered by the user is a multiple of three or five.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x;
cout<<"\nEnter a number: ";
cin>>x;    
if(x % 3 == 0 || x % 5 == 0) {
cout<<"True";   
}
else {
cout<<"False";    
}
return 0;
}
    
```
----------------------------------------


# Question 67

### **Question:**

> ***Write a program to verify whether one of the two entered integers falls within the range of 100 to 200 included.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y;
cout<<"\nEnter the value for x: ";
cin>>x; 
cout<<"\nEnter the value for y: ";
cin>>y; 
if((x >= 100 && x <= 200) || (y >= 100 && y <= 200)) {
cout<<"True";   
}
else {
cout<<"False";    
}
return 0;
}
    
```
----------------------------------------

# Question 68

### **Question:**

> ***Write a program to determine which of the two given integers is closest to the value 100. If the two numbers are equal, return 0.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int myfunc();
int myfunc(int a, int b) {
int x = abs(a - 100);
int y = abs(b - 100);
return x == y ? 0 : (x < y ? a : b);
}
int main() {
cout<<" "<< myfunc(86, 99);
cout<<"\n "<<myfunc(55, 55);
cout<<"\n "<<myfunc(65, 80);
return 0;
} 
```
----------------------------------------

# Question 69

### **Question:**

> ***Write a program to determine whether a positive number entered by the user is a multiple of three or five, but not both.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x;
cout<<"\nEnter a number: ";
cin>>x;    
if(x % 3 == 0 ^ x % 5 == 0) {
cout<<"True";   
}
else {
cout<<"False";    
}
return 0;
}
    
```
----------------------------------------


# Question 70

### **Question:**

> ***Write a program to determine whether two entered non-negative numbers have the same last digit.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y;
cout<<"\nEnter the value for x: ";
cin>>x; 
cout<<"\nEnter the value for y: ";
cin>>y;
if(abs(x % 10) == abs(y % 10)) {
cout<<"True";   
}
else {
cout<<"False";    
}
return 0;
}
    
```
----------------------------------------

# Question 71

### **Question:**

> ***Write a program to determine whether a given non-negative number is a multiple of 12 or it is one more than a multiple of 12.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x = 43;
if(x % 12 == 0 || x % 12 == 1) {
cout<<"True";   
}
else {
cout<<"False";    
}
return 0;
}     
```
----------------------------------------


# Question 72

### **Question:**

> ***Write a program that accepts two integers and returns true when one of them equals 6, or when their sum or difference equals 6.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y;
cout<<"\nEnter the value for x: ";
cin>>x; 
cout<<"\nEnter the value for y: ";
cin>>y;
if(x == 6 || y == 6 || x + y == 6 || abs(x - y) == 6) {
cout<<"True";   
}
else {
cout<<"False";    
}
return 0;
}     
```
----------------------------------------


# Question 73

### **Question:**

> ***Write a program to check whether it is possible to add two integers to get the third integer from three entered integers.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y, z;
cout<<"\nEnter the value for x: ";
cin>>x; 
cout<<"\nEnter the value for y: ";
cin>>y;
cout<<"\nEnter the value for z: ";
cin>>z;
if(x == y + z || y == x + z || z == x + y) {
cout<<"True";   
}
else {
cout<<"False";    
}
return 0;
}
    
```
----------------------------------------

# Question 74

### **Question:**

> ***Write a program that converts kilometers per hour to miles per hour.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float kmph;    
cout<<"Enter kilometers per hour: ";
cin>>kmph;
cout<<(kmph * 0.6213712)<<" miles per hour";
return 0;
}    
```
----------------------------------------


# Question 75

### **Question:**

> ***Write a program to calculate area of an ellipse.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
#define PI 3.141592
int main() {
float major, minor;
cout<<"\nEnter length of major axis: ";
cin>>major;
cout<<"\nEnter length of minor axis: ";
cin>>minor;
cout<<"\nArea of an ellipse = "<< (PI * major * minor);
return 0;
}
```
----------------------------------------

# Question 76

### **Question:**

> ***Write a program to calculate the sum of three given integers. Return the third value if the first two values are equal.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int myfunc();
int myfunc(int a, int b, int c) {
if (a == b && b == c) return 0;
if (a == b) return c;
if (a == c) return b;
if (b == c) return a;
else return a + b + c;
}
int main() { 
cout<<"\n"<<myfunc(11, 11, 11);
cout<<"\n"<<myfunc(11, 11, 16);
cout<<"\n"<<myfunc(18, 15, 10);
return 0;
}
```
----------------------------------------


# Question 77

### **Question:**

> ***Write a program to convert bytes to kilobytes.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int bytes;
cout<<"\nEnter number of bytes: ";
cin>>bytes;
cout<<"\nKilobytes: "<<(bytes/1024);
return 0;
}


```
----------------------------------------


# Question 78

### **Question:**

> ***Write a program to convert megabytes to kilobytes.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
double megabytes, kilobytes;
cout<<"\nInput the amount of megabytes to convert: ";
cin>>megabytes;
kilobytes = megabytes * 1024;
cout<<"\nThere are "<<kilobytes<< " kilobytes in " <<megabytes<< " megabytes.";
return 0;
}
```
----------------------------------------


# Question 79

### **Question:**

> ***Write a program to count the number of even elements in an integer array.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int array[1000], i, arr_size, even=0;
cout<<"Input the size of the array: ";
cin>>arr_size;
cout<<"Enter the elements in array: \n";
for(i=0; i<arr_size; i++) {
cin>>array[i];
}
 
for(i=0; i<arr_size; i++) {
if(array[i]%2==0) {
    even++;
}
}
cout<<"Number of even elements: "<< even;
return 0;
}

```
----------------------------------------


# Question 80

### **Question:**

> ***Write a program to count the number of odd elements in an integer array.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int array[1000], i, arr_size, odd=0;
cout<<"Input the size of the array: ";
cin>>arr_size;
cout<<"Enter the elements in array: \n";
for(i=0; i<arr_size; i++) {
cin>>array[i];
}
 
for(i=0; i<arr_size; i++) {
if(array[i]%2!=0) {
    odd++;
}
}
cout<<"Number of odd elements: "<< odd;
return 0;
}
```
----------------------------------------


# Question 81

### **Question:**

> ***Write a program that will accept two integers and determine whether or not they are equal.***

----------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y;
cout<<"Input the values for x and y: \n";
cin>>x;
cin>>y;
if(x == y) {
    cout<<"x and y are equal\n";
}
else {
    cout<<"x and y are not equal\n";
}
return 0;
}
```
----------------------------------------

# Question 82

### **Question:**

> ***Write a program to find the third angle of a triangle if two angles are given.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {  
int angle1, angle2; 
cout<<"\nEnter the first angle of the triangle: ";   
cin>>angle1;    
cout<<"\nEnter the second angle of the triangle: ";   
cin>>angle2; 
cout<<"\nThird angle of the triangle is: "<< (180 - (angle1 + angle2));  
return 0;  
}  
```
----------------------------------------


# Question 83

### **Question:**

> ***Write a program to determine whether a particular year is a leap year or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int year;
cout<<"Enter the year: ";
cin>>year;
if((year % 400) == 0) {
cout<<year<<" is a leap year.";
}
else if((year % 100) == 0) {
cout<<year<<" is a not leap year.";
}
else if((year % 4) == 0) {
cout<<year<<" is a leap year.";
}
else {
cout<<year<<" is not a leap year.";
}
return 0;
}
```
----------------------------------------

# Question 84

### **Question:**

> ***Write a program that reads the candidate's age and determine a candidate's eligibility to cast his own vote.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
int main() {
int age;
cout<<"\nEnter the age of the candidate: ";
cin>>age;
if(age<18) {
cout<<"\nWe apologize, but the candidate is not able to cast his vote.";
cout<<"\nAfter "<< (18-age) <<" year, the candidate would be able to cast his vote.";
}
else {
cout<<"Congratulation! the candidate is qualified to cast his vote.\n";
}
return 0;
}
```
----------------------------------------

# Question 85

### **Question:**

> ***Write a program to Convert Yard to Foot.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float yard;
cout<<"\nEnter the Length in Yard: ";
cin>>yard;
cout<<yard<<" Yard in Foot is: "<<(3*yard);
return 0;
}

```
----------------------------------------


# Question 86

### **Question:**

> ***Write a program to convert gigabytes to megabytes.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
double gigabytes, megabytes;
cout<<"\nInput the amount of gigabytes to convert: ";
cin>>gigabytes;
megabytes = gigabytes*1024;
cout<<"\nThere are "<<megabytes<<" megabytes in "<<gigabytes<<" gigabytes.";
return 0;
}

```
----------------------------------------

# Question 87

### **Question:**

> ***Write a program to Convert Kilogram to Pounds.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float kg, lbs;
cout<<"\nEnter Weight in Kilogram: ";
cin>>kg;
lbs = kg*2.20462;
cout<<kg<<" Kg = "<<lbs<<" Pounds";
return 0;
}
```
----------------------------------------


# Question 88

### **Question:**

> ***Write a program to Convert Kilogram to Ounce.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float kg, ounce;
cout<<"\nEnter Weight in Kilogram: ";
cin>>kg;
ounce = kg*35.274;
cout<<kg<<" Kg = "<<ounce<< " Ounce";
return 0;
}

```
----------------------------------------

# Question 89

### **Question:**

> ***Write a program to Convert Pounds to Grams.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float pound, gram;
cout<<"\nEnter Weight in Pounds: ";
cin>>pound;
gram = pound*453.592;
cout<<pound<<" Pound = "<<gram<<" Grams";
return 0;
}
```
----------------------------------------


# Question 90

### **Question:**

> ***Write a program  to verify whether a triangle is valid or not using angles.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
int main() {  
int angle1, angle2, angle3, sum; 
cout<<"\nEnter the first angle of the triangle: ";  
cin>>angle1;  
cout<<"\nEnter the second angle of the triangle: ";  
cin>>angle2;
cout<<"\nEnter the third angle of the triangle: ";  
cin>>angle3;
sum = angle1 + angle2 + angle3;   
if(sum == 180) {  
cout<<"\nThe triangle is valid.";  
}  
else {  
cout<<"\nThe triangle is not valid.";  
}
return 0;
} 
```
----------------------------------------

# Question 91

### **Question:**

> ***Write a program to add the digits of a two-digit number that is entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y, sum = 0;
cout<<"\nEnter a two-digit number: ";
cin>>x;
y = x;
while(y != 0) {
sum = sum + y % 10;
y = y / 10;
}
cout<<"\nSum of digits of "<<x<<" is: "<<sum;
return 0;
}

```
----------------------------------------


# Question 92

### **Question:**

> ***Write a program to verify if a character you entered is a vowel or a consonant.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char ch;
cout<<"\nEnter a character: ";
cin>>ch;
if(ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u' ||
 ch == 'A' || ch == 'E' || ch == 'I' || ch == 'O' || ch == 'U' ) {

cout<<ch<<" is a vowel";
}
else {
cout<<ch<<" is a consonant";
}
return 0;
}

```
----------------------------------------


# Question 93

### **Question:**

> ***Write a program to find factorial of a number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {    
int i, fact=1, num;    
cout<<"\nEnter a number: ";    
cin>>num;    
for(i=1; i<=num; i++) {    
      fact=fact*i;    
}    
cout<<"\nFactorial of "<<num<<" is: "<<fact;    
return 0;  
}   
```
----------------------------------------

# Question 94

### **Question:**

> ***Write a program to print number of days in a month.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x[12]={31,28,31,30,31,30,31,31,30,31,30,31}, m;
cout<<"\nEnter the month number: ";
cin>>m;
if(m>12 || m<1) {
cout<<"Invalid input";
}
else if(m==2) {
cout<<"\nNumber of days in month 2 is either 29 or 28";
}
else {
cout<<"\nNumber of days in month "<<m<< " is: "<<x[m-1];
}
return 0;
} 
```
----------------------------------------


# Question 95

### **Question:**

> ***Write a program to concatenate two strings.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<cstring>
using namespace std;
int main() {
char a[1000], b[1000];
cout<<"\nEnter the first string: ";
cin>>a;
cout<<"\nEnter the second string: ";
cin>>b;
strcat(a, b);
cout<<"\nString produced by concatenation is: "<< a;
return 0;
}

```
----------------------------------------


# Question 96

### **Question:**

> ***Write a program to find maximum between two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a,b;
cout<<"Enter two numbers: \n";
cin>>a;
cin>>b;
if(a>b) {
cout<<a<<" is a maximum number";
}
else {
cout<<b<<" is a maximum number";
}
return 0;
}
```
----------------------------------------

# Question 97

### **Question:**

> ***Write a program to compare two strings.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<cstring>
using namespace std;
int main() {
char a[100], b[100];
cout<<"Enter the first string: \n";
cin>>a;
cout<<"Enter the second string: \n";
cin>>b;
if (strcmp(a,b) == 0) {
cout<<"The 2 strings are equal.\n";
}
else {
cout<<"The 2 strings are not equal.\n";
}
return 0;
}
```
----------------------------------------

# Question 98

### **Question:**

> ***Write a program to convert the upper case letter to lower case letter.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char ch = 'G';
char b = tolower(ch);
cout<<ch<<" in lowercase is represented as "<< b;
return 0;
}
```
----------------------------------------


# Question 99

### **Question:**

> ***Write a program to find the quotient and remainder of a entered dividend and divisor.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int dividend, divisor;
cout<<"\nEnter dividend: ";
cin>>dividend;
cout<<"\nEnter divisor: ";
cin>>divisor;
cout<<"\nQuotient = "<< (dividend / divisor);
cout<<"\nRemainder = "<< (dividend % divisor);
return 0;
}
```
----------------------------------------

# Question 100

### **Question:**

> ***Write a program to determine the Size of int, float, double and char.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
cout<<"Size of char is: "<<sizeof(char)<<" byte\n";
cout<<"Size of int is: "<<sizeof(int)<<" bytes\n";
cout<<"Size of float is: "<<sizeof(float)<<" bytes\n";
cout<<"Size of double is: "<<sizeof(double)<<" bytes\n";
return 0;
}
```
----------------------------------------


# Question 101

### **Question:**

> ***Write a program to verify the password until it is correct.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int pwd, i;
while (i!=0) {
cout<<"\nEnter the password: ";
cin>>pwd;
if(pwd==1988) {
cout<<"The password you entered is correct";
i=0;
}
else {
cout<<"Incorrect password, try again";
}
cout<<"\n";
}
return 0;
}

```
----------------------------------------


# Question 102

### **Question:**

> ***Write a program to find absolute value of a number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int num; 
cout<<"Input a positive or negative number: \n";
cin>>num;
cout<<"\nAbsolute value of "<<"|"<<num<<"|"<<" is: "<<abs(num);
return 0;
} 

```
----------------------------------------


# Question 103

### **Question:**

> ***Write a program that will accept a person's height in cm and classify the person based on it.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
float ht;
cout<<"\nEnter the height (in cm): ";
cin>>ht;
if(ht < 150.0) {
cout<<"Dwarf.\n";
}
else if((ht >= 150.0) && (ht < 165.0)) {
cout<<"Average Height.\n";
}
else if((ht >= 165.0) && (ht <= 195.0)) {
cout<<"Taller.\n";
}
else {
cout<<"Abnormal height.\n";
}
return 0;
} 
```
----------------------------------------


# Question 104

### **Question:**

> ***Write a program to calculate the area of different geometric shapes using switch statements.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int choice;
float r, l, w, b, h;
cout<<"\nEnter 1 for area of circle: ";
cout<<"\nEnter 2 for area of rectangle: ";
cout<<"\nEnter 3 for area of triangle: ";
cout<<"\nEnter your choice : ";
cin>>choice;

switch(choice) {
case 1:
cout<<"Enter the radius of the circle: ";
cin>>r;
cout<<"\nArea of a circle is: " << (3.14*r*r);
break;
case 2:
cout<<"Enter the length and width of the rectangle: \n";
cin>>l;
cin>>w;
cout<<"\nArea of a rectangle is: "<<(l*w);
break;
case 3:
cout<<"Enter the base and height of the triangle: \n";
cin>>b;
cin>>h;
cout<<"\nArea of a triangle is: "<<(0.5*b*h);
break;
default:
cout<<"\nPlease enter a number from 1 to 3.";
break;
}
return 0;
}
```
----------------------------------------

# Question 105

### **Question:**

> ***Write a program to accept a character from the keyboard and print "Yes" if it is equal to y. Otherwise print "No".***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char ch;
cout<<"Enter a character: ";
ch = getchar ();
if(ch == 'y' || ch == 'Y') {
cout<<"Yes\n";
}
else {
cout<<"No\n";
}
return(0);
}
```
----------------------------------------

# Question 106

### **Question:**

> ***Write a program that uses bitwise operators to multiply an entered value by four.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
long x, y;
cout<<"Enter a integer: ";
cin>>x;
y = x;
x = x << 2;
cout<< y<<" x 4 = "<< x;
return 0;
}
```
----------------------------------------

# Question 107

### **Question:**

> ***Write a program to check whether a number entered by the user is power of 2 or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x;
cout<<"Enter a number: ";
cin>>x;
if((x != 0) && ((x &(x - 1)) == 0)) {
cout<<x<<" is a power of 2";
}
else {
cout<<x<<" is not a power of 2";
}
return 0;
}


```
----------------------------------------


# Question 108

### **Question:**

> ***Write a program to determine whether a triangle is scalene, isosceles, or equilateral.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int side1, side2, side3;
cout<<"\nEnter the first side of the triangle: ";
cin>>side1;
cout<<"\nEnter the second side of the triangle: ";
cin>>side2;
cout<<"\nEnter the third side of the triangle: ";
cin>>side3;
if(side1 == side2 && side2 == side3) {
cout<<"\nThe given Triangle is equilateral.";
}
else if(side1 == side2 || side2 == side3 || side3 == side1) {
cout<<"\nThe given Triangle is isosceles.";
}
else {
cout<<"\nThe given Triangle is scalene.";
}
return 0;
}


```
----------------------------------------


# Question 109

### **Question:**

> ***Write a program to print ASCII values of all the letters of the English alphabet from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i;
for(i='A'; i<='Z'; i++) {
cout<<"ASCII value of "<<char(i)<<"="<<int(i)<<endl;
}
return 0;
}
```
----------------------------------------


# Question 110

### **Question:**

> ***Write a program to find sum of even numbers between 1 to n.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i, num, sum=0;
cout<<"Enter a number: ";
cin>>num;
for(i=2; i<=num; i=i+2) {
sum = sum + i;
}
cout<<"\nSum of all even number between 1 to " <<num<< " is: "<< sum;
return 0;
}
```
----------------------------------------

# Question 111

### **Question:**

> ***Write a program to find sum of odd numbers between 1 to n.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i, num, sum=0;
cout<<"Enter a number: ";
cin>>num;
for(i=1; i<=num; i=i+2) {
sum = sum + i;
}
cout<<"\nSum of all odd number between 1 to " <<num<< " is: "<< sum;
return 0;
}
```
----------------------------------------

# Question 112

### **Question:**

> ***Write a program to find maximum number using switch case.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y;
cout<<"Enter any two numbers: \n";
cin>>x;
cin>>y;
switch(x > y) {
case 0: cout<<y<<" is Maximum number";
break;
case 1: cout<<x<<" is Maximum number";
break;
}
return 0;
}

```
----------------------------------------

# Question 113

### **Question:**

> ***Write a program that allows you to enter the cost price and the selling price of a product and calculate profit or loss.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int cp, sp; 
cout<<"\nInput Cost Price: ";
cin>>cp;
cout<<"\nInput Selling Price: ";
cin>>sp;
if(sp > cp) {
cout<<"Profit = "<< (sp - cp);
}
else if(cp > sp) {
cout<<"Loss = "<< (cp - sp);
}
else {
cout<<"No Profit No Loss.";
}
return 0;
}

```
----------------------------------------


# Question 114

### **Question:**

> ***Write a program that display the pattern like a right angle triangle using an asterisk.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int rows;
cout<<"Input the number of rows: ";
cin>>rows;
for(int x=1; x<=rows; x++) {
for(int y=1; y<=x; y++)
cout<<"*";
cout<<"\n";
}
return 0;
}
```
----------------------------------------


# Question 115

### **Question:**

> ***Write a program that display the pattern like a right angle triangle using a number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int rows;
cout<<"Input the number of rows: ";
cin>>rows;
for(int x=1; x<=rows; x++) {
for(int y=1; y<=x; y++)
cout<<""<<y;
cout<<"\n";
}
return 0;
}

```
----------------------------------------


# Question 116

### **Question:**

> ***Write a program to determine the number and sum of all integers between 50 and 100 which are divisible by 2.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, sum=0;
cout<<"Numbers between 50 and 100, divisible by 2: \n";
for(x=51; x<100; x++) {
if(x%2==0) {
cout<<" "<<x;
sum+=x;
}
}
cout<<"\nThe sum: "<< sum;
return 0;
}
```
----------------------------------------

# Question 117

### **Question:**

> ***Write a program that uses the function to determine whether a entered number is even or odd.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int myfunc(int x) {   
return (x & 1);
}
int main() {
int x;
cout<<"Enter any number: ";
cin>>x;
if(myfunc(x)) {
cout<<"\nThe number you entered is odd.";
}
else {
cout<<"\nThe number you entered is even.";
}
return 0;
}

```
----------------------------------------


# Question 118

### **Question:**

> ***Write a program to find square root of a entered number.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<cmath>
using namespace std;
int main() {
int x;
cout<<"Enter any number: ";
cin>>x;
cout<<"Square root of "<<x<< " is: "<<(double)sqrt(x);
return 0;
}
```
----------------------------------------

# Question 119

### **Question:**

> ***Write a program to find power of a entered number using library function.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<cmath>
using namespace std;
int main() {
int x, y;
cout<<"\nEnter the value for x: ";
cin>>x;
cout<<"\nEnter the value for y: ";
cin>>y;
cout<<x<<"^"<<y<<" = " << (long)pow(x,y);
return 0;
}
```
----------------------------------------


# Question 120

### **Question:**

> ***Write a program to determine if the character entered is an alphabetic or numeric character.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char ch;
cout<<"Enter a character: ";
cin>>ch;
if(isdigit(ch)) {
cout<<ch<<" is a Digit";
}
else if(isalpha(ch)) {
cout<<ch<<" is an Alphabet";
}
else {
cout<<ch<<" is not an Alphabet, or a Digit";
}
return 0;
}

```
----------------------------------------


# Question 121

### **Question:**

> ***Write a program to determine whether the character entered is an alphanumeric character or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char a;
cout<<"Enter a character: ";
cin>>a;
if(isalnum(a)) {
cout<<a<<" is an alphanumeric character.";
}
else {
cout<<a<<" is NOT an alphanumeric character.";
}
return 0;
}

```
----------------------------------------

# Question 122

### **Question:**

> ***Write a program to determine whether the character entered is an punctuation character or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char a;
cout<<"Enter a character: ";
cin>>a;
if(ispunct(a)) {
cout<<a<<" is an punctuation character.";
}
else {
cout<<a<<" is NOT an punctuation character.";
}
return 0;
}
```
----------------------------------------


# Question 123

### **Question:**

> ***Write a program to check whether the entered character is a graphic character or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char a;
cout<<"Enter a character: ";
cin>>a;
if(isgraph(a)) {
cout<<a<<" is a graphic character.";
}
else {
cout<<a<<" is NOT a graphic character.";
}
return 0;
}
```
----------------------------------------


# Question 124

### **Question:**

> ***Write a program to list all printable characters using isprint() function.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i;
for(i = 1; i <= 127; i++) 
if(isprint(i)!= 0)
cout<<" "<<char(i);
return 0;
}

```
----------------------------------------


# Question 125

### **Question:**

> ***Write a program to check whether the entered character is a hexadecimal digit character or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char a;
cout<<"Enter a character: ";
cin>>a;
if(isxdigit(a)) {
cout<<a<<" is a hexadecimal digit character.";
}
else {
cout<<a<<" is NOT a hexadecimal digit character.";
}
return 0;
}

```
----------------------------------------

# Question 126

### **Question:**

> ***Write a program to print ASCII value of all control characters.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int i;
cout<<"The ASCII value of all control characters are: \n";
for(i=0; i<=127; i++) {
if(iscntrl(i)!=0)
cout<<"\n  "<< i;
}
return 0;
}


```
----------------------------------------

# Question 127

### **Question:**

> ***Write a program to check whether the given character is a white-space character or not.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include <iostream>
using namespace std;
int main() {
char c;
char ch = ' ';
if(isspace(ch)) {
    cout << "\nNot a white-space character.";
} 
else {
    cout << "\nWhite-space character.";
}
return 0;
}
 
```
----------------------------------------


# Question 128

### **Question:**

> ***Write a program to illustrate isprint() and iscntrl() functions.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
char ch = 'a';
if(isprint(ch)) {
cout<<ch<<" is printable character."<<endl;
} 
else {
cout<<ch<<" is not printable character."<<endl;
}

if(iscntrl(ch)) {
cout<<ch<<" is control character."<<endl;
} 
else {
cout<<ch<<" is not control character."<<endl;
}
return (0);
}
```
----------------------------------------



# Question 129

### **Question:**

> ***Write a program to calculate surface area of cube.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int side;
long area;
cout<<"\nEnter the side of cube: ";
cin>>side;
area = 6*side*side;
cout<<"\nThe surface area of cube is: "<< area;
return 0;
}
```
----------------------------------------


# Question 130

### **Question:**

> ***Write a program to subtract 2 numbers without using subtraction operator.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x =6, y=3;
cout<<x+(~y)+1;
return 0;
}
```
----------------------------------------


# Question 131

### **Question:**

> ***Write a program to add 2 numbers without using addition operator.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x =6, y=3;
cout<<x-(~y)-1;
return 0;
}
```
----------------------------------------

# Question 132

### **Question:**

> ***Write a program to multiply a number by 2 without using multiplication operator.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x=2;
cout<< (x<<1);
return 0;
}
```
----------------------------------------

# Question 134

### **Question:**

> ***Write a program to divide a number by 2 without using division operator.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x=12;
cout<< (x>>1);
return 0;
}
```
----------------------------------------

# Question 135

### **Question:**

> ***Write a program to calculate volume of sphere.***

---------------------------------------

<strong>Solution: </strong>

```C++ language

#include<iostream>
using namespace std;
int main() {
int radius;
float PI = 3.141592;
cout<<"\nEnter the radius of sphere: ";
cin>>radius;
float volume = (4/3)*(PI*radius*radius*radius);
cout<<"\nThe volume of sphere is: "<< volume;
return 0;
}
```
----------------------------------------


# Question 136

### **Question:**

> ***Write a program to calculate volume of ellipsoid.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int r1, r2, r3;
float PI = 3.141592;
cout<<"\nEnter the radius of the ellipsoid of axis 1: ";
cin>>r1;
cout<<"\nEnter the radius of the ellipsoid of axis 2: ";
cin>>r2;
cout<<"\nEnter the radius of the ellipsoid of axis 3: ";
cin>>r3;
float volume = (4/3)*(PI*r1*r2*r3);
cout<<"\nThe volume of ellipsoid is: "<< volume;
return 0;
}
```
----------------------------------------

# Question 137

### **Question:**

> ***Write a program that uses a for loop to determine power of a number entered by the user.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int x, y;
long power = 1;
cout<<"\nEnter the value for x: ";
cin>>x;
cout<<"\nEnter the value for y: ";
cin>>y;
for(int i=1; i<=y; i++) {
power = power * x;
}
cout<<x<<"^"<<y<<" = "<<power;
return 0;
}
```
----------------------------------------


# Question 138

### **Question:**

> ***Write a program to read three numbers and find average of numbers.***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
using namespace std;
int main() {
int a,b,c;
float avg;
cout<<"\nEnter the first number: ";
cin>>a;
cout<<"\nEnter the second number: ";
cin>>b;
cout<<"\nEnter the third number: ";
cin>>c;
avg=(a+b+c)/3.0;
cout<<"\nAverage of three numbers is: "<< avg;
return 0;
}
```
----------------------------------------


# Question 139

### **Question:**

> ***Write a program to read integer "n" and print first three powers (n<sup>1</sup>, n<sup>2</sup>, n<sup>3</sup>).***

---------------------------------------

<strong>Solution: </strong>

```C++ language
#include<iostream>
#include<cmath>
using namespace std;
int main() {
int n;
cout<<"\nEnter a number: ";
cin>>n;
cout<<pow(n, 1)<<" "<< pow(n, 2)<<" "<< pow(n, 3);
return 0;
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
	
