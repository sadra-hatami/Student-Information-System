<div align="center">

# Student Information System
# 🎓

### A C++ console program for student records

A small terminal desk that adds, lists, edits, and deletes students. Records are stored in `users.txt` and stay after the program closes.

<br>

# 👨‍💻 **Sadra Hatami**

### *Developer • Software Engineer • Creator*

<br>

[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![Console](https://img.shields.io/badge/Interface-Console-2C3E50?style=for-the-badge)](https://en.wikipedia.org/wiki/Command-line_interface)
[![File](https://img.shields.io/badge/Storage-users.txt-003B57?style=for-the-badge)](#-project-structure)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/license/mit)
![Open Source](https://img.shields.io/badge/Open_Source-Project-black?style=for-the-badge&logo=github)

<br>

[🌐 GitHub Profile](https://github.com/sadra-hatami)
•
[📧 Email](mailto:sadra.hatami.1732@gmail.com)

</div>

---

# 📑 Table of Contents

- [About](#-about)
- [Why This Project?](#-why-this-project)
- [Key Features](#-key-features)
- [Menu](#-menu)
- [Project Structure](#-project-structure)
- [Technologies](#️-technologies)
- [Build](#-build)
- [Usage](#️-usage)
- [Notes](#-notes)
- [FAQ](#-faq)
- [Contact](#-contact)
- [License](#-license)
- [Support](#-support)

---

# 📖 About

**Student Information System** is a console program written in C++.

The menu can add a student, list the file, modify a record by last name, or delete one. Each record keeps a first name, last name, course, and section. The file used for storage is `users.txt`.

> **Tagline:** *A C++ console program that stores student names, course, and section in a local file.*

---

# 🚀 Why This Project?

A student file is a clean place to practice a menu and record updates.

This one keeps that scope:

- Add more than one student in a row
- List what is already stored
- Find a student by last name and edit the fields
- Delete a match and write the file again

It is a study program, not a school portal.

---

# ✨ Key Features

- ➕ Add records
- 📋 List records
- ✏️ Modify by last name
- 🗑️ Delete by last name
- 💾 Local file storage
- 💻 Console menu only

---

# 🎮 Menu

1. Add Records
2. List Records
3. Modify Records
4. Delete Records
5. Exit Program

A record has first name, last name, course, and section.

---

# 📁 Project Structure

```text
Student-Information-System/
├── main.cpp
├── studentdatabase.cbp
├── users.txt
└── README.md
```

`main.cpp` is the program. `studentdatabase.cbp` opens it in Code::Blocks. `users.txt` is the record file. Do not commit `bin`, `obj`, or an `.exe`.

---

# 🛠️ Technologies

- C++
- Standard library streams
- C file functions for `users.txt`
- No database and no extra packages

---

# 🚀 Build

```bash
git clone https://github.com/sadra-hatami/Student-Information-System.git
cd Student-Information-System
g++ main.cpp -o students
./students
```

On Windows, open `studentdatabase.cbp` in Code::Blocks and build, or use MinGW on `main.cpp`.

---

# ▶️ Usage

1. Build and run from the folder that contains `users.txt`.
2. Add a student.
3. List, modify, or delete by last name.
4. Exit. The file keeps the records.

---

# 📝 Notes

- The program looks for `users.txt` in the working folder. If that file is missing, it creates one.
- Delete rewrites the file through a temporary `temp.dat`.
- This is a practice desk, not a school information system.

---

# ❓ FAQ

### Does it save after exit?

Yes. Records are written to `users.txt`.

### Do I need the `bin` folder?

No. Build creates it again.

### Is this a website?

No. It is a terminal menu.

---

# 📬 Contact

**Developer:**

### Sadra Hatami

📧 [Email](mailto:sadra.hatami.1732@gmail.com)

🌐 [GitHub](https://github.com/sadra-hatami)

---

# 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If this program is useful as a study sample, please consider giving it a ⭐ on GitHub.

---

<div align="center">

## Designed & Developed with ❤️ for the developer community of Iran and the world by **Sadra Hatami**

</div>
