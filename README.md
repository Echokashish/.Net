Practical-1

1. Write a program to display your name and your course name.
   Code:  using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("My name is Kashish Varma");
            Console.WriteLine("My course name is BCA");
        }
    }
}

Output:

<img width="342" height="72" alt="image" src="https://github.com/user-attachments/assets/842e05e2-f5de-4df9-a71d-9122bbb49da2" />


2. Write a C# program to declare and initialize variables of the
different data types and display their values.
Code:  using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int age = 20;               
            char grade = 'A';          
            string name = "Kashish";    
            bool isstudent = true;      
            double cgpa = 7.68;         

            Console.WriteLine("Name: " + name);
            Console.WriteLine("Age: " + age);
            Console.WriteLine("Student: " + isstudent);
            Console.WriteLine("Grade: " + grade);
            Console.WriteLine("CGPA: " + cgpa);
            Console.ReadLine();
        }
    }
}

Output:

<img width="191" height="136" alt="image" src="https://github.com/user-attachments/assets/4a527d12-1903-4111-817b-fb2843d2b90a" />


3. Write a C# program to demonstrate implicit type conversion from int to double. Display both values.
   Code:  using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int num = 101;
            double result = num;
            Console.WriteLine("Integer value: " + num);
            Console.WriteLine("Double value after implicit conversion: " + result);
            Console.ReadLine();
        }
    }
}

Output:  

<img width="536" height="75" alt="image" src="https://github.com/user-attachments/assets/21db64a2-1e41-47e3-8e12-7024bf578362" />


4. Write a C# program to demonstrate explicit type conversion from double to int. Display both values.
 Code: using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int num = 101;
            int result = (int)num;
            Console.WriteLine("Integer value: " + num);
            Console.WriteLine("Int value after explicit conversion: " + result);
            Console.ReadLine();
        }
    }
}

Output: 

<img width="514" height="64" alt="image" src="https://github.com/user-attachments/assets/fb596e82-e8bc-4fbc-a61b-87b26a9168c1" />


5. Write a C# program to input marks of two subjects and display their total marks.
    Code:  using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter marks of Subject 1: ");
            int marks1 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter marks of Subject 2: ");
            int marks2 = Convert.ToInt32(Console.ReadLine());
            int total = marks1 + marks2;
            Console.WriteLine("Total Marks: " + total);
            Console.ReadLine();
        }
    }
}

Output: 

<img width="360" height="89" alt="image" src="https://github.com/user-attachments/assets/ac98e459-4889-4c62-bf5b-7b1f9485ae6d" />


6. WAP to swap the values of two variables: price1 and price2.
   Code:  using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int price1 = 100;
            int price2 = 200;
            Console.WriteLine("Before Swapping");
            Console.WriteLine("Price1 = " + price1);
            Console.WriteLine("Price2 = " + price2);
            int temp = price1;
            price1 = price2;
            price2 = temp;
            Console.WriteLine("After Swapping");
            Console.WriteLine("Price1 = " + price1);
            Console.WriteLine("Price2 = " + price2);
            Console.ReadLine();
        }
    }
}

Output:

<img width="220" height="151" alt="image" src="https://github.com/user-attachments/assets/e1cd51c2-145f-4aa3-b694-4bf91d888a68" />


7. WAP to check whether the entered roll number is even or odd.
    Code:   using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter your roll number: ");
            int rollNumber = Convert.ToInt32(Console.ReadLine());
            if (rollNumber % 2 == 0)
            {
                Console.WriteLine("The roll number is Even.");
            }
            else
            {
                Console.WriteLine("The roll number is Odd.");
            }
        }
    }
}

Output: 

<img width="347" height="53" alt="image" src="https://github.com/user-attachments/assets/e90ccc29-ff7e-45f6-8f5e-b9e654b3e06d" />


8. WAP to calculate the area of a square when side length is given.
   Code:  using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter the side length of the square: ");
            int side = Convert.ToInt32(Console.ReadLine());
            int area = side * side;
            Console.WriteLine("Area of the square: " + area);
        }
    }
}

Output: 

<img width="510" height="65" alt="image" src="https://github.com/user-attachments/assets/66ca6a1c-036d-4ffa-8fb7-bd383bd1f5a7" />


9. Write a C# program to perform boxing of an int value to an object type and display the object value.
    Code:  using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int number = 42;
            object boxedNumber = number;
            Console.WriteLine("Original int value: " + number);
            Console.WriteLine("Boxed object value: " + boxedNumber);
            Console.ReadLine();
        }
    }
}

Output: 

<img width="299" height="64" alt="image" src="https://github.com/user-attachments/assets/d4d9c067-3f65-4316-b137-4e68a4e8528b" />


10. Write a C# program to perform unboxing of an object (containing int value) to an int variable and display the int value.
    Code:   using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            object boxedValue = 100;
            int number = (int)boxedValue;
            Console.WriteLine("Boxed object value: " + boxedValue);
            Console.WriteLine("Unboxed int value: " + number);
            Console.ReadLine();
        }
    }
}

Output:

<img width="308" height="54" alt="image" src="https://github.com/user-attachments/assets/0ed40094-3452-4585-a815-739a5b9e3b4e" />


11. Write a C# Sharp program to read the age of a candidate and determine whether it is eligible for casting his/her own vote.
    Code:  using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kashish.net
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter your age: ");
            int age = Convert.ToInt32(Console.ReadLine());
            if (age >= 18)
            {
                Console.WriteLine("You are eligible to vote.");
            }
            else
            {
                Console.WriteLine("You are not eligible to vote.");
            }
            Console.ReadLine();
        }
    }
}

Output:  

<img width="314" height="57" alt="image" src="https://github.com/user-attachments/assets/1e1c18d2-e609-4d61-9328-57ffddbf19ae" />
