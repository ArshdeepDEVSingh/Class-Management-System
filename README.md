# Class Management System

This project is a minimalistic and interactive **Class Management System** built using Python and Tkinter for graphical user interfaces. The project allows for adding, editing, and managing student data stored in a JSON database.

## Features

- Add new student data, including name, roll number, mobile number, date of birth, and more.
- Edit or remove existing student data.
- GUI built using Tkinter for an intuitive user experience.
- Data storage and retrieval using a JSON database.

## Prerequisites

Ensure you have the following installed on your system:
- Python 3.x
- Tkinter (included by default with Python installations)
- PyInstaller (optional, if creating an executable)

## Installation

go to issues and just download it.

   *Note: This project does not have additional dependencies apart from Tkinter, which comes pre-installed with Python.*

## Usage

1. Run the main script:
    ```bash
    python app.py
    ```
2. Use the GUI to add, edit, or remove student data.

## Building an Executable (Optional)

To create a standalone executable using PyInstaller:
```bash
pyinstaller --onefile --add-data "student_data.json;." app.py
