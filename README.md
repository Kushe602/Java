# Java Practice Repository

A collection of Java fundamentals and multi-file object-oriented programming exercises. This repository is organized for browsing individual examples and practicing core language concepts.

## Repository structure

### `javabasics/`

Standalone exercises include:

| Program | Practice topic |
| --- | --- |
| `HelloWorld.java` | First Java program and console output |
| `LargestInThree.java` | Conditional logic and comparisons |
| `Grade.java` | Grade/decision logic |
| `AreaOfShape.java`, `VolumeOfShape.java` | Arithmetic and geometry calculations |
| `PrimeNumberCheck.java` | Prime-number checking |
| `PalindromeNumber.java` | Numeric palindrome logic |
| `PositiveNumAndEvenOdd.java` | Sign and parity checks |
| `fibonaciseries.java` | Fibonacci sequence |
| `sumofdigit.java` | Digit processing |
| `Switch.java`, `TrafficLightMessage.java`, `MovieRating.java` | Switch-based branching and messages |
| `Main.java` | Entry-point example |

### `Multi_File_Programs/`

Examples split across multiple source files:

- `Employee.java` and `EmployImp.java`
- `Student.java` and `StudentImp.java`

These are useful for practicing classes, objects, and separating a model from a program that uses it.

## Requirements

- A Java Development Kit (JDK) installed.
- A terminal, IDE, or editor that can compile and run Java programs.

Check the installation:

```bash
java -version
javac -version
```

## Compile and run a standalone example

Run these commands from the repository root:

```bash
javac javabasics/HelloWorld.java
java -cp javabasics HelloWorld
```

For another standalone exercise, replace `HelloWorld.java` and `HelloWorld` with the corresponding file and class name. The class name is case-sensitive and should match the public class declared in the source.

## Compile a multi-file example

Compile the related files together so the compiler can resolve their classes. For example:

```bash
javac Multi_File_Programs/Employee.java Multi_File_Programs/EmployImp.java
```

Run the class that declares the relevant `public static void main(String[] args)` method, using its declared package and class name. Inspect the source first to confirm the entry point.

## Suggested learning path

1. Start with `HelloWorld.java` and understand compilation versus execution.
2. Practice conditionals with `LargestInThree.java`, `Grade.java`, and `PositiveNumAndEvenOdd.java`.
3. Work through numeric problems such as prime checks, palindrome checks, digit sums, and Fibonacci sequences.
4. Review switch-based examples and shape calculations.
5. Explore the multi-file programs to understand how Java classes work together.

## Contribution and accuracy notes

This README describes the source files currently listed in the repository. It does not claim that every exercise has been tested or that the repository contains an automated test suite. If you add an example, include its filename, the concept it practices, and compile/run instructions.

---

**Purpose:** Java learning and practice exercises.
