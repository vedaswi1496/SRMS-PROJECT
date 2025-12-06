"# SRMS-PROJECT" 
# Student Management System (C Language)

This is a simple terminal-based Student Management System written in C. It supports multiple user roles—**Admin**, **User**, **Staff**, and **Guest**—with different access privileges. The system allows secure login, student record management, and role-specific menus.

---
## Features

- **Login System** with role-based access
- **Admin**: Add, view, search, update, and delete student records
- **User**: View own profile and student list
- **Staff**: View student list
- **Guest**: View public info only
- Data persistence using binary and text files

---

## File Structure

| File Name        | Purpose                                  |
|------------------|------------------------------------------|
| `Application.c`  | Main source code                         |
| `students.dat`   | Binary file storing student records      |
| `credentials.txt`| Text file storing login credentials      |

---

### Compile the Program

gcc Application.c -o student_mgmt