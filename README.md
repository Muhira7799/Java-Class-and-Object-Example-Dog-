# Java Class and Object Example (Dog)

A small Java program that demonstrates how to define a class with fields and a method, create an object, and use it.

## What It Demonstrates

- A class (`Dog`) with fields `eyes`, `legs`, and `name`
- A method (`move()`)
- Creating an object with `new Dog()`
- Setting fields and reading them with the dot operator

```java
Dog d = new Dog();
d.eyes = 2;
d.legs = 4;
d.name = "Bob";
d.move();
```

## Output

```
Eyes: 2
Legs: 4
Name: Bob
Dog can move
```

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
javac DogDemo.java
java DogDemo
```

## Project Structure

```
.
├── DogDemo.java
└── README.md
```

## Next Steps

- Add a constructor to set `eyes`, `legs`, and `name` at creation
- Make the fields `private` and add getters and setters
- Create more `Dog` objects and compare them
- Extend `Dog` from an `Animal` parent class
