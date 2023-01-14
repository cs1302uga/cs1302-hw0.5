# cs1302-hw0.5 Implementing Tic-Tac-Toe - Part 2

![Approved for: Spring 2023](https://img.shields.io/badge/Approved%20for-Spring%202023-magenta)

This homework is designed to give students the opportunity to complete the Tic-Tac-Toe game in a Unix
environment. This homework also explores the `check1302` program that helps students check their code
style. At the end of the assignment, students will have an opportunity to submit an assignment on Odin
for the first time.

## Prerequisite Knowledge

* An understanding of classes, objects, and 2-D arrays in the Java programming language.

## Exercise Steps

### Checkpoint 1 Steps

1. Log into your Odin account. You should not use an IDE to complete this homework. Instead, you are expected 
   to use Odin and Emacs.
   
1. Use Git to clone the repository for this exercise onto Odin into a subdirectory called `cs1302-hw0.5` using
   the following command (remember not to type the `$` as that represents our prompt):

   ```
   $ git clone --depth 1 https://github.com/cs1302uga/cs1302-hw0.5.git
   ```
   
1. Change into the `cs1302-hw0.5` directory and type the `tree` command. You should see three familiar files under
   the `src` directory. This is the same code you downloaded and completed in the previous homework assignment.
1. Without changing directories, open the `TicTacToeGame.java` file using Emacs. Take a minute to look through the
   file. You should recognize this as the original file without any of the modifications you made last week.
1. Take a moment to think about the process of downloading this code from GitHub (you just typed a single command) and
   compare that process to what you had to do to get started last week (saving the file to your hard drive, locating your
   favorite IDE, creating a project in your IDE, importing the code, etc.).
1. Now that we've got our environment set up, we want you to complete the `TicTacToeGame.java` file on Odin. Please do this
   without copying and pasting your code from an IDE. The purpose of this part of the exercise is for you to get practice with
   Emacs. It will feel slow and error-prone at first. However, you will get much faster over time. Note: You should have 
   already implemented these methods (if you haven't, please go back to the first part of this assignment).
1. Once your code is completed, exit the Emacs text editor. You should still be in the `cs1302-hw0.5` diretory.
1. Create a new folder called `bin` directly within the `cs1302-hw0.5` directory.
1. Compile the three Java files located in the `src` directory - placing the byte code (`.class`) files in the `bin`
   directory. Remember to use the `-d` command-line option when compiling.
1. If you have any syntax errors, note where the error occurs, go back into `TicTacToeGame.java` and fix the errors.
1. Once your code compiles, run the `TicTacToeTester` class and make sure it passes all tests. If not, fix the bugs in the
   code before proceeding.
1. Once the `TicTacToeTester` passes all of the provided tests, run the `TicTacToeRunner` and play a few games of
   Tic-Tac-Toe.
   
### Checkpoint 2 Steps

1. 

<hr/>

![CP](https://img.shields.io/badge/Just%20Finished%20Checkpoint-1-success?style=for-the-badge)

<hr/>

### Checkpoint 2 Steps - Testing your Implementation

In software development, it is important to **thoroughly** test all of the methods you write by writing
test code to go along with the implementation. Luckily, a test program for our Tic-Tac-Toe implementation 
already exists. To test the code you wrote, download 
[`TicTacToeTester.java`](https://github.com/cs1302uga/cs1302-ce0.5/blob/main/src/TicTacToeTester.java) and
add it to your existing project. Then, run the code. If you encounter errors, work with your group to resolve
the issues in those methods.

Generally, when we test methods in a larger software system, we will test each method thoroughly as we write it.
As you can probably imagine, you don't want to write too much code before testing as bugs can be much harder
to find in large projects. We will discuss ways to effectively approach this later in the semester.

<hr/>

![CP](https://img.shields.io/badge/Just%20Finished%20Checkpoint-2-success?style=for-the-badge)

<hr/>

### Checkpoint 3 Steps - Play the Game!

Now that your code is implemented and tested, play the game against your neighbor! To do this, download
[`TicTacToeRunner.java`](https://github.com/cs1302uga/cs1302-ce0.5/blob/main/src/TicTacToeRunner.java) and add
it to your existing project. This class serves as a command-line interface for your game. Please note that other
interfaces (such as graphical user interfaces) would also work with your implementation!

<hr/>

![CP](https://img.shields.io/badge/Just%20Finished%20Checkpoint-3-success?style=for-the-badge)

<hr/>

### Submission Steps

**Each student needs to individually submit their own work.**

1. Create a plain text file called `SUBMISSION.md` directly inside the `cs1302-hw0.5`
   directory with your name and UGA ID number.
   
   Here is an example of the contents of `SUBMISSION.md`.
   
   ```
   Sally Smith (811-000-999)
   ```

1. Change directories to the parent of `cs1302-hw0.5` (e.g., `cd ..` from `cs1302-hw0.5`).
   
1. Use the `submit` command to submit this exercise to `csci-1302`:
   
   ```
   $ submit cs1302-hw0.5 csci-1302
   ```
   
   Read the output of the submit command very carefully. If there is an error while submitting, then it will displayed 
   in that output. Additionally, if successful, the submit command creates a new receipt file in the directory you 
   submitted. The receipt file begins with rec and contains a detailed list of all files that were successfully submitted. 
   Look through the contents of the rec file and always remember to keep that file in case there is an issue with your submission.

   **Note:** You must be on Odin to submit.

<hr/>

![CP](https://img.shields.io/badge/Just%20Finished-Submission-success?style=for-the-badge)

<hr/>

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-nd/4.0/)

<small>
Copyright &copy; Michael E. Cotterell, Brad Barnes, and the University of Georgia.
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a> to students and the public.
The content and opinions expressed on this Web page do not necessarily reflect the views of nor are they endorsed by the University of Georgia or the University System of Georgia.
</small>
