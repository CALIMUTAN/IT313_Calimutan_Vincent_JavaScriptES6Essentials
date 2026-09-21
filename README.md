# IT313_Calimutan_Vincent_JavaScriptES6Essentials
for school purposes

## Problem

This program processes student grades to determine their average and enrollment status. Students with an average of 75 or more are considered PASSING, while those below 75 are placed on PROBATION.

## Approach

The program:

- Retrieves enrollee data asynchronously using a Promise.
- Calculates each student's average using `computeAverage()`.
- Determines their status using `isPassing()`.
- Calculates the class average and number of passing students.
-Displays the results as an enrollment eligibility report.

The grade calculations are stored in `gradeUtils.js`, while the main program logic is in `main.js`.

## How to Run

Make sure Node.js is installed, then run:

```bash
node main.js
```

The enrollment eligibility report will be displayed in the terminal.


