# Array to ArrayList and Back

This repository demonstrates how to convert an integer array (`int[]`) into an `ArrayList<Integer>` and then convert that `ArrayList` back into an `int[]`. It showcases basic data structure manipulation in Java and serves as a quick reference for beginners or anyone looking to refresh their knowledge of arrays and `ArrayList`s.

## Files Included

1. **ArrayToArrayListConverter.java**  
   - Provides a method `convertToArraylist(int[] array)` that takes an integer array and returns an `ArrayList<Integer>`.

2. **ArrayListToArrayConverter.java**  
   - Contains the method `convertToarray(ArrayList<Integer> arrayList)` which converts an `ArrayList<Integer>` back to an integer array.

3. **main.java**  
   - A driver program that prompts the user for input, invokes the conversion methods, and then prints out the results of each conversion step.

## How It Works

1. **User Input**: The program asks for the number of elements and then reads each integer to form the initial array.
2. **Conversion to `ArrayList`**: Using `ArrayToArrayListConverter`, the array is transformed into an `ArrayList<Integer>`.
3. **Conversion Back to Array**: With `ArrayListToArrayConverter`, the newly created `ArrayList` is converted back into a standard integer array.
4. **Output**: The contents of both the intermediate `ArrayList` and the final converted array are displayed.

## Getting Started

1. **Clone or Download** the repository.
2. **Compile** all Java files (e.g., `javac main.java ArrayToArrayListConverter.java ArrayListToArrayConverter.java`).
3. **Run** the `main` class (`java main`).
4. **Input** the size of the array and its elements when prompted.
5. **View** the resulting `ArrayList` and the final array in the console output.

## Why It’s Useful

- Offers a clear example of moving data between arrays (fixed-size) and `ArrayList` (dynamic-size).
- Serves as a concise code snippet for developers needing to perform these operations in larger projects.
- Provides a simple learning exercise for those new to Java and its collections.
