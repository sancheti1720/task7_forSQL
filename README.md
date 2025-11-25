# Task 7 – Creating Views

This task focuses on using SQL **Views** to simplify queries, improve security, and create reusable logic in a database.

---

## **Objective**
- Learn how to create SQL views  
- Use views to hide data, simplify queries, and build reusable SELECT logic  
- Practice derived tables and CHECK OPTION  

---

## 🛠 Tools Used
- SQLite / MySQL Workbench  
- Sample Library Management System database  

---

## Database Tables
The task uses three simple tables:

1. **authors**  
2. **books**  
3. **issued_books**

These tables help demonstrate view creation clearly for students.

---

## What This Task Includes
✔ Creating multiple views  
✔ Using JOINs inside views  
✔ Creating derived table views  
✔ Creating a secure view  
✔ Using WITH CHECK OPTION  
✔ Example SELECT usage  

---

## Views Created
1. **vw_book_details** – Book with Author Name  
2. **vw_issued_books** – Issued Books + Student + Author  
3. **vw_expensive_books** – Books priced above 300  
4. **vw_author_book_count** – Author-wise book count  
5. **vw_student_names** – Secure view showing only student names  
6. **vw_low_price_books** – Books under 400 (write restricted using CHECK OPTION)

---

## How to Run
1. Run table creation SQL  
2. Insert sample data  
3. Run each CREATE VIEW statement  
4. Test using:

```sql
SELECT * FROM vw_book_details;
SELECT * FROM vw_issued_books;
```



## ✔ Completed By
SQL Developer Internship – Task 7  
Views & 
