# IT24017_First-30-days-work
Date:4/19/26
Day:1
Topic: CLASS & OBJECT
Vedio link:

Creating a Class:-
EXAMPLE 1:
Public Class Car {
String color;
String model;
int year;
void displayInfo () {
System.out.println("car Model: " + model);
System.out.println("car Color: " + color);
System.out.println("car Year: "  + year);
}
}

EXAMPLE 2:
Creating a subclass:-

class Animal {
   void eat() {
    System.out.println("Eat");
    }
}
class Dog extends Animal {
  void bark() {
  System.out.println("Bark");
    }
}
public class Main {
public static void main(String[] args) {
        Dog d = new Dog();
        d.eat();
        d.bark();
    }
}

EXAMPLE 3:-
Creating an object
public class Main{
public static void main(String[] arge){
myCar = new Car();
myCar.color = "Read";
myCar.model = "Toyota";
myCar.year = 2020;
myCar.displayInfo();
}
}

EXAMPLE 4:-
Public access modifier:
public class Car {
public String model;
}

EXAMPLE 5:-
Private modifier:
public class Car{
private String color;
private void displayColor(){
System.out.println("Car color: " + color);
}
}

EXAMPLE 6:-
Default modifier:-
class Car{
String model;
void displayModel(){
System.out.println("Car Model: " + model);
}
}

EXAMPLE 7:-
Static modifier:-
Public class Car {
static int numberOfCars = 0;
public car() {
numberOfCars++;
}
static void displayCount() {
System.out.println("Total Cars: " + numberOfCars);
}
}

