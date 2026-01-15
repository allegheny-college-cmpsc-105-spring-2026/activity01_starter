# Coding a Teacher's Story Problem Generator

## Assigned

Thursday, 15 January 2026

## Due

Thursday, 15 January 2026 by 4:15 PM

## Goals

- Practice using basic constructs in Python programming.
- Gain experience with using GitHub to submit work.
- Develop skills in implementing logical mechanisms in programming.

## Project Overview

This project involves creating a Python program that generates a mathematical story problem and evaluates a student's response. The program will:
1. Prompt the **teacher** to provide two numerical values to complete the story problem.
2. Use the teacher's inputs to create a story problem.
3. Display the problem to the **student** and ask for their answer.
4. Calculate the correct answer and provide feedback on whether the student's answer is correct.

## Your Source Code

Locate and edit the file: `src/storyProblem.ipynb` in your repository.

The file contains `TODO` comments highlighting the parts of the program you need to complete. Follow the instructions in these comments to finish the program.

### Steps

1. Replace placeholder values (`FIRST_VALUE` and `SECOND_VALUE`) with variables to capture the teacher's input.
2. Prompt the **teacher** to input two numerical values to complete the story problem.
3. Use the teacher's inputs to generate the completed story problem and display it to the **student**.
4. Prompt the **student** to input their answer to the story problem.
5. Calculate the correct result using the teacher's inputs.
6. Compare the student's input with the correct result and provide feedback.

### Example Program Execution

**Program Outputs**:
```
Incomplete story problem:
"What value do you get when you raise FIRST_VALUE to the power of SECOND_VALUE?"
```

**Teacher's Input**:
```
Enter the FIRST_VALUE: 2
Enter the SECOND_VALUE: 7
```

**Program Outputs**:
```
Completed story problem:
"What value do you get when you raise 2 to the power of 7?"
```

**Student's Input**:
```
Enter the result of the above story problem: 127
```

**Program Response**:
- If the student's input is correct:
  ```
  The correct value is 127. You answered the problem correctly!
  ```
- If the student's input is incorrect:
  ```
  The correct value is 128. Your answer is incorrect. Try again next time!
  ```

In your own story problem and code, please be creative!

---

## GatorGrade Checking

You can also use `gatorgrade` to check the baseline requirements of this assignment by running the following command in your terminal:

`gatorgrade --config config/gatorgrade.yml`

If `gatorgrade` shows that all checks pass, you will know that you have met baseline requirements of this project.

## Submission

As you are working, you are to commit and push regularly. The commands are the following.

```bash
git add .
git commit -m ``Your notes about commit here''
git push
```

After you have pushed your work to your repository, please visit the repository at the GitHub website (you may have to log-in using your browser) to verify that your files were correctly sent.

## Project Assessment

This is a check mark grade.

## Seeking Assistance

Students who have questions about this project outside of the class or lab times are invited to ask them in the course's Discord channel or during instructor's or TL's office hours.
