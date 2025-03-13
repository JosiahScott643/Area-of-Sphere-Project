<h1>Area of a Sphere Calculator</h1>

<h2>Description</h2>
The **Area of a Sphere Calculator** is a simple Java program designed to compute the surface area of a sphere based on user input. The program prompts the user to enter the radius, applies the mathematical formula for surface area, and displays the result formatted to two decimal places.

The formula for calculating the surface area of a sphere is:
\[
A = 4\pi r^2
\]
where *r* is the radius of the sphere.

This project demonstrates basic Java programming concepts, including user input handling, mathematical computations, and formatted output.

<br />

<h2>Languages and Tools Used</h2>

- <b>Java</b>
- <b>Scanner Class</b> (for user input)
- <b>Math Library</b> (for π calculations)

<h2>Program Walk-through</h2>

1. **Prompt User for Radius**:
   - The program asks the user to enter the radius of the sphere.
   - It captures the input using a `Scanner` object.

2. **Calculate the Surface Area**:
   - The radius is inserted into the formula:  
     **A = 4 × π × r²**  
   - The computed value is stored in a variable.

3. **Display the Result**:
   - The result is printed to the console.
   - The output is formatted to two decimal places for better readability.

<h2>Example Code</h2>

```java
import java.util.Scanner;

class AreaOfASphere {
    public static void main(String[] args) {    
        Scanner keyboard = new Scanner(System.in);
        System.out.print("Enter the radius: ");
        
        double radius = keyboard.nextDouble();
        double area = 4 * Math.PI * Math.pow(radius, 2);

        System.out.printf("The Area of a Sphere given a radius of %.2f is: %.2f%n", radius, area);
    }
}
