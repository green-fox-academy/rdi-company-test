# Danubius Test

## Short questions

- What does method overloading mean?

- What distinguishes object, class and interface?

- What does encapsulation mean?

- What is polymorphism?

- What does inheritance mean?

- Describe the differences, if any, between
stack and queue.

- In which situation should be used a List over an Array structure?

## Programming tasks

### Fibonacci

Write a method that displays the first 100 Fibonacci numbers separated with commas.
Example: the first 10 elements of the Fibonacci
sequence are: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34 …

### Shape

Create a base class named “Shape” with a method to return the area of the shape.
Create a class named “Triangle” derived from the base class “Shape”.
Class “Triangle” must have two constructors.
One receives the length of the (a) side of the triangle and the related (ma)
height. The other receives the length of (a),(b),(c) sides of the triangle.
In the second case, the constructor must validate the input by checking that the
length of one side is smaller than the sum of the lengths of the other two sides.
If the input is invalid, it should throw an exception. Implement the method
(available in the base class) that calculates the area of the triangle on the
basis of the available data. You can use two formulas. If the length of a side
and height is given: `T=(a*ma)/2`. If the lengths of the three sides are given,
you can use the Hérón formula:
`√(〖s*(s-a)*(s-b)*(s-c)〗^ ) where s=(a+b+c)/2`

### Odd Even

Write a method that can determine if a given integer number is odd or even.
It is ONLY allowed to use addition or subtraction operations
(do NOT use modulus ‘%’, shift ‘<<’, multiply, divide, etc.). Return true if even.
`bool IsEven(int number)`

### Matrix

Write a method that can determine if a matrix has a saddle point.
The input parameter is a matrix constructed of integers. The method must return
a boolean value that is true if the matrix has a saddle point (an element that
is the smallest in its row and the largest in its column), and false if the
matrix has NO saddle point.

### Next highest

Write a method with an integer input parameter that must return the NEXT highest
number using the same digits of the input integer.
i.e., if the given integer is 1234,
you should return 1243.
`int NextHighestNumberWithSameDigits(int number)`
