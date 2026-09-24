# DATA-TRANSFORMER-
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&height=240&section=header&text=DATA%20TRANSFORMER&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Database%20Design%20%7C%20Joins%20%7C%20Functions%20%7C%20Analytics&descSize=22&descAlignY=60" alt="DataTransformer banner">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=F7B500&center=true&vCenter=true&width=600&lines=Learning+SQL+one+query+at+a+time...;PostgreSQL+%7C+17+Queries+%7C+Hands-on+Practice" alt="Typing animation">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Database-PostgreSQL-blue?logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Language-SQL-orange" alt="SQL">
  <img src="https://img.shields.io/badge/Queries-17-green" alt="17 Queries">
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-yellow" alt="Level">
</p>

<p align="center"><i>💭 "Every table holds a story. A good query is just the right question asked at the right time." ✨</i></p>

<p align="center"><b>📦 3 Tables &nbsp;•&nbsp; 🔍 17 Queries &nbsp;•&nbsp; 🧠 6 SQL Concepts &nbsp;•&nbsp; 🐘 PostgreSQL</b></p>

<p align="center">⭐ <i>Practice • Learn • Repeat • Master SQL</i> ⭐</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Table%20of%20Contents&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="📑 Table of Contents">
</p>

| # | 📚 Section | # | 📚 Section |
|---|---|---|---|
| 1 | 📖 About the Project | 8 | 🔍 Queries Covered *(Joins, Subqueries, Date, String, Window, CASE)* |
| 2 | 🎯 Features | 9 | ▶️ How to Run |
| 3 | 🧰 Tech Used & Prerequisites | 10 | 🎓 Learning Outcomes |
| 4 | 🏗️ Database Setup | 11 | 📝 Notes |
| 5 | 📋 Tables (Schema) | 12 | 🚀 Future Improvements |
| 6 | 🔗 Relationship | 13 | 👩‍💻 Author |
| 7 | 🧾 Sample Data | | |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=About%20the%20Project&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="📖 About the Project">
</p>

**DataTransformer** is a hands-on SQL project built in **PostgreSQL**. The goal is to take raw data stored in a few simple tables and *transform* it into useful information using SQL.

The project is built around a small **e-commerce / company** scenario:

| 🎭 Who | 📝 Role in the project |
|---|---|
| 👤 **Customers** | People who register on the platform |
| 🛒 **Orders** | Customers place orders worth some amount of money |
| 🧑‍💼 **Employees** | Staff working in different departments with different salaries |

Using these three tables, the project practises **17 queries** that cover the most commonly used SQL concepts, from combining tables (joins) to ranking rows and creating categories with conditional logic. Every query below has its **purpose, SQL code, explanation and expected output** so it is easy to follow.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Features&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🎯 Features">
</p>

| ✅ Feature | 📝 What it covers |
|---|---|
| 🏗️ Database & table creation | `CREATE DATABASE`, `CREATE TABLE` with data types |
| 🔑 Keys & constraints | `PRIMARY KEY` on every table and `FOREIGN KEY` between orders and customers |
| 📥 Data insertion | `INSERT INTO ... VALUES` with multiple rows in one statement |
| 🔀 Joins | `INNER`, `LEFT`, `RIGHT` and `FULL OUTER JOIN` |
| 🧩 Subqueries | Filtering rows using `AVG()` calculated in an inner query |
| 📅 Date functions | `EXTRACT`, date subtraction with `CURRENT_DATE`, `TO_CHAR` |
| 🔤 String functions | `CONCAT`, `REPLACE`, `UPPER`, `LOWER`, `TRIM` |
| 📊 Window functions | Running total with `SUM() OVER`, ranking with `RANK() OVER` |
| 🎛️ Conditional logic | `CASE WHEN ... THEN ... ELSE ... END` for discounts and salary bands |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Tech%20Used%20%26%20Prerequisites&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🧰 Tech Used & Prerequisites">
</p>

| 🧰 Item | 📝 Details |
|---|---|
| 🐘 Database | PostgreSQL (version 12 or above recommended) |
| 💾 Language | SQL: DDL (create tables), DML (insert data), DQL (select queries) |
| 🖥️ Tools | `psql` command line, pgAdmin, DBeaver or any PostgreSQL client |

**Before you start, you should have:**

- ✔️ PostgreSQL installed and running on your computer
- ✔️ A user with permission to create a database
- ✔️ Basic idea of what a table, row and column are

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Database%20Setup&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🏗️ Database Setup">
</p>

