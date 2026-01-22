# EXPERIMENT2
## TITLE:2a.)implement class mechanism in java
```
#experiment2
## TITLE: 2a.) Implement class mechanism in java 
```
class myclass {
void displaymessage() {
System.out.println("welcome to java");
}
int add (int a, int b) {
return a+b;
}
public static void main(String[] args) {
myclass obj = new myclass();
obj.displaymessage();
int result = obj.add(10, 20);
System.out.println("sum: " + result);
}
}
```
# OUTPUT
![2a output](https://github.com/user-attachments/assets/c5a07a4f-7b4d-4ac5-b4ed-cfa3a5ab4cb2)

## TITLE: 2b.) java program implement method overloading
```
class OverloadExample {
int add(int a, int b) {
return (a + b);
}
double add(double a, double b) {
return a + b;
}
int add(int a, int b, int c) {
return a + b + c;
}
public static void main(String[] args) {
OverloadExample obj = new OverloadExample();
int sum1 = obj.add(10, 20);
double sum2 = obj.add(5.5, 6.5);
int sum3 = obj.add(10, 20, 30);
System.out.println("Result of adding two integers: " + sum1);
System.out.println("Result of adding two double values: " + sum2);
System.out.println("Result of adding three integers: " + sum3);
}
}
```
# OUTPUT
![2b output](https://github.com/user-attachments/assets/202910bb-3ffd-482f-b7e7-19d44fefa78b)

## TITLE: 2c.) java program implement constructor
```
class Student {
String name;
int age;
int marks;
Student (String n, int a, int m) {
name = n;
age = a;
marks = m;
}
void display ( ) {
System.out.println ("Name: " + name);
System.out.println ("Age: " + age);
System.out.println ("Marks: " + marks);
}
public static void main(String[] args) {
Student S1 = new Student ("Alice", 20, 85);
S1.display ( );
}
}
```
# OUTPUT
![2c output](https://github.com/user-attachments/assets/acb9b1e3-416c-403d-9fc5-247c2ebe0c99)
