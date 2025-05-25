# mec_portal
A Teacher  Attendance and Lesson Planning management system

I am creating a school app for managing teachers, and their attendance. 
the teachers in turn will manage lesson plans. 
The school head/admin will have the sole access and authority to CRUD teachers. 
Teachers can only view their attendances, and can CRUD lesson plans. It will be built using Django.

teachers/
├── __init__.py
├── models.py
├── views.py
├── urls.py
├── management/
│   ├── __init__.py
│   └── commands/
│       ├── __init__.py
│       └── setup_school.py
└── templates/
    └── teachers/
        ├── landing.html
        ├── headteacher_login.html
        ├── teacher_login.html
        ├── headteacher_dashboard.html
        └── teacher_dashboard.html
