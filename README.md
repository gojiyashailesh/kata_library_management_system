# ![Library Management System](assets\20241225_231048.png)


# ***Kata Library Management System***

## 🚀 **Objective**
The purpose of this project is to design and implement a **Library Management System** as part of the **Incyubyte Campus Placement Drive** technical round. The system facilitates essential library operations such as book addition, borrowing, returning, and inventory viewing with a focus on scalability, maintainability, and modern software development principles.

---

## 🌟 **Features**
### 📚 **Core Features**
- **Add Book**: Add books to the library with comprehensive details, including ISBN, title, author, and publication year.
- **Borrow Book**: Enable users to borrow books while updating the library inventory.
- **Return Book**: Process book returns and reintegrate them into the library's available stock.
- **View Available Books**: Display all books currently available in the library, presented in a clean tabular format.

### ✅ **Validation Constraints**
- **ISBN Verification**: Ensure every book has a valid **13-digit ISBN** for standardized identification.

---

## 🛠️ **Technology Stack**
- **Programming Language**: Python
- **Development Methodology**: Test-Driven Development (TDD)
- **Libraries & Tools**:
  - `pytest`: Unit testing and TDD framework.
  - `prettytable`: Clean tabular display for book data.
  - `venv`: Virtual environment for dependency isolation.

---

## 📂 **Project Structure**
- **`assets/`**: Contains CSS files for customizing the `test_report.html`.
- **`src/`**: Contains the core modules of the Library Management System.
- **`tests/`**: Includes all test cases for unit testing and validation.
- **`output_visual.txt`**: Demonstrates the working flow of the application.
- **`report.html`**: Detailed HTML report of test cases, generated using `pytest-html`.
- **`menu.py`**: Entry point for running the application.
- **`requirements.txt`**: Lists all required dependencies for the project.
- **`.gitignore`**: Specifies files and directories to be excluded from version control.
- **`venv/`**: Virtual environment for managing dependencies.

---

## 💻 **How to Run**
### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/gojiyashailesh/library_management_system.git
cd library-management-system
```

### 2️⃣ **Setup Virtual Environment**
```bash
python -m venv venv
source venv/bin/activate  #linux/MacOS
venv\Scripts\activate     #Windows
```

### 3️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 4️⃣ **Run the Application**
```bash
python menu.py
```

### 5️⃣ **Execute Test Cases**
```bash
pytest tests/ --html=test_report.html --self-contained-html
```

### 6️⃣ **View Test Report**
Open the `test_report.html` file in your browser for a detailed report of test results.

---

## 🧪 **Development Practices**
- **SOLID Principles**: Ensured modular and scalable code architecture.
- **TDD (Test-Driven Development)**: Created robust functionality by writing failing tests first, then implementing logic to pass them.
- **Version Control**: Maintained granular commit history with descriptive messages to ensure traceability.

---

## 🚧 **Future Enhancements**
- **Data Persistence**: Integrate a database (e.g., SQLite, PostgreSQL) for permanent data storage.
- **User Management**: Add authentication and role-based authorization.
- **Advanced Search**: Implement filters (e.g., by title, author, or genre).
- **GUI**: Develop an interactive graphical interface for better usability.
- **Analytics Dashboard**: Introduce library usage metrics for admins.

---

## 🔍 **Key Highlights**
- **AI-Assisted Development**: Leveraged modern AI tools (e.g., Claude, ChatGPT) for optimized and efficient development.
- **Clean Code**: Emphasized clarity and readability to ensure maintainability.
- **Reporting**: Comprehensive test reporting using `pytest-html` with customization for clarity.

---

## ✨ **Thank You!**
Thank you for exploring this project. This Library Management System represents a blend of strong design principles and modern development practices to meet the technical expectations of the **Team Incyubyte**. Your feedback is highly valued!

---


