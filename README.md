# School Management System

![developer](https://img.shields.io/badge/Developed%20By%20%3A-Ayush-red)
---
## screenshots
### Homepage
Homepage snap[Alt text](static/images/Screenshots/Home.png)
### Admin Dashboard
Dashboard snap[Alt text](static/images/Screenshots/Admin.png)
### Teacher Dashboard
Teacher snap[Alt text](static/images/Screenshots/Tutor.png)
### Student Dashboard
Student snap[Alt text](static/images/Screenshots/Student.png)
---

## Functions

- Admin can add/update/delete/view student
- Admin can add/update/delete/view teacher
- Admin can add/update/delete/view course
- Admin can add/update/delete/view student attendance
- Admin can add/update/delete/view teacher attendance
- Admin can add/update/delete/view notice
- Teacher can view student
- Teacher can view student attendance
- Teacher can view their attendance
- Teacher can view notice
- Teacher can take attendance of student
- Student can view notice
- Student can view their attendance

### Teacher
First the teacher will apply for job,if he/she gets selected there accounts will be made and approved by the admin, after approval only teacher can access their dashboard.
After account approval by admin, teacher can take attendance of any class and view their attendance later.
Teacher can also publish/announce notice to student like submission of assignments.

## Student
First student will take admission/signup.
When their account is approved by admin, only then the student can access their dashboard.
After account approval by admin the student can view their details like attendance.
Student can't view attendance of other student.
Student can't announce, they can only view.

### Admin
First admin will signup for a account.
After login they can see how many student/teacher wants to get job/admission in their school.
They can approve or delete/cancel the request.
They can update any student/teacher details.
Admin can announce notice also.


## Drawbacks
- On update page of teacher/student you must have to update password.
- Anyone can become Admin

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :

``` python -m pip install -r requirements.txt ```


- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/

```
- Now you can explore it

## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Github](https://github.com/Ayushpal11)

