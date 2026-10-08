# Python-assignment

This code was created to create a student management system that manages the students grades across different subjects.

In Section A, an empty list that will contain the details of the students was created. 
total_students holds the number of people in a particular class.
grades[] holds the grades of the student for a particular subject.
names[] holds the names of the students in a class.
After it's creation, the user was prompt to enter the number of students they want to manage their grades.

For each students, their details, names and grades were entered using a loop. The user prompts in the loop had validations that ensure that the desire data is enter( the grades should be in a range between 0 and 100).The names and grades collected/entered were added to the empty list created above. 
Using another loop, all of the student's grades were totaled and the class average was calculated.

In Section B, the system was modified such that it can hold grades for different subjects instead of 1 subject. 
First a list with different subjects for which the grades of these subjects will be recorded was created. 
A tuple that holds the grade and name is created. A grade.append() is used to add the grades to the tulple. 
A FOR loop is created to calculate the average .It loops through all the grades and divides them by the number of subjects. 
A FOR loop is created to print the grades and name of students. it loops through the names and grades in the tulple. This loop also prints the highest and the lowest marks for particular subjects.
A summary table showing names, subjects grades and class average is created.A header row includes name, different subjects and average. 

#SECTION C
In Section c,a dictionary is created tp replac the tulple list. A dictionary where the student name is the key and the grades are the values .
This dictionary was the improvement and extended such that the subjects is a key and holds multiple grades for a subject.
students[student_name] =grades stored the grades for a particular student in a dictionary. 
subject_num stores how mant gradss are expected per subject. An input prompt was used to ask the user how many grades are expected per subject. 
A loop was used to add a new student to the tuple. The loop promts the user to enter the student name and it will check if the student name already exists in the tuple created.
If the studects existed, the system will tell the user and will not add the student,but if the student does not exist, the system will ask the user for the student's grades. The validation rules will also apply to the students grades.
For updating the student's grades. A simple input prompt was used.
subject=() holds the name of the subject gor which the grage is to be changed.The prompt asks the user to enter the name of the student whose grades are to be updated.
new grade=() holds the chafed grade.the system will ask the user for the new grade.
remove_choice holds the answer to whether the user wants to remove a student or not. if the answer is yes, the user enters the name of the student they want to remove if it is not, the process is skipped. The del function use the student_name and removes the student from the list
grades_view holds the subject for which the user has interest in viewing the grades.the user inputs the subject, if the input subject exists in the dictionary, the name and grades for each student for that particular subject is printed.
search_name holds the name of the student being searched for. results stores the student's dictionary. all_grades stores grades for the student. the user enters the name, the name is checked on the dictionary and the grades are stored, the grades and subject are then print using the key, value item.
