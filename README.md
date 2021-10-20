# Student-Management-System

## Group Members

>1. 19BCE183 - Patel Sarthak
>2. 19BCE195 - Patel Jinil
>3. 19BCE220 - Rana Yash


## Project Description

>In our project *Student Management System* has Following features:
1. Student Login: The username of the student will be his *Roll No* and password will be his
*Phone number*.
 * *Attendance Generator*: which displays the attendance of the students.
 * *Fee Status Checker*: which displays the Fee status of the student i.e., Paid, Unpaid, and
Remaining.
 * *ID card*: This displays the ID-Card of the student with unique *Barcode*.
 * *Marksheet*: This displays the Marksheet of the Student and displays Grades respectively. 
 * *Exit*: This will return to the main Homepage of the Student Management System.
<br />

2. Employee Login: The username will be **12345** and Password **admin**.
   <br/>
   (Note: this username and password are just taken as sample)
 * *Manage Marks*: Which manages the Marks of the Student i.e.
 (Allows the employee to edit the marks).
 * *Manage Attendance*: Which handles the attendance of all the Students.
 * *Manage Fee Status*: Which handles the Fee status of the Student.
 * *Register Student*: Which register the new student and also creates his ID-Card.
 * *Exit*: Which exits from the Employee System.

<br />

## Packages:
Installing tkinter using the following command.
```
pip install tk
import tkinter as tk
```
Installing PIL.
```
pip install pillow
import PIL
```
Importing Sqlite3.
```
pip install pysqlite3
import sqlite3
```
Installing Qrcode.
```
pip install qrcode
import qrcode
```
## Running the files:

1. To run the *Student Management System*, we have to first run *StartingFile.py* which opens
 the home page showing two Login features: *Student* and *Employee*.
 
 <img src="Management System/Screenshot/SS1.png">
 
 <br/>
 
2. Let’s first understand the features of faculty side, here we have set only one id-password
for faculty.

Note: You can set it by opening database in command prompt and insert value by sql query.
Here, default id is “12345” and password is “admin”.

<img src="Management System/Screenshot/SS2.png">
 
 <br/>

3. If the password entered is incorrect which is not in database of employee table, then error 
will be displayed as below:

<img src="Management System/Screenshot/SS3.png">
 
 <br/>

4. After entering correct password as given above, you will have a Menu containing 5 items as 
below:
1) Manage Student data.
2) Manage Attendance.
3) Manage Marks.
4) Manage Fee Marks.
5) Exit

<img src="Management System/Screenshot/SS4.png">
 
 <br/>

5. Click the Manage Student, and you will have screen as below where you can add, delete and 
update the data of any student with the details containing roll number, name, gender, email, 
phone and address, etc. You can also search the data by name, roll number, etc in the tree view.

<img src="Management System/Screenshot/SS5.png">
 
 <br/>

6. Click the back button and go to the Manage Attendance page where you have to enter the roll 
number in the text box and click the Check it button after that you can enter the attendance of 
that student by one radio button, which contains value of present and absent, then click ok
after entering your choice.

<img src="Management System/Screenshot/SS6.png">
 
 <br/>

7. If you enter the roll number incorrectly, then you will a below screen:

<img src="Management System/Screenshot/SS7.png">
 
 <br/>

8. Click the back button and go to the Manage Marks where you can manage the marks of 6 subjects 
which are pre-defined as DC, DSA, OOPS, DM, POE, etc. It will add all the marks in database of 
student_marks.

<img src="Management System/Screenshot/SS8.png">
 
 <br/>

9. Click the back button and go to the managing fees status where you will have to enter the 
roll number of a student. If, it is present in data, you can enter his fees status and click the 
ok button.

<img src="Management System/Screenshot/SS9.png">
 
 <br/>

10. On clicking the exit button, you will be on the screen where you have started named as 
HomePage, where you can get two choices as student and faculty.

<img src="Management System/Screenshot/SS10.png">
 
 <br/>

11. Click on the student, enter password and id where password will be your registered phone
number while filling out the form.

<img src="Management System/Screenshot/SS11.png">
 
 <br/>

12. If the entered student roll number is not present in the database, then the following screen 
will be shown:

<img src="Management System/Screenshot/SS12.png">
 
 <br/>

13. On entering the correct details of the student, the menu of that respective student will be 
opened, where the options are available as follows:
1) Generate ID Card.
2) Show Attendance.
3) Show Marksheet.
4) Show Fee Status.
5) Exit.

<img src="Management System/Screenshot/SS13.png">
 
 <br/>

14. Click, the Generate Id Card, where ID Card will be generated for that respective student for 
which you have logged in.

<img src="Management System/Screenshot/SS14.png">
 
 <br/>

15. Click the back button, go to Show Attendance where you can check your attendance entered by 
the faculty.

<img src="Management System/Screenshot/SS15.png">
 
 <br/>

16. Click the back button, and go to the marksheet menu, where the student can get his/her 
marksheet as per the given marks by the faculty.

<img src="Management System/Screenshot/SS16.png">
 
 <br/>

17. If the student is failed in any of the subject, then he will have red coloured marks, and 
even the total grade will be IF as shown in marksheet.

<img src="Management System/Screenshot/SS17.png">
 
 <br/>

18. Here, fees details will be shown to the student as per the details shown below. We have also 
attached the functionality to check if the fees details are not entered by the faculty, then it 
will show the message that “Fees details are not available”.

<img src="Management System/Screenshot/SS18.png">
 
 <br/>


## Conclusion
Thus, this is the python based GUI project which shows the functionality of student 
management system developed with the help of tkinter, PIL, sqlite3 and qrcode.
