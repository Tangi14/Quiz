# Quiz
Quiz 1
You are hired as a programmer to develop a system that captures only assessments for 
students.
Submission
Please create a private GitHub repo, copy the content of this quiz and put it in your 
README.md file
Create a file called solu2on.js – this file should contain your soluCon.
Challenge
Write a JavaScript code that calculates a student’s CA mark, Exam Mark, and Final Mark based 
on the following calculaCon criteria. Using JavaScript console.table() method, print out 
the results of the students that should look like this
First Name Surname CA Mark Exam Mark Final Mark Grade
Lukas Hango 67 90 62.8 Very Good
John Shimbuli 72.75 29 46.5 Qualifies for Sup
CA Mark
For CA, students have 4 assessments: each contribuCng 25% towards CA. These assessments 
can be 2 tests and 2 assignments or 3 assignments and 1 test or 4 assignments. To qualify for 
the exam, a student should get a CA mark of above 40. If a student gets less than 40 CA, then 
output, does not qualify for exam and automaCcally put 0 (zero) for exam marks. The marks of 
each student are stored in an object.
Example;
Exam Marks
The exam marks are stored in an array of two elements, the 1st element stores what the student 
got in the exam if the student qualified for exams. Put 0 here if the student did not qualify for 
the exam. The second element stores either “Pass” if the student wrote exams and they got 
more than 50% or “Fail” if the student got less than 50%. if the student did not write exams, the 
second element should be “Does not qualify for Exam”.
Final Marks
The final marks are stored in an array of two elements, the 1st element stores the final mark and 
the second element stores the grade of the student based on the following table
Mark Grade
0 – 45 Fail
46 – 49 Qualifies for Sup
50 – 59 Good
60 – 79 Very Good
80 - 100 Excellent
The weight of CA towards final mark is 40% and the weight of exam marks towards the final 
mark is 60%.