First create the database, then connect to it so that all the tables are created inside it.

```sql
CREATE DATABASE DataTransformer;
```

Connect to the new database (in `psql`):

```sql
\c DataTransformer
```

> 💡 In pgAdmin or DBeaver, simply select the `datatransformer` database from the left panel before running the script.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Tables%20%28Schema%29&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="📋 Tables (Schema)">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Customers_News&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="👤 Customers_News">
</p>

Stores the people who have registered as customers.

| 🔑 Column | 🧬 Data Type | 📌 Constraint | 📝 Meaning |
|---|---|---|---|
| `CustomerID` | `INT` | PRIMARY KEY | Unique ID of each customer |
| `FirstName` | `VARCHAR(50)` | | Customer's first name |
| `LastName` | `VARCHAR(50)` | | Customer's last name |
| `Email` | `VARCHAR(100)` | | Email address |
| `RegistrationDate` | `DATE` | | Date on which the customer registered |

```sql
CREATE TABLE Customers_News(
    CustomerID INT PRIMARY KEY,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    Email VARCHAR(100),
    RegistrationDate DATE
);
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Orders_News&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🛒 Orders_News">
</p>

Stores the orders placed by customers. Each order belongs to exactly one customer.

| 🔑 Column | 🧬 Data Type | 📌 Constraint | 📝 Meaning |
|---|---|---|---|
| `OrderID` | `INT` | PRIMARY KEY | Unique ID of each order |
| `CustomerID` | `INT` | FOREIGN KEY → `Customers_News(CustomerID)` | Who placed the order |
| `OrderDate` | `DATE` | | Date of the order |
| `TotalAmount` | `DECIMAL(10,2)` | | Order value with 2 decimal places |

```sql
CREATE TABLE Orders_News (
    OrderID INT PRIMARY KEY,
    CustomerID INT,
    OrderDate DATE,
    TotalAmount DECIMAL(10,2),
    FOREIGN KEY (CustomerID) REFERENCES Customers_News(CustomerID)
);
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Employees_News&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🧑‍💼 Employees_News">
</p>

Stores the employees of the company.

| 🔑 Column | 🧬 Data Type | 📌 Constraint | 📝 Meaning |
|---|---|---|---|
| `EmployeeID` | `INT` | PRIMARY KEY | Unique ID of each employee |
| `FirstName` | `VARCHAR(50)` | | Employee's first name |
| `LastName` | `VARCHAR(50)` | | Employee's last name |
| `Department` | `VARCHAR(50)` | | Department such as Sales or HR |
| `HireDate` | `DATE` | | Date of joining |
| `Salary` | `DECIMAL(10,2)` | | Salary amount |

```sql
CREATE TABLE Employees_News(
    EmployeeID INT PRIMARY KEY,
    FirstName VARCHAR(50),
    LastName VARCHAR(50),
    Department VARCHAR(50),
    HireDate DATE,
    Salary DECIMAL(10,2)
);
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Relationship&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🔗 Relationship">
</p>

```
 Customers_News                      Orders_News
+------------------+               +------------------+
| CustomerID  (PK) |──────────────<| OrderID     (PK) |
| FirstName        |    1  :  Many | CustomerID  (FK) |
| LastName         |               | OrderDate        |
| Email            |               | TotalAmount      |
| RegistrationDate |               +------------------+
+------------------+

 Employees_News  (standalone table, no relationship)
```

| 🏷️ Term | 📝 Meaning |
|---|---|
| 🔑 **Primary Key (PK)** | Uniquely identifies each row in a table |
| 🔗 **Foreign Key (FK)** | `Orders_News.CustomerID` must always match an existing `Customers_News.CustomerID`, so an order can never belong to a customer that does not exist |
| 👥 **One-to-Many** | One customer can place many orders, but each order belongs to only one customer |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Sample%20Data&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🧾 Sample Data">
</p>
<img width="1536" height="1024" alt="ChatGPT Image Sep 25, 2026, 12_01_30 AM" src="https://github.com/user-attachments/assets/a675aa3e-356d-482a-b396-167b99841734" />





<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Customers%20Data&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="👤 Customers Data">
</p>

| CustomerID | FirstName | LastName | Email | RegistrationDate |
|---|---|---|---|---|
| 1 | kavita | khu | kavita.khu@email.com | 2022-03-15 |
| 2 | bhavika | tha | bhavika.tha@email.com | 2021-11-02 |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Orders%20Data&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🛒 Orders Data">
</p>

| OrderID | CustomerID | OrderDate | TotalAmount |
|---|---|---|---|
| 101 | 1 | 2023-07-11 | 150.50 |
| 102 | 2 | 2023-08-03 | 200.75 |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Employees%20Data&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🧑‍💼 Employees Data">
</p>

| EmployeeID | FirstName | LastName | Department | HireDate | Salary |
|---|---|---|---|---|---|
| 1 | Mark | Johnson | Sales | 2020-01-15 | 50000.00 |
| 2 | Susan | Lee | HR | 2021-03-20 | 55000.00 |

Data is inserted with one `INSERT` statement per table, for example:

```sql
INSERT INTO Orders_News (OrderID, CustomerID, OrderDate, TotalAmount)
VALUES
(101, 1, '2023-07-11', 150.50),
(102, 2, '2023-08-03', 200.75);
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Queries%20Covered&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🔍 Queries Covered">
</p>

