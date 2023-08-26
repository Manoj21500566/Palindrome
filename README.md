# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.

## Algorithm:

Step1: Start the Program.

Step2: Create a class and declare two variable with string datatype

Step3: Loop over the entire string and reverse it

Step4: Use if condition to check whether the string and the reversed string is equal or not.

Step5: Print palindrome if it's equal else print not a palindrome.

Step6: Stop the Program.

## Program:
~~~
DEVELOPED BY : Manoj M
REGISTER NO : 212221240027
using System;
namespace palindrome
{
    class stringl
    {
        public static void Main(string[] args)
        {
            string str,rev="";
            int n;
            Console.WriteLine("Enter a String :");
            str = Console.ReadLine();
            n = str.Length - 1;
            for(int i =n; i >=0; i--)
            {
                rev = rev + str[i];
            }
            if(rev==str)
            
                Console.WriteLine("{0} is Palindrome", str);
            else
                    Console.WriteLine("{0} is not Palindrome", str);
            
        }
    }
}
~~~
## Output:

![1](https://github.com/Manoj21500566/Palindrome/assets/94588708/cc3648f0-cf65-4e4e-b881-861a674df6ba)


![2](https://github.com/Manoj21500566/Palindrome/assets/94588708/81d76078-cf14-4526-83b1-b50eb9ca8b7b)



## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
