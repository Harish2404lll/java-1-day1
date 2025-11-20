# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a Student object and assign values to roll_no and name inside the main() method.

## ALGORITHM :
1.	Define a class named Student.
2.	Declare a String variable name and initialize it with "John".
3.	Declare a String variable address and initialize it with "Chennai".
4.	Define a class named Test.
5.	Inside the Test class, define the main() method.
6.	Create an object obj of the Student class.
7.	Print the values of obj.name and obj.address.
8.	End.



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: Harish G
RegisterNumber:  212222243001
*/
```

## Sourcecode.java:
```
    public static void main(String[]args){
    Student obj = new Student();
    obj.roll_no = "21CSE03";
    obj.name = "John";
    
    System.out.println(obj.roll_no+" "+obj.name);
    }
```



## OUTPUT:
<img width="477" height="234" alt="image" src="https://github.com/user-attachments/assets/93db85e4-7544-441f-b8d9-494da0448e16" />



## RESULT:
Thus, the class Student with the String variables name and address was created successfully.
