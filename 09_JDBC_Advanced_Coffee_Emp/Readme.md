# ☕ 9_JDBC_Advanced_Coffee_and_Emp

This module showcases **advanced JDBC operations using JSP** with conditional logic and dynamic queries on MySQL tables. It focuses on deletion and selection based on specific conditions for both `Coffee` and `Employee` entities.

Each task includes JSP files, database setup scripts, and output screenshots.

---

## 🗑️ 9a. Delete Coffee Record by ID

This part demonstrates:
- Deleting a coffee record using its unique `id`

### 📄 JSP Files:
- [`index.jsp`](./09A_DeleteCoffeeRecord_ByID/src/main/webapp/index.jsp)
- [`deleteCoffee.jsp`](./09A_DeleteCoffeeRecord_ByID/src/main/webapp/deleteCoffee.jsp)

### 📂 SQL Setup:
- [`database_setup.sql`](./09A_DeleteCoffeeRecord_ByID/database/database_setup.sql)

### 🔗 Output Screens:
- [9a.png](./09A_DeleteCoffeeRecord_ByID/9a.png)

---

## 🔍 9b. Show Coffee Records with Names Starting with 'D'

This part demonstrates:
- Fetching and displaying coffee records whose names start with the letter **'D'**

### 📄 JSP Files:
- [`index.jsp`](./09B_ShowCoffeeRecords_NamesStartingWithD/src/main/webapp/index.jsp)
- [`queryCoffeeStartD.jsp`](./09B_ShowCoffeeRecords_NamesStartingWithD/src/main/webapp/queryCoffeeStartD.jsp)

### 📂 SQL Setup:
- [`database_setup.sql`](./09B_ShowCoffeeRecords_NamesStartingWithD/database/database_setup.sql)

### 🔗 Output Screens:
- [9b.png](./09B_ShowCoffeeRecords_NamesStartingWithD/9b.png)

---

## ➕ 9c. Append New Employee Record

This part demonstrates:
- Inserting a new employee record via JSP form into the `Emp` table

### 📄 JSP Files:
- [`index.jsp`](./09C_AppendNewEmployeeRecord/src/main/webapp/index.jsp)
- [`appendEmp.jsp`](./09C_AppendNewEmployeeRecord/src/main/webapp/appendEmp.jsp)

### 📂 SQL Setup:
- [`database_setup.sql`](./09C_AppendNewEmployeeRecord/database/database_setup.sql)

### 🔗 Output Screens:
- [9c.png](./09C_AppendNewEmployeeRecord/9c.png)
- [9c0.png](./09C_AppendNewEmployeeRecord/9c0.png)

---

## ✂️ 9d. Delete Employees Whose Names Start with 'S'

This part demonstrates:
- Deleting all employee records from the `Emp` table where names begin with **'S'**

### 📄 JSP Files:
- [`index.jsp`](./09D_DeleteEmployees_NamesStartWithS/src/main/webapp/index.jsp)
- [`deleteEmpNameStartS.jsp`](./09D_DeleteEmployees_NamesStartWithS/src/main/webapp/deleteEmpNameStartS.jsp)

### 📂 SQL Setup:
- [`database_setup.sql`](./09D_DeleteEmployees_NamesStartWithS/database/database_setup.sql)

### 🔗 Output Screens:
- [9d.png](./09D_DeleteEmployees_NamesStartWithS/9d.jpg)
- [9d0.png](./09D_DeleteEmployees_NamesStartWithS/9d0.jpg)

