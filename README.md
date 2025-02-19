Outputting Characters from a String
String myString = "Chaf";
System.out.println(myString.charAt(2));

Output:
a

String myString = "Chaf";
System.out.println(myString.charAt(0));

Output:
C


Task
1.Write a program which does the following:

Create a string variable word and assign the text "Programming" to it.
Print the characters o and r (only one) from the string word in separate lines using the syntax defined above.

class Codechef
{
	public static void main (String[] args)
	{
		String word= "Programming";
        System.out.println(word.charAt(2));
        System.out.println(word.charAt(1));

	}
}
Your Output
o
r


Changing Characters in a String
String word = "CodeShef";
char[] wordArray = word.toCharArray();
wordArray[4] = 'C';

Task
2.Write a program which does the following:

Initialise a string variable word and assign the value "Ocygen" to it.
You now want to fix the typo in the given string.
Use the syntax learnt previously to replace 'c' with 'x' in the variable word.
Output the updated word to console.
class Codechef
{
	public static void main (String[] args)
	{
		// Update the blank in code given below
		String word = "Ocygen";
        char[] wordArray = word.toCharArray();
        wordArray[1] = 'x';
        word = new String(wordArray);
        System.out.println(word);
	}
}

Your Output
Oxygen

string Operations
Let us finish this module with some more practice!

3.Write a program which does the following:

Declare a string variable var.
Assign the value "String" to it.
And then print to the console the first 3 characters of the string.
Do not include any space or new line.
When you run the code, you will get a compilation error - go ahead and debug the code as well.

class Codechef
{
	public static void main (String[] args)
	{
		String var = "String";
        char[] varArray=var.toCharArray();
        varArray[0]= 's';
        var=new String(varArray); 
        System.out.print(varArray[0]);
        System.out.print(varArray[1]);
        System.out.print(varArray[2]);
	}
}
Your Output
str

Taking user input
import java.util.Scanner;
Scanner objName = new Scanner(System.in);
String varName = objName.nextLine();

4.class Codechef
{
	public static void main (String[] args)
	{
		
		Scanner John = new Scanner(System.in);
		String varName = John.nextLine();
		System.out.println(varName);
	}
}
Sample Input
John
Your Output
John

Calculator
Complete the given program to create a simple calculator that performs addition and subtraction.

5.Declare 2 integer variables a and b
Initialize the variables a and b with two user inputs.
Declare an integer variable sum - and assign the value of addition of a and b to it.
Declare another integer variable diff - and assign the value of subtraction of a and b to it.
Output sum and diff to the console on separate lines with the same message as given in sample output.
Sample 1:
Input
Output
35
23
Sum is: 58
Difference is: 12

import java.util.Scanner;

class Codechef
{
	public static void main (String[] args)
	{
		// Update the blank in the code below
		Scanner read = new Scanner(System.in);
		int a =35;
		int b =23;
		int sum = a+b;
		int diff =a-b;
		System.out.println("Sum is: " + sum);
		System.out.println("Difference is: " + diff);
	}
}
Sample Input
35
23
Your Output
Sum is: 58
Difference is: 12
\Hello user
Write a program which does the following:

Declare a string variable x.
Accept a text user input - the name of the user - and store it in the variable x.
Output and print to the console "Hello" before the user defined name.
Remember to add a space between "Hello" and x.
Sample 1:
Input
Output
Chef
Hello Chef

import java.util.Scanner;

6.class Codechef
{
	public static void main (String[] args)
	{
		// Update the blank in the code below
		Scanner read = new Scanner(System.in);
		String x = read.nextLine();
		System.out.println("Hello " + x);
	}
}
Sample Input
Chef
Your Output
Hello Chef

Find the Area of any rectangle
Let us revisit our favourite rectangle and its area problem.

7.Write a program which does the following:

Declare 2 integer variables length and width.
In this problem - accept 2 user defined inputs from the console and initialise these values length and width.
Create another integer variable area - compute the area of the rectangle and store it as area.
Output area to the console.
Sample 1:
Input
Output
10
23
Area of the rectangle is: 230
import java.util.Scanner;

class Codechef
{
	public static void main (String[] args)
	{
	   // Update the blank in code below
		Scanner read = new Scanner(System.in);
        int length = read.nextInt();
        int width = read.nextInt();

        int area =10* 23;

        System.out.println("Area of the rectangle is: " + area);
	}
}
Sample Input
10
23
Your Output
Area of the rectangle is: 230

Cubes and Squares
Write a program which does the following:

Declare an integer variable a.
Accept a user input and store it in the variable a.
Declare 2 variables square and cube - compute and store the square and cube of a in them.
Output square and cube to the console on separate lines.
Note:
Square of an integer N = N * N.
Cube of an integer N = N * N * N.
Sample 1:
Input
Output
3
Square is: 9
Cube is: 27

8.import java.util.Scanner;

