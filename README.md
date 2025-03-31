## D2L Messaging App

## Project Purpose
This project is capstone project built with ASP.NET Core. It's a messaging app to allow students to message each other in real time. 

## Setup Instructions

### **Prerequisites**
#### **Software Required:**
- Visual Studio 2022 with the following workloads:
  - ASP.NET and web development
  - SQL Server Management Studio (SSMS)
- Git

#### **Local Environment Requirements:**
- A local instance of SQL Server. You'll need to create your own instance of "appsettings.json".

---

### **Steps to Clone and Run the App**
#### **1. Clone the Repository**
Open Git Bash, navigate to the folder where you want to save the project, and run:

```sh
git clone https://github.com/amandaestevs/INFO2300_A3.git
cd INFO2300_A3
```
#### 2. Reapplying Migrations
Note: Migrations were removed for this assignment. If you encounter errors related to database migrations, you may need to reapply them.

- Open Visual Studio.  
- Navigate to Tools > NuGet Package Manager > Package Manager Console.  
- Run the following commands:
   ```sh
   Add-Migration InitialCreate
   Update-Database
