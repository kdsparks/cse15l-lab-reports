# Lab Report 5

## Debugging Scenario
Student's Original Post:

Hello,

When I run the bash script, my test method `testCalculateGradeA` fails, as the grade calculated is `"F"` instead of `"A"`. I think the bug has something to do with my `findGrade` method in `Grades.java`, but I'm not sure because `testCalculateGradeC` passed which is odd. I tried changing my if statements to else if, but it didn't fix the bug.

![error output](symptom.png)

TA's Response:

First I'd recommend checking if the numerical grade is calculated correctly in your `findGrade` method. Try adding a test with just one `Grade` in the `scores` array, then another tests with two `Grade`s. Rerun `bash test.sh` after each addition of a test. You can disable the original tests by commenting out the `@Test` line.

Student's Response:

Another screenshot/terminal output showing what information the student got from trying that, and a clear description of what the bug is

![Image]()

Description

4) At the end, all the information needed about the setup including:
* The file & directory structure needed
  ```

  ```
* The contents of each file before fixing the bug
  ```

  ```
* The full command line (or lines) you ran to trigger the bug
  ```

  ```
* A description of what to edit to fix the bug
  
---
## Reflection
In a couple of sentences, describe something you learned from your lab experience in the second half of this quarter that you didn't know before.
