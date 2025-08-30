# Smart Expense Tracker (Java + MySQL)

A simple Java-based Expense Tracker with CRUD operations, categorized expenses, total expense calculation, and a Swing UI.

🚀 Features
- Add, view, and delete expenses
- Categorized expense tracking
- Report (total expenses)
- MySQL database for persistence
- Java Swing UI

🛠 Tech Stack
- **Java** (Core + JDBC + Swing)
- **MySQL** (Database)
- **Git** (Version Control)

📂 Setup
1. Import `db_schema.sql` into MySQL.
2. Update database credentials in `DatabaseConnection.java`.
3. Compile & run:
   ```bash
   javac -d bin src/**/*.java
   java -cp bin Main

