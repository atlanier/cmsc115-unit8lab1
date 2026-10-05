# Lab Reflection: Git Version Control + Debugging (BuggyProgram)

## Student Name
Anthony Tucker Lanier

## GitHub Repository URL
Paste your GitHub repository URL here.
https://github.com/atlanier/cmsc115-unit8lab1
---

# Commit 1: Initial Commit

## What did you include in this commit?
-
I included the original BuggyProgram starter code and the project files before making any changes.
## What was the purpose of this commit?
-
The purpose was to create a starting point so I could track each change I made while debugging the program.
---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
-
The tests checking the grade categories and score boundaries were failing.
## What was the issue in the code?
-
The "Meets" and "Exceeds" results were reversed, and the score boundary conditions were incorrect.
## What change did you make to fix it?
-
The expected results showed which score ranges needed to return each performance level and helped identify the incorrect conditional logic.
## How did the tests help guide your fix?
-
I changed the conditions so scores of 90 or higher return "Exceeds", scores of 80 or higher return "Meets", and lower scores return "Does Not Meet".
---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
-
The tests that calculated the sum of even numbers in an array were failing.
## What was the issue in the code?
-
The sum started at 1 instead of 0, and the loop used i <= values.length, which caused it to go past the last valid array index.
## What change did you make to fix it?
-
I changed the starting sum from 1 to 0 and changed the loop condition from i <= values.length to i < values.length.
## How did the tests help guide your fix?
-
The expected sums showed that the total was incorrect, and the array error helped identify that the loop was going beyond the valid array indexes.
---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
-
The tests checking the upper boundary of the range were failing.
## What was the issue in the code?
-
The loop included the ending value when it was supposed to stop before the end of the range.
## What change did you make to fix it?
-
I changed the loop condition from i <= end to i < end.
## How did the tests help guide your fix?
-
The expected results helped show that the ending value should not be included in the total.
---

# Overall Reflection

## Which task was the easiest to fix? Why?
-
Task 1 was the easiest because the incorrect return values in the conditional statements were easy to identify and correct.
## Which task was the most difficult? Why?
-
Task 2 was the most difficult because it had more than one problem. I had to correct both the starting value of the sum and the loop boundary.
## How did Git help you track your progress through the debugging process?
-
Git allowed me to save each fix as a separate commit. This made it easy to see what changed during each step of the lab.
## Why is it important to make small, frequent commits when debugging code?
-
mall commits make it easier to identify which changes fixed or caused a problem. They also make it easier to return to an earlier version if something goes wrong.
## What did you learn about using JUnit tests to guide debugging?
-
I learned that JUnit tests can show when the output of a method does not match the expected result. This helps narrow down where the problem is and confirms whether a fix works correctly.
---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
-
I completed the reflection questions, reviewed the README, added my name and GitHub repository URL, and made sure the previous task information was complete.
## Why is it useful to document your work after completing a programming task?
-
Documentation explains what was changed, why it was changed, and what was learned. It also makes it easier for someone else to understand the work later.