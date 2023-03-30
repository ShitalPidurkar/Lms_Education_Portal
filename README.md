# Lms_Education_Portal
This is a web-based learning management system built with Python Django. It allows teachers to create courses, add course materials, and manage students. Students can sign up for courses, view course materials, and submit assignments.

Requirements
Python (version 3.6 or higher)
Django (version 3.1 or higher)
MySQL database

Installation
Clone the repository: git clone https://github.com/your-username/lms.git
Install the required packages: pip install -r requirements.txt
Create a MySQL database and update the DATABASES setting in settings.py accordingly.
Run database migrations: python manage.py migrate
Create a superuser: python manage.py createsuperuser
Start the development server: python manage.py runserver

Usage
Admin
As an admin, you have full control over the LMS system. You can perform the following tasks:
- Create new instructors and learners
- View and edit information about instructors and learners
- View and edit all courses, including the ability to delete courses if necessary
- Monitor the progress of all students in all courses

To use the LMS as an admin:
- Log in with your superuser account.
- Click on the "Admin" link in the navigation menu.
- From here, you can add, view, and edit users and courses.

Instructor
As an instructor, you have control over the courses that you teach. You can perform the following tasks:
- Create new courses
- Edit course information, such as course name and description
- Add and manage course materials, such as lecture notes, assignments, and quizzes
- View and grade student assignments and quizzes
- View the progress of your students in your courses

To use the LMS as an instructor:
- Log in with your instructor account.
- Click on the "My Courses" link in the navigation menu.
- From here, you can create new courses or select an existing course to manage.

Learner
As a learner, you have the ability to enroll in courses and track your progress. You can perform the following tasks:
- Browse and search for courses
- Enroll in courses
- View course materials, such as lecture notes, assignments, and quizzes
- Submit assignments and quizzes
- View your progress in enrolled courses

To use the LMS as a learner:
- Log in with your learner account.
- Click on the "Browse Courses" link in the navigation menu.
- From here, you can search for and enroll in courses, view course materials, and submit assignments and quizzes.

Credits
This project was created by Shital Pidurkar.
