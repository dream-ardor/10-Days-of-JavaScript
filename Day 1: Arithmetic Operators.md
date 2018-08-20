Task:
Complete the following functions in the editor below:
getArea(length, width): Calculate and return the area of a rectangle having sides length and width .
getPerimeter(length, width): Calculate and return the perimeter of a rectangle having sides length and width .
The values returned by these functions are printed to stdout by locked stub code in the editor.

SOLUTION:
```javascript

function getArea(length, width) {
    let area;
    area= length * width;
     return area;
}

/**
*   Calculate the perimeter of a rectangle.
*	
*	length: The length of the rectangle.
* width: The width of the rectangle.
*   
*	Return a number denoting the perimeter of a rectangle.
**/

function getPerimeter(length, width) {
    let perimeter;
   perimeter = 2 * (length + width); // Write your code here 
    return perimeter;
}