| 🧩 Category | 🔢 Queries | 🎯 Skill practised |
|---|---|---|
| 🔀 Joins | 1 – 4 | Combining data from two tables |
| 🧩 Subqueries | 5 – 6 | Query inside a query |
| 📅 Date Functions | 7 – 9 | Working with dates |
| 🔤 String Functions | 10 – 13 | Cleaning and formatting text |
| 📊 Window Functions | 14 – 15 | Running totals and ranking |
| 🎛️ CASE Expressions | 16 – 17 | If-else logic in SQL |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Joins&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🔀 Joins">
</p>

A **join** combines rows from two tables using a related column, here `CustomerID`. The type of join decides which rows are kept.

```
 INNER JOIN         LEFT JOIN          RIGHT JOIN         FULL OUTER JOIN
  ( A ( ∩ ) B )      ( A█( ∩ ) B )      ( A ( ∩ )█B )      ( A█( ∩ )█B )
 only matching     all of A +         all of B +         everything from
 rows              matching B         matching A         both tables
```

#### 1️⃣ INNER JOIN

| 🎯 Purpose | Get all orders together with the details of the customer who placed them |
|---|---|
| 💡 **How it works** | Returns only the rows where `CustomerID` exists in **both** tables. Customers without orders (and orders without customers) are left out |

```sql
SELECT o.OrderID, o.CustomerID, c.FirstName, c.LastName,
       c.Email, o.OrderDate, o.TotalAmount
FROM Customers_News c
INNER JOIN Orders_News o
ON c.CustomerID = o.CustomerID;
```

| OrderID | CustomerID | FirstName | LastName | Email | OrderDate | TotalAmount |
|---|---|---|---|---|---|---|
| 101 | 1 | kavita | khu | kavita.khu@email.com | 2023-07-11 | 150.50 |
| 102 | 2 | bhavika | tha | bhavika.tha@email.com | 2023-08-03 | 200.75 |

#### 2️⃣ LEFT JOIN

| 🎯 Purpose | List **all customers**, along with their orders if they have any |
|---|---|
| 💡 **How it works** | Every row of the left table (`Customers_News`) is kept. If a customer has no order, the order columns show `NULL`. Useful to find customers who never ordered |

```sql
SELECT c.CustomerID, c.FirstName, c.LastName,
       o.OrderID, o.OrderDate, o.TotalAmount
FROM Customers_News c
LEFT JOIN Orders_News o
ON c.CustomerID = o.CustomerID;
```

| CustomerID | FirstName | LastName | OrderID | OrderDate | TotalAmount |
|---|---|---|---|---|---|
| 1 | kavita | khu | 101 | 2023-07-11 | 150.50 |
| 2 | bhavika | tha | 102 | 2023-08-03 | 200.75 |

#### 3️⃣ RIGHT JOIN

| 🎯 Purpose | List **all orders**, along with their customer details if available |
|---|---|
| 💡 **How it works** | Every row of the right table (`Orders_News`) is kept. It is the mirror image of a `LEFT JOIN` |

```sql
SELECT o.OrderID, o.CustomerID, o.OrderDate, o.TotalAmount,
       c.FirstName, c.LastName, c.Email
FROM Customers_News c
RIGHT JOIN Orders_News o
ON c.CustomerID = o.CustomerID;
```

| OrderID | CustomerID | OrderDate | TotalAmount | FirstName | LastName | Email |
|---|---|---|---|---|---|---|
| 101 | 1 | 2023-07-11 | 150.50 | kavita | khu | kavita.khu@email.com |
| 102 | 2 | 2023-08-03 | 200.75 | bhavika | tha | bhavika.tha@email.com |

