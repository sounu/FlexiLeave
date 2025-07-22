

# 📘 FlexiLeave – PHP Leave Management System

**FlexiLeave** is a simple and efficient Leave Management System built using **HTML**, **CSS**, **PHP**, and **MySQL**. It enables employees to request leaves online and allows managers/admins to approve or reject requests with ease. The system also provides a clear view of leave balances and history.

---

## ✨ Features

- 📝 Employee leave request form
- ✅ Admin/Manager approval or rejection
- 📋 View leave status and history
- 📊 Leave balance tracking (Casual, Sick, etc.)
- 🔐 Secure login system (session-based)
- 📂 Admin dashboard to manage employees and requests
- 📁 MySQL database for persistent storage

---

## 🛠️ Tech Stack

| Layer       | Technology        |
|-------------|-------------------|
| Frontend    | HTML, CSS         |
| Backend     | PHP               |
| Database    | MySQL             |
| Hosting     | XAMPP / WAMP / LAMP / Live Server |

---

## 🖼️ Screenshots


---

## 📦 Installation Instructions

```bash
# 1. Clone or download the project
git clone https://github.com/your-username/leaveflow-php.git

# 2. Move the project to your XAMPP or WAMP www/htdocs folder

# 3. Import the SQL database
# Open phpMyAdmin and create a new database (e.g. leaveflow)
# Import the SQL dump file (leaveflow.sql)

# 4. Configure database connection
# In config/db.php or wherever your DB settings are:
$host = "localhost";
$user = "root";
$password = "";
$database = "leaveflow";

# 5. Run the project
# Visit http://localhost/leaveflow in your browser

