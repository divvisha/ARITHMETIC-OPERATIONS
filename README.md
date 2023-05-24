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

  import java.util.Scanner;<br>
  public class Calculation<br>
  {<br>
      public static void main(String[] args)<br>
      {<br>
          Scanner s=new Scanner(System.in);<br>
          System.out.println("Enter a number:");<br>
          int a=s.nextInt();<br>
          System.out.println("Enter a number:");<br>
          int b=s.nextInt();<br>
          System.out.println("Sum: "+(a+b));<br>
          System.out.println("Difference: "+(a-b)); <br>
          System.out.println("Product: "+(a*b));<br>
          System.out.println("Quotient: "+(a/b));<br>
          System.out.println("Remainder: "+(a%b));<br>
      }<br>
  }

# OUTPUT:

<img width="302" alt="java ex1 op" src="https://github.com/divvisha/ARITHMETIC-OPERATIONS/assets/127508123/0bac0b1d-7576-4409-8c4c-019af87532dc">

# RESULT:

 The java program to perform arithmetic operations is written, compiled and executed and the desired output is obtained successfully.

