# EXPERIMENT-1 JAVA PROGRAM TO PRINT THE ARITHMETIC OPERATIONS.

# AIM:

 To write a java program to print the Arithmetic operations.

# ALGORITHM:

 1. Import the Java Scanner to get input from the user.
 2. Declare the variables that we are about to use.
 3. Instantiate the Scanner class.
 4. Get two numbers as input from the user.
 5. Perform all arithmetic operations such as Addition, Difference, Product, Quotient and Modulus.
 6. Print the output.

# PROGRAM:

import java.util.Scanner;
public class Calculation
{
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        System.out.println("Enter a number:");
        int a=s.nextInt();
        System.out.println("Enter a number:");
        int b=s.nextInt();
        System.out.println("Sum: "+(a+b));
        System.out.println("Difference: "+(a-b)); 
        System.out.println("Product: "+(a*b));
        System.out.println("Quotient: "+(a/b));
        System.out.println("Remainder: "+(a%b));
    }
}

# OUTPUT:

<img width="302" alt="java ex1 op" src="https://github.com/divvisha/ARITHMETIC-OPERATIONS/assets/127508123/0bac0b1d-7576-4409-8c4c-019af87532dc">

# RESULT:

 The java program to perform arithmetic operations is written, compiled and executed and the desired output is obtained successfully.