#### 4️⃣ FULL OUTER JOIN

| 🎯 Purpose | Get **all customers and all orders**, whether they match or not |
|---|---|
| 💡 **How it works** | Combines `LEFT` and `RIGHT` joins. Unmatched rows from either side appear with `NULL` in the other table's columns |

```sql
SELECT c.CustomerID, c.FirstName, c.LastName,
       o.OrderID, o.OrderDate, o.TotalAmount
FROM Customers_News AS c
FULL OUTER JOIN Orders_News AS o
ON c.CustomerID = o.CustomerID;
```

| CustomerID | FirstName | LastName | OrderID | OrderDate | TotalAmount |
|---|---|---|---|---|---|
| 1 | kavita | khu | 101 | 2023-07-11 | 150.50 |
| 2 | bhavika | tha | 102 | 2023-08-03 | 200.75 |

> 📌 With the current sample data every customer has an order, so all four joins give the same rows. Insert a customer with no order to see the difference between them.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Subqueries&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🧩 Subqueries">
</p>

A **subquery** is a `SELECT` written inside another query. Here it calculates an average, and the outer query uses that value to filter rows.

#### 5️⃣ Orders above the average order amount

| 🎯 Purpose | Find customers who placed an order worth more than the average order |
|---|---|
| 💡 **How it works** | The inner query `SELECT AVG(TotalAmount)` returns `175.625`. The outer query keeps only orders with `TotalAmount > 175.625` |

```sql
SELECT c.CustomerID, c.FirstName, c.LastName,
       o.OrderID, o.TotalAmount
FROM Customers_News c
INNER JOIN Orders_News o
ON c.CustomerID = o.CustomerID
WHERE o.TotalAmount > (
    SELECT AVG(TotalAmount)
    FROM Orders_News
);
```

| CustomerID | FirstName | LastName | OrderID | TotalAmount |
|---|---|---|---|---|
| 2 | bhavika | tha | 102 | 200.75 |

#### 6️⃣ Employees above the average salary

| 🎯 Purpose | Find employees who earn more than the company average |
|---|---|
| 💡 **How it works** | The average salary is `(50000 + 55000) / 2 = 52500`, so only employees earning more than that are returned |

```sql
SELECT EmployeeID, FirstName, LastName, Department, Salary
FROM Employees_News
WHERE Salary > (
    SELECT AVG(Salary)
    FROM Employees_News
);
```

| EmployeeID | FirstName | LastName | Department | Salary |
|---|---|---|---|---|
| 2 | Susan | Lee | HR | 55000.00 |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Date%20Functions&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="📅 Date Functions">
</p>

#### 7️⃣ Extract year and month

| 🎯 Purpose | Split an order date into separate year and month columns, useful for monthly or yearly reports |
|---|---|
| 💡 **How it works** | `EXTRACT(part FROM date)` pulls out one part of a date such as `YEAR`, `MONTH` or `DAY` |

```sql
SELECT OrderID, OrderDate,
       EXTRACT(YEAR FROM OrderDate)  AS OrderYear,
       EXTRACT(MONTH FROM OrderDate) AS OrderMonth
FROM Orders_News;
```

| OrderID | OrderDate | OrderYear | OrderMonth |
|---|---|---|---|
| 101 | 2023-07-11 | 2023 | 7 |
| 102 | 2023-08-03 | 2023 | 8 |

#### 8️⃣ Difference in days from today

| 🎯 Purpose | Find how many days ago each order was placed |
|---|---|
| 💡 **How it works** | In PostgreSQL, subtracting one `DATE` from another gives the number of days. `CURRENT_DATE` is today's date |

```sql
SELECT OrderID, OrderDate,
       CURRENT_DATE - OrderDate AS DifferenceInDays
FROM Orders_News;
```

> 📌 The result depends on the day you run the query, so it grows by 1 every day. Example: an order on `2023-07-11` gives the number of days between that date and today.

#### 9️⃣ Format the date as DD-Mon-YYYY

| 🎯 Purpose | Show dates in an easy-to-read format |
|---|---|
| 💡 **How it works** | `TO_CHAR(date, 'format')` converts a date to text. `DD` = day, `Mon` = short month name, `YYYY` = 4-digit year |

```sql
SELECT OrderID,
       TO_CHAR(OrderDate, 'DD-Mon-YYYY') AS FormattedOrderDate
FROM Orders_News;
```

