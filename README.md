ShapeHierarchy

ShapeHierarchy is a Java project designed to model a hierarchy of geometric shapes. This project demonstrates object-oriented principles such as inheritance and encapsulation by implementing various shape classes. The initial implementation includes a Rectangle class with methods to calculate geometric properties.
Features

    Rectangle Class: Implements methods to calculate area and perimeter, and provides access to its dimensions.
    Shape Hierarchy: Lays the groundwork for extending the hierarchy to include other shapes in the future.
    Encapsulation: Demonstrates encapsulation by using private fields and public getter methods.

Getting Started

To get started with the project, you’ll need to have Java Development Kit (JDK) installed on your machine.
Prerequisites

    Java JDK 8 or later
    An IDE like IntelliJ IDEA, Eclipse, or a simple text editor

Installation

    Clone the repository:

    bash

git clone https://github.com/yourusername/ShapeHierarchy.git

Navigate to the project directory:

bash

    cd ShapeHierarchy

    Open the project in your IDE or compile and run the code using the command line.

Running the Code

To compile and run the Rectangle class:

    Compile the code:

    bash

javac src/Rectangle.java

Run the code:

bash

    java src/Rectangle

Project Structure

    src/: Contains all the source code files.
        Shape.java: Base class for geometric shapes.
        Rectangle.java: Class representing a rectangle, extending Shape.

Usage

Here’s a brief example of how to use the Rectangle class:

java

public class Main {
    public static void main(String[] args) {
        Rectangle rect = new Rectangle(5.0, 3.0);
        System.out.println("Length: " + rect.getLength());
        System.out.println("Width: " + rect.getWidth());
        System.out.println("Area: " + rect.getArea());
        System.out.println("Perimeter: " + rect.getPerimeter());
    }
}

Contributing

Feel free to contribute to the project by submitting pull requests or opening issues. Contributions are welcome to add more shapes or improve existing functionalities.
