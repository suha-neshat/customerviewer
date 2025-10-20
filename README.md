
#  Customer Order Viewer

The **Customer Order Viewer** is a desktop application built to help administrators and staff manage student enrollments and view customer purchase activity.  
It connects a simple graphical user interface (GUI) with backend logic and a database to demonstrate how CRUD operations (Create, Read, Update, Delete) work in a real-world desktop app.

---

## ⚙️ Tech Stack

-  **C# (.NET / WPF)** – Builds the desktop interface with dropdowns, buttons, and list views.  
-  **Entity Framework / LINQ** – Simplifies database access and querying.  
-  **SQL Server / SQLite** – Stores all student, course, and customer order data.  
-  **MVVM Pattern (optional)** – Separates logic from UI for cleaner architecture.  
-  **Console Logging** – Displays real-time purchase or enrollment activity for debugging and verification.

---


###  Enrollment Manager Interface

<img width="1280" height="487" alt="Screenshot_20251019-171644" src="https://github.com/user-attachments/assets/9259a090-6f51-425b-961d-2b9c1a38127a" />

<img width="1052" height="534" alt="Screenshot_20251019-171958" src="https://github.com/user-attachments/assets/136d106f-7d13-429d-a428-1cd7c2657c2a" />


This window shows the **Enrollment Manager**, built in WPF:  
- Dropdowns let you select a **Student** (e.g., *Eusebio*) and **Course** (e.g., *Architecture*).  
- The numbered list displays available course slots or IDs.  
- Buttons at the bottom let you **Save Enrollment** or **Create New Enrollment**.  
- The confirmation message at the bottom ("Enrollment saved") confirms successful database write operations.

 This demonstrates the link between the GUI and database.

---




The console view lists all customer purchase records from the database.  
Each entry includes:  

