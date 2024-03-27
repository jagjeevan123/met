1.Write a Java Program of constructor and method.
class Box
{
int length, breadth, height; // Class Variable
Box (int l, int b, int h) //Constructor
{
length = l;
breadth = b;
height = h;
}
void display() //Method
{
int volume=length*breadth*height;
System.out.println ("Volume of Box is= "+volume);
}
}
class Demo1
{
public static void m
ain(String M[])
{
Box b1=new Box (10, 20, 30);
Box b2=new Box (100, 200, 300);
b1.display();
b2.display();
}
}

13. Write a Java Program of Abstract class.
abstract class Shape
{ 
 abstract void show(); 
} 
class Rectangle extends Shape
{ 
 void show()
 {
 System.out.println ("I am rectangle");
 } 
} 
class Circle extends Shape
 { 
 void show()
 {
 System.out.println ("I am circle");
 } 
} 
class Test
{ 
public static void main (String M[])
 { 
 Shape s=new Circle(); //Reference
 s.show(); 
Shape s1=new Rectangle(); //Reference
 s1.show();
 } 
} 


