# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: SRINIVASAN V
RegisterNumber: 212222043008  
*/
```

## Sourcecode.java:
```
class Animal {
    public void eat() {
        System.out.println("I can eat");
    }
}

class Person extends Animal {
    public void name() {
        System.out.println("My name is Rohu");
    }
}

public class Main extends Person {
    public static void main(String[] args) {
        Main obj = new Main();
        obj.name();
        obj.eat();
    }
}
```
## OUTPUT:
<img width="434" height="196" alt="438032100-1846d70a-097b-4b4d-a830-f0f1da459732" src="https://github.com/user-attachments/assets/89e00fdc-4b23-4e9e-90f1-1fb93fa986a9" />




## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
