# Learning basics of C++ - open/read .txt (Quiz)
> Training course - Pasja Informatyki, C++ course, episode 7 ( [Link](https://www.youtube.com/watch?v=h2Taf16gQDI) )

## General info
The basics of working with text files in C++ using the `fstream` standard library. File `dane.txt` contains 8 lines: topic, nick, question, answer A, answer B, answer C, answer D, correct answer. Program opens the file, then reads the contents of it with a `while` loop and `getline()` function until the end of the file. Each line is saved to a `string` array. All of the arrays have 5 elements. When the contents are saved, the file is closed. Then the program outputs the contents of the first read question on the screen and asks the user for an answer. The answer is transformed to lowercase characters using the `transform()` function. If the answer is correct, the user gains a point. If not, the program shows the correct answer and moves to the next question. At the end of the questions, total amount of points is shown on the screen.
If the file doesn't exist, the program shows a warning and ends.

## Technologies
* C++
* CodeBlocks (IDE)
* GNU GCC Compiler (minGW)

## Contact
Created by [ReznoRMichael](https://github.com/ReznoRMichael)