# **Const uses**
## **Declaring Constant values**
When declaring a variable that will be constant through the code you use `const` to tell the compiler to prevent the programmer from changing it.<br>
The syntax:
```
const int x=5;
```
Note: The const variable must be intialized at decleration time.<br><br>

## **Const Pointers**
Constant in pointers are used in 2 ways; either prevent changing the data pointed to, or prevent changing what the pointer is pointing to.<br>
1. To make the address stored in the pointer itself constant add const after * as following: <br><br>
The syntax:
   ```
   int x;
   int * const ptr = &x;
   ```
2. Declaring a pointer to constant data: <br><br>
The syntax:
   ```
   const int *ptr;
   ```
<br>

## **Instead of #define:** 
Const keyword instead of the #define preprocessor directive to define constant values. <br><br>

## **Const Objects:**
An object of a class may be declared constant as the variables, and this object cannot be modified<br>
The syntax:
```
const Date Birthday(1, 3, 1999);
```
<br>

## **Const Methods:**
Const object cal only call const Methods, these methods make the object cannot bs modified. Const methods are "read-only".<br>
The syntax:
```
const Class_Name Object_name;
```
<br><br><br>

# **Ampersand Uses:**

## **In Logical Expressions:**
& is used to say AND in th code.<br>
The syntax:
```
if (i > 3 && j < 0 )
    cout << "The expression is true.";
```
<br>

## **In Reference:**

When a variable is declared as a reference, it becomes an alternative name for an existing variable. A variable can be declared as a reference by putting ‘&’ in the declaration. <br>
The syntax:
```
int x = 10;
int& ref = x;
```
## **Variable Address:**
& is used to get the address that a variable is stored in the memory.<br>
The Syntax:
```
int x = 10;
int *y;
y=&x;
cout<<y;
```
The output will be as follow:
```
0113F828
```
<br>



