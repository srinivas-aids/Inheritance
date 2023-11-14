# Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance.
## Algorithm:
step 1:
Create a base class.

step 2:
Create two child class.

step 3:
Create a constructor in the base class and print a message.

step 4:
create a function in child class to print a message.

## Program:
```
using System;
namespace unit1
{
    public class vehicle
    {
        public vehicle()
        {
            Console.Write("tyre is attached");
        }

    }
    public class car : vehicle
    {
        public void display()
        {
            Console.Write(" to car");
        }
    }
    public class scooter : vehicle
    {
        public void display()
        {
            Console.Write(" to scooter");
        }
    }
    public class program
    {
        public static void Main(string[] args)
        {
            car car = new car();
            car.display();
            Console.WriteLine();
            scooter scooter = new scooter();
            scooter.display();
            Console.ReadKey();
        }
    }
}
```

## Output:
![image](https://github.com/Bhuvaneshwari-2003/Inheritance/assets/94828604/f8bd7419-9ad9-432b-a00c-d20b028c6042)


## Result:
C# program to print some messages using hierarchical inheritance is implemented successfully.
