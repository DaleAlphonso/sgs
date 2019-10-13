We have created a database (Student grading system ) where a professor can login the system by the given username and password 
provided to the database already. If the password and username are match it goes to the next page where all students marks are
displayed with their percentage and to see a data of a particular student one can click on any  row of the table and the data on
that tuple will displayed on the textbox .
When a subject teacher wants to see the marks of all student for a particular course , a search textbox is provided where the 
professor has to enter the name of the course and the marks of all student for that course will be displayed on the Jtable. 
But if the username and password are not matched it will show a dialog box with a message.

Student grading system Database consist of tables like person_table , department_table, ca_table , course_table and exam_table.
person_table :Information about the student and teacher; RollId , pname, dob , age , p-addr,emailid,ptype(Student/teacher),password
dept_code.
department:dept_code,dept_name.
course:course_id, course_name , sem and year .
ca:rollid, courseid , ia1 , ia2, ut1 ,ut2,ca_id.
exam :rollid , courseid,ese,prac,oral,tw,exam_id.
