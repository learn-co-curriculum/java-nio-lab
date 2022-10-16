# Java NIO Lab

## Learning Goals

- Practice reading and writing a text file using the `Files` class from the
  `java.nio` package.

## Instructions

Given the `GroceryListDriver` class again, modify the program to use the
`Files` class from the `java.nio` package to read and write a text file.

Reuse the last lab to modify the methods you already wrote to use the new
classes we just learned about.

To implement the reading and writing of a text file, consider the following
instructions and tips:

- Modify the `GroceryListDriver` class.
    - Rewrite the method to write to a text file.
        - Use the `writeString()` method to write to a text file.
        - Each item in the list should be on its own new line.
        - Refer back to the Java NIO lesson.
    - Rewrite the method to read a text file line-by-line.
        - Use either the `readString()` method or the `readAllLines()` method to
          read from the text file.
        - Return a `String` to print out to the console the list of groceries.
        - Refer back to the Java NIO lesson.
- When running the `GroceryListDriver` class, pass in a file named
  `grocery-list.txt`.
- Remove the `@Disabled` annotation from the unit tests and ensure that the
  tests pass successfully. Refactor as needed.
