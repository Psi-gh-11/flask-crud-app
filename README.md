# Flask CRUD App 📚

A Flask-based CRUD (Create, Read, Update, Delete) web application that demonstrates fundamental web development principles. This project showcases how to build a simple yet functional web application with Flask for managing data persistence.

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **Create**: Add new records to the database ➕
- **Read**: View existing records with filtering and search 👀
- **Update**: Edit records seamlessly ✏️
- **Delete**: Remove records securely 🗑️
- **Responsive Design**: Works seamlessly across all devices 📱💻
- **User-Friendly Interface**: Simple and intuitive UI for easy navigation

## 🛠️ Tech Stack

- **Backend**: Flask (Python web framework) 🐍
- **Database**: SQLite (or configured database in `app.py`)
- **Frontend**: HTML5, CSS3
- **Version Control**: Git & GitHub 📂
- **Package Manager**: pip

## 📦 Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- pip (Python package installer)
- Git
- Virtual environment tool (venv)

## 🚀 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/Psi-gh-11/flask-crud-app.git
cd flask-crud-app
```

### Step 2: Create a Virtual Environment

```bash
# On macOS/Linux
python3 -m venv env
source env/bin/activate

# On Windows
python -m venv env
env\Scripts\activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
python app.py
```

The application will be available at `http://localhost:5000` 🌍

## 📁 Project Structure

```
flask-crud-app/
├── app.py                 # Main Flask application file
├── requirements.txt       # Python dependencies
├── .gitignore            # Git ignore rules (env/, __pycache__/, etc.)
├── LICENSE               # MIT License
├── README.md             # This file
├── templates/            # HTML template files
│   ├── base.html         # Base template with common layout
│   ├── index.html        # Home/list page template
│   ├── create.html       # Create record template
│   ├── edit.html         # Edit record template
│   └── delete.html       # Delete confirmation template
├── static/               # Static files (CSS, JavaScript, images)
│   └── style.css         # Stylesheet
└── instance/             # Instance folder (database files)
    └── app.db            # SQLite database file
```

## 💡 Usage

### Creating a Record
1. Navigate to the "Create" page
2. Fill in the required fields
3. Click "Submit" to add the record to the database

### Viewing Records
- The home page displays all records in a table format
- Use search or filter options to find specific records

### Updating a Record
1. Click the "Edit" button next to a record
2. Modify the information
3. Click "Update" to save changes

### Deleting a Record
1. Click the "Delete" button next to a record
2. Confirm the deletion when prompted

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a new branch for your feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

Please ensure your code follows the existing style and include appropriate comments.

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

The MIT License permits you to:
- ✅ Use the software for any purpose
- ✅ Copy, modify, and distribute
- ✅ Include in proprietary applications

Simply include a copy of the license and copyright notice.

---

## 📚 Learning Resources

- [Flask Documentation](https://flask.palletsprojects.com/)
- [Python Virtual Environments](https://docs.python.org/3/tutorial/venv.html)
- [SQLite Documentation](https://www.sqlite.org/docs.html)

---

**Built with ❤️ by Psi-gh-11**

If you found this project helpful, please consider giving it a ⭐ star!
