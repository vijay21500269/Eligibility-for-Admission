# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:

Step 1 :
Import the 'System' namespace to use the classes present in the 'System' namespace.

Step 2 :
Declare the Main method.

Step 3 :
Declare name variable in string format and marks variable in integer format.

Step 4 :
Using " Console.Write " print the statement and get the input from user using " Console.ReadLine " .

Step 5 :
Add the 3 subject marks and store it in sum_of_three. Add the marks of physics and maths and store it in sum_of_two.

Step 6 :
Using Nested if loop check whether the student is eligible or not eligible for engineering admission with the conditions given.

Step 7 :
Print the result.

## Program:
```
using System;
namespace eligible
{
    class marks
    {
        public static void Main(string[] args)
        {
            int mat, phy, chem,sum_of_three,sum_of_two;
            string name;
            Console.WriteLine("Enter the name");
            name = Console.ReadLine();
            Console.WriteLine("Enter the Math mark");
            mat = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the Physics mark");
            phy = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the Chemistry mark");
            chem = Convert.ToInt32(Console.ReadLine());
            sum_of_three = mat + phy + chem;
            sum_of_two = mat + phy;
            if((mat>=65)&&(phy>=55)&&(chem>=50))
                {
                if((sum_of_three>=180)||(sum_of_two>=140))
                {
                    Console.WriteLine("{0} is Eligible for admission",name);
                }
                else
                {
                    Console.WriteLine("{0} is Not Eligible for admission", name);
                }

            }
            else
            {
                Console.WriteLine("{0} is Not Eligible for admission",name);
            }
        }
    }
}
```

## Output:

![o1](https://user-images.githubusercontent.com/94381788/225391375-4ff54679-2901-4587-bfd2-c8dafc8cbc57.jpg)




## Result:

Thus a C# program to find the eligibility for admission to an engineering course is written and executed.


