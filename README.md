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

- User management with group-based permissions
- Creation and editing of:
  - Subjects
  - Timetables
  - Students and teacher groups
- Grade entry and automatic final grade calculation
- Messaging system for internal communication
- Role-specific interfaces for admins, teachers, students, and parents

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

- Manual user scenario testing (admin/teacher/student/parent)
- Observed and resolved issues related to:
  - Message display and selection
  - Form state persistence after cancellation
  - Group visibility and hierarchy logic
  - Grade form configuration with weights and formulas

## 📊 Technologies Used

- C#
- .NET (Windows Forms)
- MySQL
- Entity Framework
- Visual Studio

## 👥 Project Team

Eustachy Lisiński
Agata Sobczyk  
Karolina Barszcz  
Kamila Młynarczyk  
Artur Ulman  
Miłosz Wojtanek


## 📜 License

Academic project created as part of a university course.

