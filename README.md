# codtech-task-2
Overview of the Student Grade Tracking Program
Purpose:
The program is designed to help users track and manage student grades by:

Inputting Grades: Users can input grades for various subjects.
Calculating Average Grade: It computes the average of the entered grades.
Determining Letter Grade: Converts the average grade into a letter grade based on predefined criteria.
Calculating GPA: Computes a Grade Point Average (GPA) based on the letter grade.
Displaying Results: Presents a summary of the grades, average grade, letter grade, and GPA.
Components:

get_grade_input():

Function: Collects grades from the user for different subjects.
Details:
Prompts the user to enter a subject and a numeric grade.
Accepts multiple subjects and grades until 'done' is typed.
Validates that grades are numeric and within the 0-100 range.
Returns: A dictionary where keys are subject names and values are grades.
calculate_average(grades):

Function: Calculates the average of the grades.
Details:
Computes the mean of all grade values.
Returns 0 if no grades are entered.
Returns: The average grade as a float.
get_letter_grade(average):

Function: Converts the average numeric grade into a letter grade.
Details:
Uses predefined ranges to assign letter grades:
A (90 and above)
B (80-89)
C (70-79)
D (60-69)
F (below 60)
Returns: A letter grade as a string.
calculate_gpa(letter_grade):

Function: Converts the letter grade into a GPA value.
Details:
Uses a dictionary to map letter grades to GPA values:
A = 4.0
B = 3.0
C = 2.0
D = 1.0
F = 0.0
Returns: The GPA as a float.
display_results(grades):

Function: Displays the grades, average grade, letter grade, and GPA.
Details:
Prints each subject with its grade.
Shows the average grade, the corresponding letter grade, and the GPA.
main():

Function: Manages the flow of the program.
Details:
Welcomes the user and initiates the grade input process.
Calls display_results() to show the computed results.
Behavior: Ensures that the grade tracking process is initiated and completed smoothly.
Workflow:
Initialization:

The user is greeted and prompted to input grades.
Data Collection:

Grades are collected for various subjects until the user types 'done'.
Processing:

The average grade is calculated.
The letter grade and GPA are determined based on the average grade.
Output:

A formatted report is displayed, showing each subject's grade, the average grade, letter grade, and GPA.
Usage:
Run the Program: Save the script as grade_tracker.py and execute it using Python (python grade_tracker.py).
Interact: Follow the prompts to input subject grades and view the results.
This program provides a basic but functional approach to managing student grades, which can be extended with additional features or integrated into larger systems if needed.



