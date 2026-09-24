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

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=About%20the%20Project&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="📖 About the Project">
</p>

DataTransformer is a hands-on SQL project built in **PostgreSQL**. It uses three simple tables (customers, orders, employees) to practise the most important SQL concepts, from creating tables to writing window functions and conditional logic.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Features&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🎯 Features">
</p>

- ✅ Database and table creation with primary and foreign keys
- ✅ Sample data insertion
- ✅ All 4 types of joins
- ✅ Subqueries with `AVG()`
- ✅ Date and string manipulation
- ✅ Window functions (running total, ranking)
- ✅ `CASE` expressions for categorisation

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Database%20Setup&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🏗️ Database Setup">
</p>

```sql
CREATE DATABASE DataTransformer;
\c DataTransformer
```

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Tables&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="📋 Tables">
</p>

| 🏷️ Table | 🔑 Columns | 📝 Description |
|---|---|---|
| 👤 `Customers_News` | CustomerID (PK), FirstName, LastName, Email, RegistrationDate | Customer details |
| 🛒 `Orders_News` | OrderID (PK), CustomerID (FK), OrderDate, TotalAmount | Orders placed by customers |
| 🧑‍💼 `Employees_News` | EmployeeID (PK), FirstName, LastName, Department, HireDate, Salary | Employee details |

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Relationship&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🔗 Relationship">
</p>

```
Customers_News (1) ───────< (Many) Orders_News
   CustomerID  (PK)              CustomerID (FK)
```

One customer can place many orders.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Sample%20Data&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🧾 Sample Data">
</p>

- 👤 **Customers:** 2 records (IDs 1, 2)
- 🛒 **Orders:** 2 records (IDs 101, 102)
- 🧑‍💼 **Employees:** 2 records (IDs 1, 2)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Queries%20Covered&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🔍 Queries Covered">
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Joins&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🔀 Joins">
</p>
| # | Query | Purpose |
|---|---|---|
| 1 | `INNER JOIN` | Orders with matching customer details |
| 2 | `LEFT JOIN` | All customers and their orders (if any) |
| 3 | `RIGHT JOIN` | All orders and their customers (if any) |
| 4 | `FULL OUTER JOIN` | All customers and all orders, matched or not |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Subqueries&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🧩 Subqueries">
</p>
| # | Purpose |
|---|---|
| 5 | Customers with order amount above the average order amount |
| 6 | Employees with salary above the average salary |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Date%20Functions&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="📅 Date Functions">
</p>
| # | Function | Purpose |
|---|---|---|
| 7 | `EXTRACT` | Get year and month from `OrderDate` |
| 8 | `CURRENT_DATE - OrderDate` | Days between order date and today |
| 9 | `TO_CHAR` | Format date as `DD-Mon-YYYY` |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=String%20Functions&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🔤 String Functions">
</p>
| # | Function | Purpose |
|---|---|---|
| 10 | `CONCAT` | Build full name |
| 11 | `REPLACE` | Replace part of a string |
| 12 | `UPPER` / `LOWER` | Change name casing |
| 13 | `TRIM` | Remove extra spaces from email |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=Window%20Functions&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="📊 Window Functions">
</p>
| # | Function | Purpose |
|---|---|---|
| 14 | `SUM() OVER` | Running total of `TotalAmount` |
| 15 | `RANK() OVER` | Rank orders by amount |

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=80&text=CASE%20Expressions&fontSize=24&fontColor=ffffff&fontAlignY=40" alt="🎛️ CASE Expressions">
</p>
| # | Purpose |
|---|---|
| 16 | Discount tier: > 1000 = 10%, > 500 = 5% |
| 17 | Salary category: High (>= 55000), Medium (>= 40000), Low |

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=How%20to%20Run&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="▶️ How to Run">
</p>

1. 🛠️ Create the database and connect to it.
2. 🧱 Run the `CREATE TABLE` statements in this order: Customers → Orders → Employees.
3. 📥 Run the `INSERT` statements.
4. 🔎 Run the queries one by one and check the output.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Notes&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="📝 Notes">
</p>

- ⚠️ Use table names consistently. Tables are created as `Customers_News`, `Orders_News`, `Employees_News`, so every query and the foreign key must use these same names.
- 💡 With the current sample data, query 11 (`John` → `Jonathan`) and query 16 (discounts) show no changes, because no name is `John` and no order is above 500. Add more rows to see them in action.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Future%20Improvements&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🚀 Future Improvements">
</p>

- ➕ Add more sample data for better results
- 🗂️ Add indexes for faster queries
- 👁️ Create views for common reports
- ⚙️ Add stored procedures and triggers

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Tech%20Used&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="🧰 Tech Used">
</p>

- 🐘 PostgreSQL
- 💾 SQL (DDL, DML, DQL)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&section=header&height=110&text=Author&fontSize=34&fontColor=ffffff&fontAlignY=40" alt="👩‍💻 Author">
</p>

**Kavita Khushalani**

---

<p align="center">Made with ❤️ by <b>Kavita Khushalani</b></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:E0A95F,100:C77BA8&height=100&section=footer" alt="footer">
</p>
