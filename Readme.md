# Java Programming Assignment – Karthikeya JS (4AL22CS072)

This repository provides a well-organized collection of 28 Java programs covering key concepts such as data structures, string manipulation, graphical interfaces using Swing, web development with Servlets and JSP, and database interaction using JDBC.

---

## 📁 Directory Overview

- [01_Array_vs_LinkedList](./1_arrayList_and_linkedList)
- [02_String_Handling_and_Performance](./2_string_handling_and_performance)
- [03_String_Operations_and_Exercises](./3_String_Operations_and_Exercises)
- [04_Swing_Basics_and_Buttons](./4_swing_basics_and_buttons)
- [05_JList_and_TabbedPane](./5_jList_and_tabbedPane)
- [06_Servlet_Basics](./6_servlet_basics)
- [07_JSP_Session_and_Cookie_Management](./7_jsp_session_and_cookie_management)
- [08_JDBC_Coffee_and_Employee_CRUD](./8_jdbc_coffee_and_emp_crud)
- [09_JDBC_Advanced_Coffee_and_Employee](./9_jdbc_advanced_coffee_and_emp)

---

## 🛠️ JDBC Setup Guide

To execute the database-related programs in folders `08_JDBC_Coffee_and_Employee_CRUD` and `09_JDBC_Advanced_Coffee_and_Employee`, please follow these steps:

### 1. Install XAMPP
Get XAMPP from the official website:  
🔗 [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)

### 2. Start Required Services
Launch XAMPP Control Panel and ensure the following are running:
- **Apache**
- **MySQL**

### 3. Database Configuration
1. Open your browser and go to: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
2. Click on the **Import** tab.
3. Choose the `database.sql` file included in the project.
4. Hit **Go** to create the necessary tables (like `coffee`, `Emp`, etc.)

### 4. Install Apache Tomcat
Download and set up Tomcat from:  
🔗 [https://tomcat.apache.org/](https://tomcat.apache.org/)

- Configure it as your server for JSP and Servlet files.
- Deploy your project by placing JSP/Servlet files inside the `webapps` folder or configure it through your IDE (e.g., Eclipse or IntelliJ).

### 5. Add JDBC Driver to Your Project
- Download the **MySQL JDBC Driver** from:  
  🔗 [https://dev.mysql.com/downloads/connector/j/](https://dev.mysql.com/downloads/connector/j/)
- Add the `.jar` file to your project’s classpath.  
  *(Eclipse: Right-click project → Build Path → Add External JARs)*

### 6. Edit Connection Configuration
Ensure the database connection string matches your setup in `Connection.java` or `DBConnect.jsp`:
```java
Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/your_db_name", "root", "");
