<div align="center">

# 🗂️ Company Management App

### A desktop company management system built with Python and PyQt5

A simple GUI application for managing employees, tasks, deadlines, and project milestones in one local desktop workspace.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![PyQt5](https://img.shields.io/badge/PyQt5-GUI-green?style=for-the-badge)
![Desktop App](https://img.shields.io/badge/Desktop-Application-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Final%20Project-orange?style=for-the-badge)

</div>

---

## 📌 Overview

**Company Management App** is a Python desktop application designed to help manage basic company operations through a graphical interface.  
The app provides separate sections for employee management and task management, allowing users to add, edit, delete, and organize company data locally.

This project was developed as a final project and demonstrates GUI programming, event-driven application design, data persistence, and basic management-system logic using **Python** and **PyQt5**.

---

## ✨ Features

### 👥 Employee Management
- Add new employees
- Edit employee information
- Delete employees
- Store employee details such as:
  - Name
  - ID
  - Gender
  - Age
  - Join date
  - Assigned tasks
  - Finished tasks
  - Unfinished tasks

### ✅ Task Management
- Add new tasks
- Edit task details
- Delete tasks
- Assign tasks to people
- Set task start date and deadline
- Define task importance level

### 🎯 Milestone Management
- Add milestones to tasks
- Set milestone deadlines
- Display remaining days until milestone deadline
- Show warning text when a milestone deadline has passed

### 💾 Local Data Storage
- Uses `pickle` for saving and loading application data locally
- Keeps employees, tasks, and milestones available between sessions

### 🖥️ Graphical User Interface
- Built with **PyQt5**
- Multiple `.ui` files for different application windows
- Styled dark-themed interface
- Table-based data display
- Buttons for add, edit, delete, and milestone actions

---

## 🧰 Technologies Used

| Technology | Purpose |
|---|---|
| **Python** | Main programming language |
| **PyQt5** | GUI framework |
| **Qt Designer `.ui` files** | Interface layout design |
| **Pickle** | Local data persistence |
| **QTableWidget** | Displaying employees and tasks |
| **QDate / QCalendarWidget** | Date selection and deadline handling |

---

## 🕹️ How to Use

### Main Menu
After launching the app, the main window allows you to choose between:

- **Employees Section**
- **Tasks Section**

### Employees Section
In this section, you can:
1. View all registered employees.
2. Add a new employee using the add button.
3. Edit employee information.
4. Delete an employee from the list.

### Tasks Section
In this section, you can:
1. View all tasks.
2. Add a new task with deadline and importance.
3. Edit existing task details.
4. Delete a task.
5. Add milestones to a task.

### Milestones
Each task can include milestones with individual dates.  
The app calculates how many days remain until each milestone deadline.

---

## 📸 Application Preview

> Screenshots can be added here after capturing the main menu, employee page, task page, and milestone window.

```text
Main Menu → Employees Section / Tasks Section
Employees Section → Add / Edit / Delete Employees
Tasks Section → Add / Edit / Delete Tasks + Add Milestones
```

---

## 👨‍💻 Author

**Mohammad Barabadi**

GitHub: [@mohammadbrd](https://github.com/mohammadbrd)

---

## 📄 License

No license file is currently included in this repository.  
If this project is intended to be open source, consider adding a license such as MIT.

---

<div align="center">

### ⭐ If you find this project useful, consider giving it a star!

</div>
