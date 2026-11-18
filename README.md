**PROJECT MANAGEMENT SYSTEM**

A full-stack web application developed using Python, Django REST Framework, and React.js to manage projects, users, and tasks through role-based access control and a structured task verification workflow.

The application provides separate access and dashboard statistics for Admin, Manager, and Member roles, helping teams organize projects, track tasks, and manage task approvals.

**TECHNOLOGIES USED**

**Programming Languages:** Python, JavaScript

**Backend:** Django, Django REST Framework

**Frontend:** React.js, HTML5, CSS3

**Database:** SQLite

**Authentication:** JWT (JSON Web Token)

**Development Tools:** Git, GitHub, VS Code, PyCharm

**KEY FEATURES**

**1. USER MANAGEMENT AND AUTHENTICATION**

*Custom user model with Admin, Manager, and Member roles.


*JWT-based authentication for secure login and API access.

*Role-based permissions and access restrictions.

*User profile management.

**2. PROJECT MANAGEMENT**

*Create and manage projects.

*Assign users to projects.

*Track project status: Planning, Active, and Completed.

*Manage project-related tasks.

**3. TASK MANAGEMENT AND VERIFICATION**

*Create, assign, update, and manage tasks.

*Set task priorities and due dates.

*Allow members to mark assigned tasks as completed.

*Enable managers and admins to approve or reject completed tasks.

*Provide feedback when rejecting tasks.

*Allow members to update and resubmit rejected tasks.

*Track task verification status.

**4. ROLE-BASED DASHBOARD**

*Separate dashboard statistics for Admin, Manager, and Member roles.

*Display project and task counts.

*Track pending, completed, verified, and rejected tasks.

*Provide role-specific project and task information.

**APPLICATION SCREENSHOTS**

**1. LOGIN PAGE**

![Login Page](Output/Login%20page.png)

**2. DASHBOARD**

![Dashboard](Output/Dashboard.png)

**3. PROJECT MANAGEMENT**

![Project Management](Output/Projects.png)

**4. PROJECT CREATION FORM**

![Project Creation Form](Output/projectform.png)

**5. TASK MANAGEMENT**

![Task Management](Output/Tasks.png)

**6. TASK CREATION FORM**

![Task Creation Form](Output/Taskform.png)

**7. TASK VERIFICATION**

![Task Verification](Output/Task%20Verification.png)

**8. REJECTED TASK AND FEEDBACK**

![Rejected Task](Output/Rejected%20Task.png)

**9. USER MANAGEMENT**

![User Management](Output/Users.png)

**10. USER CREATION FORM**

![User Creation Form](Output/Usersform.png)




**PROJECT STRUCTURE**

- **backend/**
  - **api/**
    - `models.py`
    - `views.py`
    - `serializers.py`
    - `permissions.py`
    - `urls.py`
  - **pm_system/**
    - `settings.py`
    - `urls.py`
    - `asgi.py`
    - `wsgi.py`
  - `manage.py`

- **frontend/**
  - `public/`
  - `src/`
  - `package.json`

- **Output/**
  - `Dashboard.png`
  - `Login page.png`
  - `Projects.png`
  - `Rejected Task.png`
  - `Task Verification.png`
  - `Taskform.png`
  - `Tasks.png`
  - `Users.png`
  - `Usersform.png`
  - `projectform.png`

- `README.md

**LEARNING OUTCOMES**

Through this project, I gained practical experience in:

*Developing RESTful APIs using Django REST Framework.

*Building frontend applications using React.js.

*Implementing JWT authentication.

*Designing relational database models using Django ORM.

*Implementing role-based access control.

*Developing task management and verification workflows.

*Integrating frontend and backend components.

**ABOUT THE DEVELOPER**

**THATHA MAHITHA**

B.Tech in Electronics and Communication Engineering | 2025

Aspiring Python Full Stack Developer with practical experience in Python, Django, React.js, and REST API development.

**GitHub:** https://github.com/TMahitha06

**LinkedIn:** https://www.linkedin.com/in/t-mahitha-a34a65291/