| OrderID | FormattedOrderDate |
|---|---|
| 101 | 11-Jul-2023 |
| 102 | 03-Aug-2023 |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=String%20Functions&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🔤 String Functions">
</p>

#### 🔟 Concatenate first and last name

| 🎯 Purpose | Create a full name column |
|---|---|
| 💡 **How it works** | `CONCAT()` joins values together. A space `' '` is added in the middle |

```sql
SELECT CustomerID,
       CONCAT(FirstName, ' ', LastName) AS FullName
FROM Customers_News;
```

| CustomerID | FullName |
|---|---|
| 1 | kavita khu |
| 2 | bhavika tha |

#### 1️⃣1️⃣ Replace part of a string

| 🎯 Purpose | Replace the text `John` with `Jonathan` in first names |
|---|---|
| 💡 **How it works** | `REPLACE(text, old, new)` swaps every occurrence of `old` with `new`. It only changes the query result, not the stored data |

```sql
SELECT CustomerID,
       REPLACE(FirstName, 'John', 'Jonathan') AS UpdatedFirstName
FROM Customers_News;
```

| CustomerID | UpdatedFirstName |
|---|---|
| 1 | kavita |
| 2 | bhavika |

> 📌 No name contains `John` in the sample data, so nothing changes. Insert a customer named `John` to see it working.

#### 1️⃣2️⃣ Uppercase and lowercase

| 🎯 Purpose | Show first names in CAPITAL letters and last names in small letters |
|---|---|
| 💡 **How it works** | `UPPER()` converts text to capitals and `LOWER()` converts it to small letters |

```sql
SELECT EmployeeID,
       UPPER(FirstName) AS FirstName_Upper,
       LOWER(LastName)  AS LastName_Lower
FROM Employees_News;
```

| EmployeeID | FirstName_Upper | LastName_Lower |
|---|---|---|
| 1 | MARK | johnson |
| 2 | SUSAN | lee |

#### 1️⃣3️⃣ Trim extra spaces

| 🎯 Purpose | Clean the email column by removing spaces at the start and end |
|---|---|
| 💡 **How it works** | `TRIM()` removes leading and trailing spaces. It is very useful when cleaning messy data |

```sql
SELECT CustomerID,
       TRIM(Email) AS TrimmedEmail
FROM Customers_News;
```

| CustomerID | TrimmedEmail |
|---|---|
| 1 | kavita.khu@email.com |
| 2 | bhavika.tha@email.com |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Window%20Functions&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="📊 Window Functions">
</p>

A **window function** does a calculation across a set of rows related to the current row **without collapsing them** into one row (unlike `GROUP BY`). It is written with `OVER (...)`.

#### 1️⃣4️⃣ Running total

| 🎯 Purpose | Show the cumulative sum of order amounts, in order of date |
|---|---|
| 💡 **How it works** | `SUM(...) OVER (ORDER BY OrderDate ...)` adds the current order to all earlier orders. `UNBOUNDED PRECEDING` means "from the first row", up to the `CURRENT ROW` |

```sql
SELECT OrderID, OrderDate, TotalAmount,
       SUM(TotalAmount) OVER (
           ORDER BY OrderDate
           ROWS BETWEEN UNBOUNDED PRECEDING AND CURRENT ROW
       ) AS RunningTotal
FROM Orders_News;
```

| OrderID | OrderDate | TotalAmount | RunningTotal |
|---|---|---|---|
| 101 | 2023-07-11 | 150.50 | 150.50 |
| 102 | 2023-08-03 | 200.75 | 351.25 |

#### 1️⃣5️⃣ Rank orders by amount

| 🎯 Purpose | Give rank 1 to the highest-value order, rank 2 to the next, and so on |
|---|---|
| 💡 **How it works** | `RANK() OVER (ORDER BY TotalAmount DESC)` sorts by amount from high to low. If two orders have the same amount they get the same rank and the next rank is skipped |

```sql
SELECT OrderID, TotalAmount,
       RANK() OVER (ORDER BY TotalAmount DESC) AS OrderRank
FROM Orders_News;
```

| OrderID | TotalAmount | OrderRank |
|---|---|---|
| 102 | 200.75 | 1 |
| 101 | 150.50 | 2 |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=CASE%20Expressions&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🎛️ CASE Expressions">
</p>

`CASE` is SQL's version of **if / else if / else**. Conditions are checked from top to bottom and the first one that is true wins.

