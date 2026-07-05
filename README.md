# BugTracker-JDBC

A desktop-based **Bug Tracking System** built using **Java Swing**, **JDBC**, and **MySQL**. The application helps users manage software bugs by allowing them to create, update, assign, and track bug reports through an intuitive graphical interface.

---

## Features

- User Login and Registration
- Create, View, Update, and Delete Bug Reports
- Assign bugs to developers
- Update bug status (Open, In Progress, Resolved, Closed)
- Set bug priority (Low, Medium, High)
- Search and filter bug reports
- Dashboard to manage all bugs
- MySQL database integration using JDBC

---

## Tech Stack

- **Language:** Java
- **GUI:** Java Swing
- **Database:** MySQL
- **Connectivity:** JDBC
- **IDE:** Eclipse

---

## Project Structure

```
BugTracker-JDBC/
│── src/
│   ├── dao/
│   ├── database/
│   ├── model/
│   ├── ui/
│   ├── util/
│   └── Main.java
│
├── sql/
│   └── bugtracker.sql
│
├── lib/
│   └── mysql-connector.jar
│
└── README.md
```

---

## Prerequisites

Before running the project, ensure you have:

- Java JDK 17 or later
- MySQL Server
- Eclipse IDE (or any Java IDE)
- MySQL Connector/J

---

## Database Setup

### 1. Create the database

```sql
CREATE DATABASE bugtracker;
USE bugtracker;
```

### 2. Import the SQL file

Import the provided SQL script into MySQL.

```
sql/bugtracker.sql
```

### 3. Configure database credentials

Update the database connection details in your Java project.

```java
private static final String URL = "jdbc:mysql://localhost:3306/bugtracker";
private static final String USER = "root";
private static final String PASSWORD = "your_password";
```

---

## Running the Project

1. Clone the repository.

```bash
git clone https://github.com/wonka05/BugTracker-JDBC.git
```

2. Open the project in Eclipse.

3. Add the MySQL Connector JAR to the project's build path.

4. Configure the database credentials.

5. Run the `Main.java` file.

---
