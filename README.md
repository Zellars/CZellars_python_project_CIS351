# CZellars_python_project_CIS351
This Python project will retrieve and display data from an external API to produce meaningful results. In addition to demonstrating proficiency with API integration and data handling, the project will incorporate key principles of the CIA Triad (Confidentiality, Integrity, and Availability). Security measures will be implemented to ensure only authorized access, protect data from tampering, and maintain reliable operation of the program.



---

## 📘 Flask REST API – User Management System

This is a simple RESTful API built with Flask and Flask-RESTful that allows users to be added, viewed, updated, and deleted from a SQLite database.

### 🔧 Features

* GET all users or a specific user by ID
* POST new users with name and email
* PATCH user information (name & email)
* DELETE users by ID
* Input validation with `reqparse`
* Uses SQLAlchemy for ORM
* Cybersecurity-aware with CIA Triad considerations

---

### 🛡️ Security Integration (CIA Triad)

This API includes basic elements of the **CIA Triad**:

* **Confidentiality** – API key header authentication (optional add-on)
* **Integrity** – Validates input data and prevents duplicates
* **Availability** – Graceful error handling to avoid crashes

---

### ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/yourrepo.git
   cd yourrepo
   ```

2. Create instance folder and run the app:

   ```bash
   mkdir instance
   python
   >>> from api import db
   >>> db.create_all()
   >>> exit()
   ```

3. Run the app:

   ```bash
   python api.py
   ```

4. Access the API at:

   ```
   http://127.0.0.1:5000/api/users/
   ```

---

### 🧪 Testing Endpoints

Use [Postman](https://www.postman.com/) or [Thunder Client](https://www.thunderclient.com/) for sending test requests to the API.

---


