# Week 3

## Exercise 1
Step 1: Create an `OrderItem` class containing the following attributes and methods
- Attributes:
  - unitPrice: `float`
  - numberOfItems: `int`
  - itemName: `String`
- Methods:
  - `float getTotalPrice()`: returns the product of `numberOfItems` and `unitPrice`

Step 2: Create an `OrderTracker` class as the Application Class.  It should do the following:
  - Create an `OrderItem` and populate its values
  - Print the result of it calling `getTotalPrice()`

## Exercise 2 - Follow-up
- Add access modifiers and access methods and recompile
- Add range enforcement to setter
- As a follow-up, do the following:
  - Create `OrderItemFormatter` class
  - Create additional `OrderItem` and print both using the formatter

## Exercise 3 - Constructors
- got back to be previous example, create a default constructor that has a simple print statement, recompile and execute
- then add a parameterized Constructor
- modify the `main()` method to use the parameterized constructor with a new object.
  - Provide a non-numeric value and see the Exception – we will discuss later

## Exercise 4
- create a program that takes one value from STDIN and another from the command line.  It should convert them to Integers and print the sum
