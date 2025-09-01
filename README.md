Program 1

Aim
To implement the concept of **single inheritance** in C++ using a base class `Vehicle` and a derived class `Car`.


Software Used
Programiz Online Compiler (for C++ execution and testing)

Theory

Inheritance is one of the fundamental features of Object-Oriented Programming (OOP).

* It allows a class (derived class) to acquire the properties and behaviors of another class (base class).
* The base class provides common functionality, while the derived class extends or customizes it.
* In single inheritance, one derived class inherits from only one base class.

In this program:

* The base class `Vehicle` defines a data member `brand` and a member function `colour()`.
* The derived class `Car` inherits from `Vehicle` and introduces its own data member `model`.
* Objects of the `Car` class can access both the base class members (`brand`, `colour()`) and its own member (`model`).

Algorithm

1. Start the program.
2. Define the base class `Vehicle` with:

   * A data member `brand`
   * A member function `colour()`
3. Define the derived class `Car` which inherits publicly from `Vehicle` and adds a data member `model`.
4. In the `main()` function:

   * Create an object of the derived class `Car`.
   * Access and display the base class data (`brand`).
   * Access and display the derived class data (`model`).
   * Call the inherited function `colour()`.
5. Stop the program.

Conclusion

The program successfully demonstrates single inheritance in C++.
The derived class `Car` inherited data members and functions from the base class `Vehicle` while also having its own members. This shows how **code reusability and extension of functionality are achieved through inheritance.

