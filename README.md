
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
