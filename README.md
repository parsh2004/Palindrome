# Palindrome
## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:

### Step 1:
To start the C# program in visual Studio 2022.

### Step 2:
Create a class and declare two variable with string datatype.

### Step 3:
Loop over the entire string and reverse it.

### Step 4:
Use if condition to check whether the string and the reversed string is equal or not.
### Step 5:
print palindrome if it's equal else print not a palindrome.

### Step 6:
Save the program and run the program in visual studio 2022.


## Program:
~~~
using System;
namespace exp2
{
    public class Palindrome
    {
        static void Main(string[] args)
        {
            string word, reverse="";
            word = Convert.ToString(Console.ReadLine());
            Console.WriteLine("before reverse:"+word);
            for (int i=word.Length-1; i>=0; i--)
            {
                reverse += word[i];
            }
            if(reverse == word)
            {
                Console.WriteLine("{0} it is palindrome",reverse);
            }
            else
            {
                Console.WriteLine("{0} its not palindrome",reverse);
            }
            Console.ReadLine();
        }
    }
}

~~~

## Output:
### its palindrom:
![output](img1.png)
### its not a palindrom:
![output](img2.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
