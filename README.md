**Project Management System**
A full-stack web application developed using Python, Django REST Framework, and React.js to manage projects, users, and tasks through role-based access control and a structured task verification workflow.

The application provides separate access and dashboard statistics for Admin, Manager, and Member roles, helping teams organize projects, track tasks, and manage task approvals.

**Technologies Used**

Category	Technologies
Programming Languages	Python, JavaScript
Backend	Django, Django REST Framework
Frontend	React.js, HTML5, CSS3
Database	SQLite
Authentication	JWT (JSON Web Token)
Development Tools	Git, GitHub, VS Code, PyCharm
Key Features
User Management and Authentication
Custom user model with Admin, Manager, and Member roles.
JWT-based authentication for secure login and API access.
Role-based permissions and access restrictions.
User profile management.
Project Management
Create and manage projects.
Assign users to projects.
Track project status: Planning, Active, and Completed.
Manage project-related tasks.
Task Management and Verification
Create, assign, update, and manage tasks.
Set task priorities and due dates.
Allow members to mark assigned tasks as completed.
Enable managers and admins to approve or reject completed tasks.
Provide feedback when rejecting tasks.
Allow members to update and resubmit rejected tasks.
Track task verification status.
Role-Based Dashboard
Separate dashboard statistics for Admin, Manager, and Member roles.
Display project and task counts.
Track pending, completed, verified, and rejected tasks.
Provide role-specific project and task information.
**Application Screenshots**
The following screenshots demonstrate the application's interface and major features.

1. Login Page
!Login Page

2. Dashboard
!Dashboard

3. Project Management
!Projects

4. Project Creation Form
!Project Form

5. Task Management
!Tasks

6. Task Creation Form
!Task Form

7. Task Verification
!Task Verification

8. Rejected Task and Feedback
!Rejected Task

9. User Management
!Users

10. User Creation Form
!User Form

Project Structure

text
Projects/
│
├── backend/
│   ├── api/
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── serializers.py
│   │   ├── permissions.py
│   │   └── urls.py
│   │
│   ├── pm_system/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── asgi.py
│   │   └── wsgi.py
│   │
│   └── manage.py
│
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── Output/
│   ├── Dashboard.png
│   ├── Login page.png
│   ├── Projects.png
│   ├── Rejected Task.png
│   ├── Task Verification.png
│   ├── Taskform.png
│   ├── Tasks.png
│   ├── Users.png
│   ├── Usersform.png
│   └── projectform.png
│
└── README.md
Learning Outcomes
Through this project, I gained practical experience in:

Developing RESTful APIs using Django REST Framework.
Building frontend applications using React.js.
Implementing JWT authentication.
Designing relational database models using Django ORM.
Implementing role-based access control.
Developing task management and verification workflows.
Integrating frontend and backend components.
About the Developer
Thatha Mahitha

B.Tech in Electronics and Communication Engineering | 2025

Aspiring Python Full Stack Developer with practical experience in Python, Django, React.js, and REST API development.

GitHub: TMahitha06
LinkedIn: Thatha Mahitha