class Codechef
{
	public static void main (String[] args)
	{
		Scanner read = new Scanner(System.in);
		int num = read.nextInt();
		System.out.println("Square is: " + (num * num));
		System.out.println("Cube is: " + (num * num * num));
	}
}
Sample Input
3
Your Output
Square is: 9
Cube is: 27

Mile to Kilometer Convertor
Write a program which does the following:

Create a Convertor that converts miles into kilometers.(1 Mile = 1.60 KM).
Declare an integer variable mile.
Accept user input and store it in mile.
Declare a double variable km.
Compute and output distance in kilometers console.
Sample 1:
Input
Output
2
3.2

9.import java.util.Scanner;

class Codechef
{
	public static void main (String[] args)
	{
		// Update the blank in the code given below
		Scanner read = new Scanner(System.in);
		int mile = read.nextInt();
		double km = 1.60 * mile;
		System.out.println(km);
	}
}
Sample Input
2
Your Output
3.2



10.import java.util.*;

class Codechef
{
	public static void main (String[] args)
	{
	   // Update the blank in the code given below
		Scanner read = new Scanner(System.in);
        int num = read.nextInt();

        System.out.println(num + " x 1 = " + (num * 1));
        System.out.println(num + " x 2 = " + (num * 2));
        System.out.println(num + " x 3 = " + (num * 3));
        System.out.println(num + " x 4 = " + (num * 4));
        System.out.println(num + " x 5 = " + (num * 5));
        System.out.println(num + " x 6 = " + (num * 6));
        System.out.println(num + " x 7 = " + (num * 7));
        System.out.println(num + " x 8 = " + (num * 8));
        System.out.println(num + " x 9 = " + (num * 9));
        System.out.println(num + " x 10 = " + (num * 10));

	}
}
Sample Input
4
Your Output
4 x 1 = 4
4 x 2 = 8
4 x 3 = 12
4 x 4 = 16
4 x 5 = 20
4 x 6 = 24
4 x 7 = 28
4 x 8 = 32
4 x 9 = 36
4 x 10 = 40

If & Else Statements
Task
Write a program which does the following:

Let's think of a real-life example where we need to find out if a person is old enough to vote.
Find out if the age (25) is greater than OR equal to the voting age limit, which is set to 18.
Declare the variables age and voting_age - and initialize them to the values 25 and 18 - i.e. the age and the voting age respectively.
Compare age and voting_age using the syntax given above and output the following
"Old enough to vote!" if age is greater than or equal to voting_age
"Not old enough to vote." if age is lesser than voting_age

11.class Codechef
{
	public static void main (String[] args)
	{
	   // Update the blank in the code given below
		int Age = 25;
        int Vage = 18;

        if (Age >= Vage) {
            System.out.println("Old enough to vote!");
        } else {
            System.out.println("Not old enough to vote.");
        }
	}
}
Your Output
Old enough to vote!

12.class Codechef
{
	public static void main (String[] args)
	{
	   // Debug the code given below
	    int age = 25;
        int voting_age = 18;

        if (age < voting_age)
        {
            System.out.println("Not old enough to vote.");
            System.out.println("Wait for " + (voting_age - age) + " years");
        }

        else {
            System.out.println("Old enough to vote!");
        }
	}
}
Your Output
Old enough to vote!

13.Task
Write a program which does the following:

Take input for two integer variables a and b.
Output Coding is Fun! to the console if a is greater than b.
Sample 1:
Input
25
20
Output
Coding is Fun!
Sample 2:
Input
Output

import java.util.Scanner;

class Codechef
{
	public static void main (String[] args)
	{
        int a=25;
        int b=20;
        if(a>b)
        {
            System.out.println("Coding is Fun!");
        }
        else
        {
            System.out.println("Coding is not Fun");
        }
	}
}
Sample Input
25
20
Your Output
Coding is Fun!

14.Task
Some code is written in the editor.

Two variables r and k are defined.
Output based on these conditions:
If r is greater than k, output "Ram is heavier than Karan"
If r is less than k, output "Karan is heavier than Ram"
Otherwise, output "Ram & Karan have the same weight!"


import java.util.*;

class Codechef
{
	public static void main (String[] args)
	{
	   // Update the blank in the code given below
	    int r;
        int k;
        r = 24;
        k = 32;
        if (r > k) {
            System.out.println("Ram is heavier than Karan.");
        } else if (r < k) {
            System.out.println("Karan is heavier than Ram");
        } else {
            System.out.println("Ram & Karan have the same weight!");
        }

        r = 78;
        k = 78;
        if (r > k) {
            System.out.println("Ram is heavier than Karan.");
        } else if (r < k) {
            System.out.println("Karan is heavier than Ram");
        } else {
            System.out.println("Ram & Karan have the same weight!");
        }
	}
}
Your Output
Karan is heavier than Ram
Ram & Karan have the same weight!

Task
15.Write a program which does the following:

