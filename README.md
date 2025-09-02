# Python Debugging Assistant Prompt

**Author**: Shashwat Vikram Singh <br>
**Email**: shashwatvikramsingh8@gmail.com  <br>
**Submission Date**: September 2, 2025  
**Repository**: [https://github.com/shashwat-vikram-singh/python-debugging-promp](https://github.com/shashwat-vikram-singh/python-debugging-promp) <br>
**Purpose**: Submission for Python Screening Task 2 by FOSSEE

This repository contains a carefully crafted prompt designed for an AI debugging assistant to help students debug their Python code. The prompt ensures the AI provides constructive, encouraging, and student-friendly feedback without revealing the correct solution. This README provides a detailed explanation of the problem statement, the solution (the prompt), how it works, and the reasoning behind its design.

## Problem Statement

The Python Screening Task 2 requires creating a natural-language prompt for an AI language model (e.g., ChatGPT) to assist students in debugging their Python code. The prompt must:

- **Guide the AI**: Instruct the AI to analyze a student’s buggy Python code, identify issues, and provide helpful suggestions or hints.
- **Avoid Direct Solutions**: Ensure the AI does not give away the correct code or fix, focusing instead on guiding the student to find the solution themselves.
- **Be General Yet Specific**: Work across various Python coding problems (e.g., syntax errors, logical errors) while providing targeted, context-aware feedback.
- **Encourage Learning**: Use a supportive tone to foster confidence and teach debugging skills.
- **Include Reasoning**: Explain the design choices, tone, balance of feedback, and adaptability for different learner levels.

## Solution

The solution is a well-structured prompt (in `prompt.md`) that instructs an AI to act as a Python debugging assistant. The prompt is designed to:

- **Analyze Code**: Identify syntax, logical, or runtime errors in specific lines or sections.
- **Describe Issues Clearly**: Use simple, student-friendly language to explain problems without overwhelming the learner.
- **Provide Hints**: Offer questions or suggestions (e.g., “What is the value of this variable?”) to guide critical thinking.
- **Encourage Debugging Skills**: Recommend strategies like printing variables or testing edge cases to build problem-solving abilities.
- **Avoid Solutions**: Explicitly prohibit corrected code or direct fixes to ensure the student learns through exploration.
- **Adapt to Context**: Use problem descriptions or expected outputs to tailor feedback.
- **Maintain Positivity**: Use an encouraging tone to motivate students and acknowledge their efforts.

The prompt is flexible enough to handle various Python issues (e.g., incorrect loops, undefined variables, or logical errors) while being specific in its instructions to ensure consistent, helpful feedback.

## How It Works

The prompt operates as a set of instructions for an AI language model. When given a student’s Python code, the AI follows these steps:

1. **Code Analysis**: The AI scans the code for errors, such as:
   - **Syntax Errors**: Missing colons, incorrect indentation, or invalid keywords.
   - **Logical Errors**: Code that runs but produces incorrect results (e.g., a loop that skips values).
   - **Runtime Errors**: Issues like undefined variables or division by zero.
   It identifies the problematic lines or sections to focus the feedback.

2. **Issue Description**: The AI explains the problem in a clear, non-technical way. For example, instead of saying “TypeError in line 5,” it might say, “Line 5 seems to be trying to combine two things that don’t match. Let’s check what types of values are being used.”

3. **Hints and Questions**: The AI provides targeted hints, such as:
   - “What happens if you print the value of `x` before line 10?”
   - “Could the condition in this `if` statement be missing some cases?”
   These questions prompt the student to investigate without revealing the fix.

4. **Debugging Strategies**: The AI suggests general techniques, such as:
   - Adding `print()` statements to track variable values.
   - Testing with smaller or edge-case inputs.
   - Consulting Python documentation for specific functions or syntax.
   This teaches students how to debug independently.

5. **Contextual Feedback**: If the code includes a problem description (e.g., “This should sum numbers from 1 to 10”), the AI compares the code’s output to the expected result, highlighting discrepancies without correcting the code.

6. **Encouraging Tone**: The AI starts with positive feedback (e.g., “Great start on your code!”) and maintains a supportive tone to keep the student motivated.

For example, if a student’s code has a loop that doesn’t iterate correctly, the AI might say:
> Great effort on your code! I can see you’re trying to loop through a list. It looks like the loop on line 7 might not be covering all the elements. Could you check the range you’re using? Maybe try printing the index values to see what’s happening.

This approach identifies the issue, provides a hint, and suggests a debugging strategy without giving the solution.

## Files
- `prompt.md`: Contains the natural-language prompt for the AI debugging assistant, written in Markdown.
- `README.md`: This file, providing a detailed explanation of the problem, solution, how it works, setup instructions, and reasoning.

## Setup Instructions
1. **Clone the Repository**:
   ```bash

   git clone https://github.com/shashwat-vikram-singh/python-debugging-promp


