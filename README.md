# SQL Data Retrieval Lab

## Objective
The objective of this lab is to practice retrieving and analyzing data using SQL read-only queries.  
The tasks include filtering, sorting, aliasing columns, limiting results, and generating derived outputs without modifying the database.

---

# Tables Used

1. Student
2. Faculty
3. Course
4. Enrollment

These tables simulate a simple **College Database System**.

---

# Topics Covered

### 1. Basic Data Display
Using SELECT statements with column aliases to improve readability.

Example:
```sql
SELECT StudentID AS Roll_No, Name AS Student_Name
FROM Student;
