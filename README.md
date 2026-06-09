# Ejercicio

using System;

class Car
{
    string color; //campo en blanco
    int maxSpeed; // campo en blanco

static void Main(string[] args)
{
// dentro del Main();
Car myObj = new Car();
myObj.color = "red";
myObj.maxSpeed = 200; 

Console.WriteLine (myObj.color);
Console.WriteLine (myObj.maxSpeed);

}
}

//-------------------------------------------
using System;

class Car 
{
    public string model;
    public string color;
    public int year;
}

class Program
{
    
    static void Main(string[] args) 
    {
       
        Car ford = new Car(); 
        ford.model = "Mustang";
        ford.color = "red";
        ford.year = 1969;

        
        Car opel = new Car();
        opel.model = "Astra";
        opel.color = "White"; 
        opel.year = 2005;
        
      
        Console.WriteLine(opel.model);
        Console.WriteLine(opel.color);
        Console.WriteLine(opel.year);
    }
}

//--------------------------------------------------

using System;

class MyClass 
{
    public void fullthrottle() 
    {
       Console.WriteLine("the car is going as fast as it can!"); 
    }
    public string color = "red"; 
    public int maxSpeed = 200;   
    
    static void Main(string[] arg)
    {
      
        MyClass myObj = new MyClass();
        
        Console.WriteLine(myObj.color);
        Console.WriteLine(myObj.maxSpeed);
         
       
        myObj.fullthrottle();
    }
}

//------------------------------------------------------------------------------------------

using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        string firstName = "John ";
string lastName = "Doe";
string fullName = firstName + lastName;
Console.WriteLine(fullName);

    }
}

//------------------------------------------------------------------------------------------

using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
       int x, y, z;
       x = y = z = 50;
       Console.WriteLine(x + y + z);

    }
}

//---------------------------------------------------------------------------------------------------

using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
      int x = 20;
int y = 18;
if (x > y) 
{
  Console.WriteLine("x is greater than y");
}
    }
}

//------------------------------------------------------------------------------------------------------

class Car 
{
  string color;
  int maxSpeed;

  static void Main(string[] args)
  {
    Car myObj = new Car();
    myObj.color = "red";
    myObj.maxSpeed = 200;
    Console.WriteLine(myObj.color);
    Console.WriteLine(myObj.maxSpeed);
  }
}

//------------------------------------------------------------------------------------------------


