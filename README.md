#Java Assignments

# Assignment Five - Duck Simulator

Duck Simulator
This is a simple Java program that simulates the behavior of different types of ducks using the Strategy Pattern. The program demonstrates how different types of ducks can have different flying, quacking, and swimming behaviors.

Classes
Main
The Main class is the entry point of the program. It creates instances of RedHeadDuck and DecoyDuck and calls their respective methods to display their behavior.

Duck
The Duck class is an abstract class that defines the common behavior of all ducks. It has three instance variables: flyBehaviour, quackBehaviour, and swimBehaviour, which are interfaces that define the flying, quacking, and swimming behaviors of the duck. The class also provides methods to set these behaviors and perform the respective actions.

RedHeadDuck and DecoyDuck
RedHeadDuck and DecoyDuck are concrete implementations of the Duck class. They define the specific behavior of each type of duck by setting the appropriate flyBehaviour, quackBehaviour, and swimBehaviour in their constructors.

FlyBehaviour, QuackBehaviour, and SwimBehaviour
These are interfaces that define the flying, quacking, and swimming behaviors, respectively. They have concrete implementations such as FlyWithWings, FlyNoWay, Quacks, Squeak, CanSwim, and CannotSwim.

# Java Assignment Seven - Calculator Program

This is a simple calculator program implemented in Java. It provides a menu-driven interface to perform basic arithmetic operations: addition, subtraction, multiplication, and division.

## Features

- Menu-driven interface for ease of use
- Separate Java files for each operation (addition, subtraction, multiplication, division)
- Exception handling for invalid inputs (InputMismatchException)
- Division by zero error handling

## How to Run

1. Compile all the Java files using a Java compiler.
2. Run the `Main` class.
3. Follow the menu prompts to perform the desired operation.

## File Structure

- `Main.java`: Contains the main method and the menu-driven interface.
- `Addition.java`: Implements the addition operation.
- `Subtraction.java`: Implements the subtraction operation.
- `Multiplication.java`: Implements the multiplication operation.
- `Division.java`: Implements the division operation.

## Functions/Methods

### Main.java
- `main(String[] args)`: The entry point of the program, responsible for displaying the menu and delegating operations based on user choice.

### Addition.java
- `add()`: Performs the addition operation by taking two numbers as input and displaying the result. Handles `InputMismatchException` for invalid inputs.

### Subtraction.java
- `subtract()`: Performs the subtraction operation by taking two numbers as input and displaying the result. Handles `InputMismatchException` for invalid inputs.

### Multiplication.java
- `multiply()`: Performs the multiplication operation by taking two numbers as input and displaying the result. Handles `InputMismatchException` for invalid inputs.

### Division.java
- `divide()`: Performs the division operation by taking two numbers as input and displaying the result. Handles `InputMismatchException` for invalid inputs and division by zero error.



# Java Assignment Five

This is a Java program that calculates the area, perimeter/volume of various shapes such as Circle, Rectangle, Square, Sphere, Cylinder, and Pyramid.

## Features

- Interactive menu-based interface for selecting the desired shape
- Calculates the area and perimeter/volume of the selected shape
- Supports Circle, Rectangle, Square, Sphere, Cylinder, and Pyramid shapes
- Implements inheritance, abstract classes, and interfaces to promote code reusability and extensibility

## Usage

1. Run the `Main.java` file.
2. The program will prompt you to choose a shape from the menu.
3. Enter the corresponding number for the desired shape.
4. Follow the prompts to enter the necessary dimensions (e.g., radius, length, width, height) for the selected shape.
5. The program will display the shape name, area, and perimeter/volume.
6. You can continue calculating for different shapes or enter 'exit' to terminate the program.

## File Structure

- `Main.java`: The entry point of the program, containing the main method and user interaction logic.
- `Shapes.java`: Contains the abstract `Shapes` class, the `Volume` interface, and concrete shape classes (`Circle`, `Rectangle`, `Sphere`, `Cylinder`, `Pyramid`).

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
