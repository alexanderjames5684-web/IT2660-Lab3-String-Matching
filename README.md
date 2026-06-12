# IT2660-Lab3-String-Matching

## Description
This lab tests the brute-force string matching algorithm from the textbook by comparing a best-case input and a worst-case input using `System.nanoTime()`.

## Files Included
- `Main.java` - Completed Java source code for Lab 3.
- `output.txt` - Sample output from running the program.
- `reflection_answers.txt` - Draft answers for the Brightspace reflection questions.

## Lab Summary
The program uses a fixed text value:

`ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789`

The best-case pattern is:

`ABC`

This matches immediately at the beginning of the text.

The worst-case pattern is:

`789`

This matches near the end of the text, so the algorithm checks more positions before finding the match.

## How to Run
1. Open the folder in Visual Studio Code or another Java IDE.
2. Open `Main.java`.
3. Compile and run the program.
4. View the elapsed time results in the terminal.

## Course
IT-2660 - Lab 3
