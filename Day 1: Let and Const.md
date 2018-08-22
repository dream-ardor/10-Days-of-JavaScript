Task

Declare a constant variable, PI , and assign it the value Math.PI. You will not pass this challenge unless the variable is declared as a constant and named PI (uppercase).
Read a number,r, denoting the radius of a circle from stdin.
Use PI and r to calculate the area and perimeter of a circle having radius .
Print area as the first line of output and print perimeter as the second line of output.

SOLUTION:
```javascript
    // Write your code here. Read input using 'readLine()' and print output using 'console.log()'.
   function main() {
     const PI = Math.PI;
     const r = readLine();
    
    // Print the area of the circle:
   var area = PI * (r * r);
    console.log(area);
    
    // Print the perimeter of the circle:
   var perimeter = 2 * PI * r;
    console.log(perimeter); }
