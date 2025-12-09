# Exercise 3 Instructions

You are given:

```c
typedef struct
{
    char name[50];
    int score;
} student;
```

Complete a program so that it:

- Prompts the user for the number of students (up to 50).
- Creates an array of `student` of size n.
- For each student, asks for their name and exam score (0–100).
- Computes the average score.
- Prints the average and the name of the top-scoring student.

Example:

```
How many students? 3
Name: Alice
Score: 88
Name: Bob
Score: 75
Name: Carol
Score: 92

Average score: 85.0
Top student: Carol
```
