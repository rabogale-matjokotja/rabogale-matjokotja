<h1 align="center">Rabogale Matjokotja</h1>

<p align="center">
  <b>Aspiring Database Administrator &amp; Systems Analyst</b><br>
  3rd-year Informatics student · Tshwane University of Technology · South Africa
</p>

<p align="center">
  <a href="https://rabogale-matjokotja.github.io"><img alt="Website" src="https://img.shields.io/badge/WEBSITE-000000?style=for-the-badge&logo=githubpages&logoColor=white"></a>
  <a href="mailto:rabomatjuks@gmail.com"><img alt="Email" src="https://img.shields.io/badge/EMAIL-000000?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.instagram.com/rabo.exe"><img alt="Instagram" src="https://img.shields.io/badge/INSTAGRAM-000000?style=for-the-badge&logo=instagram&logoColor=white"></a>
  <a href="https://x.com/rabogale_"><img alt="X" src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"></a>
  <a href="https://www.facebook.com/rabo.hq"><img alt="Facebook" src="https://img.shields.io/badge/FACEBOOK-000000?style=for-the-badge&logo=facebook&logoColor=white"></a>
</p>

---

```sql
SELECT name, role, year
FROM   rabogale
WHERE  learning = 1;
```

```text
name   Rabogale Matjokotja
role   Aspiring DBA & Systems Analyst
year   3rd year, Informatics at TUT
(1 row)
```

I'm early in my career and I learn by building. I pick a real-world problem, design the database for it, write the T-SQL myself and publish the result, including what I'm still figuring out.

---

## 📌 Featured project

### [RetailStock: Inventory & Sales Database](https://github.com/rabogale-matjokotja/retailstock)

> **The problem:** a small retailer needs to know what to reorder and what isn't selling.

An **MS SQL Server** database that answers those questions.

- A relational schema of 10 tables with keys and constraints, plus seed data
- T-SQL queries and views that flag products to reorder and find slow-moving stock
- A static dashboard published with GitHub Pages

**[→ Live dashboard](https://rabogale-matjokotja.github.io/retailstock/)** · **[→ Code](https://github.com/rabogale-matjokotja/retailstock)**

<details>
<summary><b>View the data model</b></summary>

```mermaid
erDiagram
    Categories ||--o{ Products : classifies
    Suppliers ||--o{ Products : supplies
    Products ||--|| Inventory : "stock level"
    Products ||--o{ StockMovements : logs
    Products ||--o{ OrderItems : "sold as"
    Products ||--o{ PurchaseOrderItems : "ordered as"
    Customers ||--o{ Orders : places
    Orders ||--o{ OrderItems : contains
    Suppliers ||--o{ PurchaseOrders : receives
    PurchaseOrders ||--o{ PurchaseOrderItems : contains
```

</details>

## 🔨 In progress

**Community Library & Book Lending System** (T-SQL): a database for members, books, loans and returns, designed from the ERD up and coded by me.

---

## 🧭 How I build

```mermaid
flowchart LR
    A["Understand<br/>the problem"] --> B["Write the<br/>requirements"] --> C["Map the process<br/>and model the data"] --> D["Build it in<br/>tables and T-SQL"]
```

## 🛠️ Skills

![MS SQL Server](https://img.shields.io/badge/MS_SQL_Server-000000?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Java](https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)

| Area | What I can do so far |
|---|---|
| SQL / T-SQL | Joins, views for reporting and indexes to speed up queries |
| Database design | Tables with keys and constraints that keep data valid |
| Java | Classes and objects using core OOP principles |
| System analysis | Requirements, process flows and data modelling |

## 🎯 Next steps

- [ ] T-SQL query tuning and reading execution plans
- [ ] Backup, recovery and security basics for database administration
- [ ] Documenting systems with UML and process diagrams

---

<p align="center">
  <i>Want to talk databases or give feedback on a project?</i><br>
  <a href="mailto:rabomatjuks@gmail.com">rabomatjuks@gmail.com</a>
</p>
