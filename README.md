# 🗂️ Python File Handling CRUD Project

## 📌 Overview
This project is a simple **File Handling CRUD application** built in Python.  
It allows users to perform the following operations directly from the terminal:
- **Create** a new file and write content
- **Read** an existing file
- **Update** a file (rename, overwrite, or append content)
- **Delete** a file

The project uses Python’s `pathlib` and `os` modules for handling files and directories.

---

## 🚀 Features
- Interactive menu-driven interface
- Safe file creation (prevents overwriting existing files)
- Flexible update options:
  - Rename file
  - Overwrite file content
  - Append new content
- File deletion with existence check
- Error handling for invalid inputs

---

## 📂 Project Structure

file_crud_project/
│── main.py        # Contains all CRUD operations
│── README.md      # Project documentation

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/file-crud-project.git
   cd file-crud-project
Run the script:

bash
python main.py
Follow the on-screen instructions:

Press 1 → Create a file

Press 2 → Read a file

Press 3 → Update a file

Press 4 → Delete a file
