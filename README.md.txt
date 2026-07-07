# RepoPulse – DBMS Project

## 📌 Overview

**RepoPulse** is a Database Management System (DBMS) project that models the backend database of a Git-based source code hosting platform similar to GitHub. The project focuses on designing a normalized relational database capable of managing repositories, users, commits, branches, pull requests, issues, releases, and collaboration features.

The schema is designed with scalability, data integrity, and efficient relationship management in mind.

---

## 🚀 Features

* 👤 User Management
* 📂 Repository Management
* 🌿 Branch & Commit Tracking
* 🤝 Repository Collaborators
* ⭐ Repository Stars & Watchers
* 📝 Issue Tracking
* 🔀 Pull Request Management
* ✅ Pull Request Reviews
* 🏷️ Labels & Milestones
* 📢 Notifications
* 💬 Discussion Comments
* 🚀 Releases & Tags
* 📊 User Activity Logs
* 🔒 User Blocking & Reporting
* 📌 Repository Pinning
* 📈 Repository Clone Statistics

---

## 🗂️ Project Structure

```
RepoPulse/
│
├── database/
│   ├── DDL.sql              # Complete database schema
│   ├── seed.sql             # Sample data
│   ├── DESIGN.md            # Database design notes
│   ├── normalization.md     # Normalization proofs
│   └── ERD.png              # Entity Relationship Diagram
│
└── README.md
```

---

## 🛠️ Technologies Used

* PostgreSQL
* SQL (DDL)
* Relational Database Design
* Entity Relationship (ER) Modeling
* Database Normalization (1NF, 2NF, 3NF, BCNF)

---

## 🗄️ Database Design

The database consists of multiple interconnected tables representing the major components of a Git hosting platform, including:

* Users
* Repositories
* Commits
* Branches
* Repository Files
* File Versions
* Pull Requests
* Pull Request Reviews
* Issues
* Issue Labels
* Milestones
* Repository Releases
* Repository Tags
* Notifications
* Collaborators
* Repository Stars
* Repository Watchers
* User Activity Logs
* User Reports
* User Blocks
* Repository Clones
* Pinned Repositories

The schema uses:

* Primary Keys
* Foreign Keys
* Composite Keys
* Unique Constraints
* Check Constraints
* Identity Columns

to ensure consistency and referential integrity.

---

## 📐 Normalization

The database has been normalized to reduce redundancy and improve consistency.

* ✅ First Normal Form (1NF)
* ✅ Second Normal Form (2NF)
* ✅ Third Normal Form (3NF)
* ⚠️ Mostly BCNF (with a few intentional practical exceptions)

Detailed explanations are available in:

```
database/normalization.md
```

---

## 📊 Entity Relationship Diagram

The ER Diagram illustrating the database structure is available in:

```
database/ERD.png
```

---

## ⚙️ Setup Instructions

1. Clone the repository.

```bash
git clone https://github.com/<your-username>/RepoPulse.git
```

2. Open PostgreSQL.

3. Execute the schema.

```sql
database/DDL.sql
```

4. (Optional) Insert sample data.

```sql
database/seed.sql
```

---

## 🎯 Learning Objectives

This project demonstrates:

* Relational database design
* ER modeling
* SQL DDL scripting
* Referential integrity
* Database normalization
* Constraint implementation
* Modeling real-world software systems

---

## 📚 Future Enhancements

* Stored Procedures
* Triggers
* Views
* Index Optimization
* Role-Based Access Control
* Query Optimization
* Backup & Recovery Scripts

---

## 👨‍💻 Author

Developed as a **Database Management System (DBMS)** academic project to demonstrate database design principles and SQL implementation.

---

## 📄 License

This project is intended for educational and academic purposes.
