<img src="https://skillicons.dev/icons?i=django,powershell,html,css,js,py" />
<br>

# Students Affairs
Students Affairs is a web-based application built with Django, designed to help educational institutions manage student data, course enrollments, attendance, and grades efficiently. The platform provides a user-friendly interface for administrators, teachers, and students to access important academic information in one place, improving overall communication and record management.

## Features
Student Management System: Manage comprehensive student profiles, including personal information, academic records, and extracurricular involvement.
Course Enrollment: Facilitate the enrollment process by allowing administrators to assign courses to students quickly and efficiently.
Attendance Tracking: Monitor daily student attendance, generate attendance reports, and keep records up-to-date.
Grade Management: Teachers can input, update, and view student grades, with functionality to generate grade reports for easy tracking of academic performance.
User Roles: Different user types such as administrators, teachers, and students, with unique access permissions tailored to their role.
Announcements and Notifications: Keep students and staff informed with real-time announcements for events, exams, or important updates.
Timetable Management: Organize and display class schedules, allowing students and teachers to view their daily and weekly timetables.
Responsive Design: The site is fully responsive and accessible on both desktop and mobile devices, offering a seamless experience across platforms.

## Technologies Used
Django: The application is built using Django, a powerful Python web framework that provides a robust back-end and ensures secure data handling.
Python: The core logic of the application is written in Python, making use of its powerful libraries for web development.
HTML/CSS & JavaScript: Front-end development is achieved using standard HTML, CSS, and JavaScript for a smooth and responsive user experience.
Bootstrap: The site uses Bootstrap to enhance the visual appearance and responsiveness across different screen sizes.
SQLite (or other databases): Default database used is SQLite, but the application can be configured to use PostgreSQL or MySQL as needed.
Authentication: Built-in Django authentication to manage secure login and user roles (admin, teacher, student).

## Installation
To get the project running on your local machine, follow these steps:

1. Clone the repository: ```git clone https://github.com/joeshwoa/Students-Affairs.git```
2. Navigate to the project directory: ```cd Students-Affairs```
3. Create a virtual environment and activate it: ```python -m venv env```
   ```source env/bin/activate  # On Windows use 'env\Scripts\activate'```
4. Install the required dependencies: ```pip install -r requirements.txt```
5. Run database migrations: ```python manage.py migrate```
6. Create a superuser (admin account): ```python manage.py createsuperuser```
7. Run the development server: ```python manage.py runserver```
8. Access the application at http://127.0.0.1:8000/.

## Contributions
Contributions are welcome! If you would like to contribute, please fork the repository, make your changes, and submit a pull request. You can also open an issue if you find any bugs or have feature requests.

## License
This project is licensed under the MIT License.
