# 🏫 Student Management System

A Django-based Student Management System with an intuitive interface and powerful features for administrators, students, and staff.

---

## 🚀 How to Run the Project (Windows + VSCode Friendly)

These steps are ideal for beginners using **File Explorer**, **Command Prompt (CMD)**, and **Visual Studio Code (VSCode)**.

---

### 📋 Step-by-Step Instructions

#### 1. Open File Explorer where you want to save the project

Navigate to the folder where you'd like to clone the project.

#### 2. Open CMD in that folder

Click the address bar → type `cmd` → press **Enter**.

#### 3. Clone the repository

```bash
git clone https://github.com/Assuhh/Student-Management-System.git
```
### 4. Open the folder in VSCode

In VSCode:  
**File > Open Folder** → select the `Student-Management-System` folder you just cloned.

---

### 5. Open a terminal in VSCode

- **Shortcut**: `Ctrl + Shift + ~`  
- **Or** via menu: **Terminal > New Terminal**

✅ Make sure you're in the `Student-Management-System` directory.

---

### 6. Create and activate a virtual environment

```bash
python -m venv .venv
.venv\Scripts\activate.bat
```
### 7. Navigate to the main Django project folder (if necessary)

```bash
cd Project
```
### 8. Install dependencies

```bash
pip install -r requirements.txt
```
### 9. Run database migrations

```bash
python manage.py migrate
```
### 10. Create a superuser (admin login)

```bash
python manage.py createsuperuser
```
### 11. Start the development server

```bash
python manage.py runserver
```
### 11. Start the development server

```bash
python manage.py runserver
```
### 12. Visit the app in your browser

Open your browser and go to:

```plaintext
http://127.0.0.1:8000/