Take input from the console for integer variables a, b and c.
Do the above for 2 separate input tuples.
a = 25, b = 21, c = 52
a = 34, b = 23, c = 34
Compute and output the following for each tuple a, b and c:
"Bravo!" if a is greater than or equal to both b and c.
Otherwise print "Try again" in every other case.
Sample 1:
Input
Output
25 21 52
35 23 34
Try Again
Bravo!

import java.util.*;

class Codechef
{
	public static void main (String[] args)
	{
	   // Update the blank in the code given below
	    Scanner read = new Scanner(System.in);

        int a = read.nextInt();
        int b = read.nextInt();
        int c = read.nextInt();
        if (b==c) {
            System.out.println("Bravo!");
        } else {
            System.out.println("Try Again");
        }

        a = read.nextInt();
        b = read.nextInt();
        c = read.nextInt();
        if (b<=c ) {
            System.out.println("Bravo!");
        } else {
            System.out.println("Try Again");
        }
	}
}
Sample Input
25 21 52
35 23 34
Your Output
Try Again
Bravo!

16.Task
Write a program which does the following:

Declare a variable a and initialize it to the values 15

Compute if a is completely divisible by both 7 and 5.
Depending on the result above - output the following to the console:
The number is divisible by both 5 & 7
The number is not divisible by both 5 & 7
Re-assign a with number 35, and check for above again.

class Codechef
{
	public static void main (String[] args)
	{
	   // Update the blank in the code given below
		int a = 15;
        
        if (a % 7 != 0 && a % 5 != 0) {
            System.out.println("The number is divisible by both 5 & 7");
        }
        else {
            System.out.println("The number is not divisible by both 5 & 7");
        }
        
        a = 35;
        
        if (a % 7 == 0 && a % 5 == 0) {
            System.out.println("The number is  divisible by both 5 & 7");
        }
        else {
            System.out.println("The number is not divisible by both 5 & 7");
        }
	}
}
Your Output
The number is not divisible by both 5 & 7
The number is  divisible by both 5 & 7

17.Task
Write a program which does the following:

Take input from the console for integer variables z, x and c.
Do the above for 2 separate input tuples:
z = 5, x = 3, c = 2.
z = 3, x = 5, c = 8.
Compute and output the following for each tuple z, x and c:
"PASS" if c is greater than either x or z.
Otherwise print "FAIL" in every other case.
Sample 1:
Input
Output
5 3 2
3 5 8
FAIL
PASS

import java.util.*;

class Codechef
{
	public static void main (String[] args)
	{
	   // Update the blanks in the code given below
		Scanner read = new Scanner(System.in);

        int z;
        int x;
        int c;
        z = read.nextInt();
        x = read.nextInt();
        c = read.nextInt();
        if (c > x && c > z) {
            System.out.println("PASS");
        }
        else {
            System.out.println("FAIL");
        }

        z = read.nextInt();
        x = read.nextInt();
        c = read.nextInt();
        if (c > x || c > z) {
            System.out.println("pass");
        }
        else {
            System.out.println("Fail");
        }
	}
}
Sample Input
5 3 2
3 5 8
Your Output
FAIL
pass


Switch, Break and Default statement
switch(expression) {
  case x:
    // code 
    break;
  case y:
    // code 
    break;
  default:
    // code 
}
18.Task
Write a program which does the following:

Take input from the user with value between 1 and 7.
Compute and output to the console the day associated with that number.
Sample 1:
Input
Output
4
Thursday
import java.util.Scanner;


class Codechef
{
	public static void main (String[] args)
	{
		Scanner read = new Scanner(System.in);
		int a = read.nextInt();
		switch(a) {
        case 1:
            System.out.println("Monday");
            break;
        case 2:
            System.out.println("Tuesday");
            break;
        case 3:
            System.out.println("Wednesday");
            break;
        case 4:
            System.out.println("Thursday");
            break;
        case 5:
            System.out.println("Friday");
            break;
        case 6:
            System.out.println("Saturday");
            break;
        case 7:
            System.out.println("Sunday");
            break;
		}
	}
}
Sample Input
4
Your Output
Thursday

19.import java.util.*;

class Codechef {
    public static void main(String[] args) {
        int a, b;
        Scanner scanner = new Scanner(System.in);
        a = scanner.nextInt();
        b = scanner.nextInt();
        if (b == 0) {
            System.out.println("infinity");   // uncomment the if condition
            return;
        }
        

        System.out.println(a / b);
    }
}
Sample Input
5 3
Your Output
1

Task
20.Given a program to check a number is greater than 5 or not:

Run the code it will give wrong answer.
find the wrong condition and correct it.
Sample 1:
Input
Output
5
the number is smaller than or equal to 5
Sample 2:
Input
Output
6
the number is greater than 5

import java.util.*;
import java.lang.*;
import java.io.*;
class Codechef {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n = scanner.nextInt();
        
        if (n > 5) {             // correct the incorrect if codition 
            System.out.println("the number is  greater than 5");
        } else {
            System.out.println("the number is smaller than or equal to 5");
        }
        
        scanner.close();
    }
}
Sample Input
5
Your Output
the number is smaller than or equal to 5


