# 📚 Edukujez – Online Gradebook System

A collaborative project developed as part of a Software Engineering course. The application is a Windows Forms-based electronic gradebook system designed to support schools and universities in managing students, subjects, grades, and user interactions.

![image](https://github.com/user-attachments/assets/3411c6cb-de2b-48c4-8cfb-065e09d98a8c)


## 🧠 Project Highlights

- Developed using **C#**, **.NET**, and **Entity Framework**
- Data stored in **MySQL** with ORM mapping
- Modular codebase using repository pattern
- Designed with SOLID principles and layered architecture
- Includes admin, teacher, student, and parent user roles

## 🏗️ Core Features

- User account system with roles: **Administrator, Teacher, Student, Parent**
- **Timetable creation and management** with assignment of subjects, teachers, and classrooms
- **Event calendar** with support for activities, replacements, and scheduling
- **Subject definition** with attached materials, announcements, and grading schemes
- **Partial and final grade entry**, automatically calculated based on predefined rules
- **Messaging system** for internal communication between users
- **Behavior notes and comments** visible to authorized roles (e.g. parents)
- **Group and class management** with teacher and advisor assignments
- **Student progress tracking** accessible to parents

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/agatoneq/Online-Gradebook-Edukujez.git
   ```
2. Open the solution in **Visual Studio**
3. Set up the MySQL database (import schema if provided)
4. Update `App.config` with your local DB connection string
5. Build and run the project

## 🧪 Testing

- Manual scenario-based testing for all user roles (admin, teacher, student, parent)
- Issues identified and resolved:
  - Message delivery and display logic
  - Form cancellation and view state persistence
  - User-role-specific group visibility
  - Weighted grade rules and formula evaluation in final marks

## 🛠️ Technologies Used

- **Backend**: C#, ASP.NET Core, Entity Framework
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQL Server
- **Tools**: Visual Studio, Git

## 👥 Project Team

Eustachy Lisiński – [GitHub](https://github.com/EustachyL)  
Agata Sobczyk – [GitHub](https://github.com/agatoneq)  
Karolina Barszcz – [GitHub](https://github.com/karolinab11)  
Kamila Młynarczyk – [GitHub](https://github.com/KamilaMlyn)  
Artur Ulman – [GitHub](https://github.com/Stam8231)  
Miłosz Wojtanek – [GitHub](https://github.com/ElMilos)


## 📜 License

Academic project created as part of a university course.