#### 1️⃣6️⃣ Discount based on order amount

**🎯 Purpose:** assign a discount label to each order.

| 💰 Condition | 🏷️ Discount |
|---|---|
| `TotalAmount > 1000` | 10% Off |
| `TotalAmount > 500` | 5% Off |
| otherwise | No Discount |

```sql
SELECT OrderID, TotalAmount,
       CASE
           WHEN TotalAmount > 1000 THEN '10% Off'
           WHEN TotalAmount > 500  THEN '5% Off'
           ELSE 'No Discount'
       END AS Discount
FROM Orders_News;
```

| OrderID | TotalAmount | Discount |
|---|---|---|
| 101 | 150.50 | No Discount |
| 102 | 200.75 | No Discount |

> 📌 Both orders are below 500, so both get `No Discount`. Try inserting an order of 600 or 1200 to see the other labels.

#### 1️⃣7️⃣ Salary category

**🎯 Purpose:** group employees into salary bands.

| 💰 Condition | 🏷️ Category |
|---|---|
| `Salary >= 55000` | High |
| `Salary >= 40000` | Medium |
| otherwise | Low |

```sql
SELECT EmployeeID, FirstName, LastName, Salary,
       CASE
           WHEN Salary >= 55000 THEN 'High'
           WHEN Salary >= 40000 THEN 'Medium'
           ELSE 'Low'
       END AS SalaryCategory
FROM Employees_News;
```

| EmployeeID | FirstName | LastName | Salary | SalaryCategory |
|---|---|---|---|---|
| 1 | Mark | Johnson | 50000.00 | Medium |
| 2 | Susan | Lee | 55000.00 | High |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=How%20to%20Run&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="▶️ How to Run">
</p>

1. 🛠️ **Create the database** and connect to it:
   ```sql
   CREATE DATABASE DataTransformer;
   \c DataTransformer
   ```
2. 🧱 **Create the tables** in this order (Customers first, because Orders depends on it):
   `Customers_News` → `Orders_News` → `Employees_News`
3. 📥 **Insert the sample data** into each table.
4. 🔎 **Run the 17 queries** one by one and compare your output with the tables shown above.

Or run the whole script from the terminal:

```bash
psql -U postgres -d DataTransformer -f your_script.sql
```

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Learning%20Outcomes&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🎓 Learning Outcomes">
</p>

After completing this project you will be able to:

- ✅ Design tables with the right data types, primary keys and foreign keys
- ✅ Insert and organise data in related tables
- ✅ Choose the correct join for a given problem
- ✅ Use subqueries to compare rows with an average
- ✅ Extract, calculate and format dates
- ✅ Clean and transform text with string functions
- ✅ Calculate running totals and rankings using window functions
- ✅ Create categories and labels with `CASE`

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Notes&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="📝 Notes">
</p>

> ⚠️ **Use table names consistently.** Tables are created as `Customers_News`, `Orders_News` and `Employees_News`, so every query and the foreign key must use these exact names (with the **s**). Using `Customers_New` will give a *relation does not exist* error.

> 💡 With the current sample data, query 11 (`John` → `Jonathan`) and query 16 (discounts) show no changes, because no name is `John` and no order is above 500. Add more rows to see them in action.

> 🕒 Query 8 gives a different answer every day because it uses `CURRENT_DATE`.

> 🔤 PostgreSQL folds unquoted names to lowercase, so `Customers_News` and `customers_news` are the same table.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Future%20Improvements&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🚀 Future Improvements">
</p>

| 🚀 Idea | 📝 What it adds |
|---|---|
| ➕ More sample data | Customers without orders and bigger orders, to see every join and `CASE` result |
| 🗂️ Indexes | Faster searches on `CustomerID` and `OrderDate` |
| 👁️ Views | Saved queries for common reports such as customer orders |
| 📈 `GROUP BY` and aggregates | Total sales per customer or per month |
| ⚙️ Stored procedures and triggers | Automatic actions when data changes |
| 🔒 Constraints | `NOT NULL`, `UNIQUE` on email, `CHECK` for positive amounts |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Thought&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="💭 Thought">
</p>

> *"Every table holds a story. A good query is just the right question asked at the right time."* ✨

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Author&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="👩‍💻 Author">
</p>

**Kavita Khushalani**

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:E0A95F,100:C77BA8&height=4" width="100%" alt="divider">
</p>

<p align="center">Made with ❤️ by <b>Kavita Khushalani</b></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&height=100&section=footer" alt="footer">
</p>
