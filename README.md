# flask-transactions-app
# Flask Transactions CRUD App

This project is a simple **financial transaction recording system** built with **Flask**, demonstrating the fundamental **CRUD operations**:

* **Create** → Add a new transaction
* **Read** → View all transactions
* **Update** → Edit an existing transaction
* **Delete** → Remove a transaction

The project serves as a practice application for learning Flask routes, request handling, and template rendering.

---

## 🚀 Features

* **Transaction Records Page**

  * Displays all stored transactions
  * Options to **Add**, **Edit**, and **Delete** entries

* **Add Transaction Page**

  * Create a new entry with **Date** and **Amount**

* **Edit Transaction Page**

  * Update the date and amount of an existing transaction by its ID

---

## 🛠️ Technologies Used

* Python 3
* Flask
* HTML, CSS (Bootstrap 4)
* SQLite (or in-memory data structure, depending on setup)

---

## 📂 Project Structure

```
├── app.py                # Main Flask application
├── templates/            # HTML templates
│   ├── index.html        # Transaction Records page
│   ├── add.html          # Add Transaction page
│   ├── edit.html         # Edit Transaction page
│   └── search.html       # (Optional) Search Transactions
├── static/               # (Optional) CSS/JS files
└── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/TamariToradze/flask-transactions-app.git
   cd flask-transactions-app
   ```

2. **Create a virtual environment** (optional but recommended)

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install flask
   ```

4. **Run the app**

   ```bash
   python app.py
   ```

5. **Open in browser**
   Visit: `http://127.0.0.1:5000/`

---

## 📖 Learning Objectives

By completing this project, you will be able to:

* Implement CRUD operations in Flask
* Work with Flask routes and request handling
* Build multiple endpoint HTML interfaces with Jinja templates
* Manage application flow for real-world style apps

---

## ✨ Demo

Here’s how the application works:

* **Home Page (Transaction Records)** → View all entries and perform actions
* **Add Transaction** → Enter a new transaction
* **Edit Transaction** → Modify existing entry details
* **Delete Transaction** → Remove unwanted records

---

