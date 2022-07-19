# Student Report Management System

This is a menu driven C++ based student report management system where there are three users - admin, faculty and student.
All users can login to the system using their respective id and password given by the department at the time of their id creation.

## Admin
Admin has the credentials:

id: admin
password: admin

After login admin menu will open, and he can use his features. 
An admin has the complete access to the system. He can add new students and faculties, modify and delete their data. He can update student scores and can view everyone result. Basically, he has whole data transparency of the system.
Their is a feature called Publish Student Result in admin menu, until it's off Student cannot see his result.

## Faculty
A faculty will login to the system using faculty id and password created by the admin. Then a faculty menu will open and he can select his features there.
He has the features to view his profile, to view any student profile, update student marks. Basically partial access to the system.

## Student
A Student will login to the system using student id and password created by the admin.  Then a student menu will open and he can select his features there.
He has the features to view his profile and to view his final result. Basically limited access to only view his information.

Note: A student cannot view his result until admin review and publish final result in his menu, until then student will be shown "result not published yet status".
