# 📝 MyToDo App

A simple and **intuitive ToDo application** built with **Flask** and **SQLite** to manage your daily tasks efficiently.

---

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-2.3-lightgrey?logo=flask&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-3.40-lightgrey?logo=sqlite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## ✨ Features

- ✅ Add tasks with **title** and **description**  
- ✅ View all tasks in a **table format**  
- ✅ Update existing tasks  
- ✅ Delete tasks  
- ✅ Tasks are **timestamped**  
- ✅ Responsive design with **Bootstrap 5**  

---

## 🛠 Technologies Used

- **Backend:** Python, Flask  
- **Database:** SQLite (via SQLAlchemy)  
- **Frontend:** HTML, Jinja2 Templates, Bootstrap 5  

---

## 🚀 Installation & Setup

1. **Clone the repository**  

 ```bash
 git clone https://github.com/nandan-byte/ToDo.git
 cd ToDo
```
2. **Create and activate a virtual environment**

```bash
python -m venv env
# Windows
env\Scripts\activate
# Linux/Mac
source env/bin/activate
```
3. **Install dependencies**
```bash
pip install -r requirements.txt

```
4. **Run the application**
```bash
python app.py

```
## 📂 Project Structure
```bash
ToDo/
│
├── app.py              # Main Flask application
├── todo.db             # SQLite database (auto-generated)
├── templates/          # HTML templates
│   ├── base.html       # Main layout
│   ├── index.html      # Homepage
│   └── update.html     # Update task page
├── static/             # Optional CSS/JS files
├── requirements.txt    # Python dependencies
└── README.md           # This file
```
