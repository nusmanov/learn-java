# What is programming
* We have to tell computers what to do.
    * for example every PC game is a huge program
    * developers have to express precisely all parts of the program 
    * a programming languege is used for this

# Creating a new computer program
* **compiler** - translates the program code (text file) into computer-friendly (human-unfriendly) instructions
* **virtual machine** - executes the computer friendly instructions

# Java Virtual Machine - JVM
0) Run a java program - requires already running JVM on the computer
1) JVM examines the java program (bytecode) and follows the bytecode's instrucitons

As Java Developer we execute the javac and java (javac.exe and java.exe) to run our java codes:
 * javac demo.jar -jar

 ## write once, run everywhere
 * since 1995
 * same java bytecode runs on Windows, MacOS or Linux


# What is IDE
* IDE - Integrated developement environment (IDE) is a program where we can:
    * create new programs
    * run those
    * document those
    * edit existing ones
    * (debug)


# Setup

## Install Java
Visit the page and download Java Version 11
https://www.oracle.com/java/technologies/javase-downloads.html

## Install IDE
There are top 4 IDE for Java developement:
- IntelliJ by JetBrains
- Eclipse
- Netbeans
- VS Code with Java plugin

I recommend the IntelliJ. Please download and install the free community version:
https://www.jetbrains.com/de-de/idea/download/


# Hello World in Java

* create a new project lesson-00-helloworld
* create a new class HelloWorld

```
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```

* every line of code that can actually run needs to be inside a class
* main - is the entry point of our Java program. Every application in Java must contain the main method. The Java compiler starts executing the code from the main method.



# Exkurs

* Compile
```
javac HelloWorld.java
```
* Run
```
java -cp . HelloWorld
```
