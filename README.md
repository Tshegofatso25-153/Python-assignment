# Python-assignment

This code was created to create a student management system that manages the students grades across different subjects.

In Section A, an empty list that will contain the details of the students was created. After it's creation, the user was prompt to enter the number of students they want to manage their grades.
For each students, their details, names and grades were entered using a loop. The user prompts in the loop had validations that ensure that the desire data is enter( the grades should be in a range between 0 and 100).The names and grades collected/entered were added to the empty list created above. 
Using another loop, all of the student's grades were totaled and the class average was calculated.

In Section B, the system was modified such that it can hold grades for different subjects instead of 1 subject. 
First a list with different subjects for which the grades of these subjects will be recorded was created.

#SECTION C
In Section c,a dictionary is created tp replac the tulple list. A dictionary where the student name is the key and the grades are the values .
This dictionary was the improvement and extended such that the subjects is a key and holds multiple grades for a subject.
An input prompt was used to ask the user how many grades are expected per subject. 
A loop was used to add a new student to the tuple. The loop promts the user to enter the student name and it will check if the student name already exists in the tuple created.
If the studects existed, the system will tell the user and will not add the s
student,but if the student does not exist, the system will ask the user for the student's grades. The validation rules will also apply to the students grades.
For updating the student's grades. A simple input prompt was used. The prompt asks the user to enter the name of the student whose grades are to be updated.
it will then ask the user to enter the subject whose grade is to be updated and it will then ask for the new grade.
For removing a student,
