# Library-Book-Management-System-
The Library Book Management System is designed to manage books, library members, and  book borrowing activities in a school or public library.  Many libraries still face challenges such as poor record keeping, missing books, and difficulty  tracking borrowed items due to manual systems.
## 🛠️ Tools Used

- **MySQL** – Database management system  
- **SQL (Structured Query Language)** – Used for querying and managing data  
- **MySQL Workbench** – Database design and administration tool  
- **GitHub** – Version control and project hosting  
- **ER Diagram Tool (Draw.io / Lucidchart)** – Used for designing database diagrams
- ## 📌 Problem Statement

Libraries need an organized way to manage books and track which members have borrowed them.  

Without a proper database system, libraries experience:

- Loss of books  
- Difficulty tracking borrowed and returned books  
- Duplicate book and member records  
- Slow access to information  

This project aims to solve these problems by building a structured and normalized database system.

---

## 📋 Project Questions / Tasks

### 1️⃣ Database Model
- relational database model is suitable for a library management system because its best for structures data and clear relationships and integrity rules   
-  ## 🔐 Data Integrity 
- Tables organize data properly and reduce duplication.
- Primary keys identify each record (no duplicates, no NULLs).
- Foreign keys shows relationships between tables.
- Together, they ensure accurate, consistent, and reliable data.

---

### 2️⃣ Entities, Relationships, and Attributes
- Entities are :- BOOKS, MEMBERS AND BORROWINGS
- Relationships :- Borrows i.e One Member can borrow many books and One Book can be borrowed many times.
- Attributes :- Attributes are Borrow_id(primary key) , member_id (foreign key to members) ,book_id (foreign key to books) , borrow_date , return_date.
---

### 3️⃣ Normalization
Initially, all library data (books, members, borrow details) is stored in a single table.

#### Tasks: 
- Normalization is necessary because it helpes to Prevent storing the same data in multiple places, saving storage space and minimizing update errors.
- 
