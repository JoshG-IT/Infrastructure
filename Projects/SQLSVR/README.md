<!-- ============================================================
⚠️ EDUCATIONAL USE ONLY DISCLAIMER
Author: Joshua Gonzalez
Applies To: All repositories, labs, and educational templates under this account
============================================================ -->

> ## ⚠️ Educational Use Only — Read Before Proceeding  
>
> **Purpose:**  
> All content within any repository published by **Joshua Gonzalez** (including PDFs, Markdown files, scripts, templates, and lab instructions) is provided **strictly for educational, training, and demonstration purposes**.  
>
> **Usage Conditions:**  
> - These materials are **not intended for production or commercial use**.  
> - You are fully responsible for **any configurations, deployments, or cloud costs** incurred while following these labs.  
> - The author, **Joshua Gonzalez**, assumes **no liability** for data loss, misconfiguration, or financial impact caused by misuse or misunderstanding.  
> - Do **not** include real credentials, company data, or personal information.  
> - These labs exist for **learning, experimentation, and personal portfolio growth** only.  
>
> **Legal Notice:**  
> By accessing or using these materials, you acknowledge that you understand and accept these terms in full.  
>
> Joshua Gonzalez — Educational Training Content.  
> Redistribution or commercial resale of these materials (including anything produced or posted by Joshua Gonzalez) is **strictly prohibited without written consent**.

---

[![Hypervisor](https://img.shields.io/badge/Hypervisor-Hyper--V-orange?style=for-the-badge&logo=microsoft)](https://www.microsoft.com/en-us/virtualization/hyper-v-on-windows)
[![Windows Server](https://img.shields.io/badge/Windows-Server%202022-blue?style=for-the-badge&logo=windows)](https://www.microsoft.com/windows-server)
[![SQL](https://img.shields.io/badge/SQL%20-Server_2022-blueviolet?style=for-the-badge&logo=microsoft)](https://www.microsoft.com/en-us/sql-server)
[![Purpose](https://img.shields.io/badge/Purpose-Student_Lab_Showcase-lightgrey?style=for-the-badge)]()
[![Status](https://img.shields.io/badge/Status-Learning_Ready-brightgreen?style=for-the-badge)]()

---

# SQL Server Lab (Single VM Edition)

---

## Overview
This project demonstrates how to deploy and configure a **SQL Server 2022 environment** using **Windows Server 2022** on a single virtual machine.  

It’s designed for **hands-on training and simulation**, covering **SQL Server installation, configuration, and database management** and demonstrating **core SQL management tasks**.

---

## Key Components
| Component | Role | Description |
|------------|------|-------------|
| **VM01** | Primary Server | Windows Server 2022 with SQL Server 2022 installed |
| **SQL Server 2022** | Database Engine | The main SQL Server instance for database operations |
| **EmployeeDB Database** | Application Database | The database used to store employee information |

---

## Learning Objectives
- Learn to **install and configure SQL Server 2022** on a Windows Server VM  
- Understand how to create and manage databases and tables in SQL Server  
- Learn how to use **SQL Server Management Studio (SSMS)** for SQL operations  
- Understand the importance of **data querying and filtering** for real-world applications  

---

## Core Lab Setup
| Component | Purpose | Notes |
|------------|----------|-------|
| **VM01** | SQL Server Host | Windows Server 2022 with SQL Server 2022 installed locally |
| **EmployeeDB Database** | Application DB | Database used to store employee data |
| **SQL Server Management Studio (SSMS)** | Database Management | Installed on VM01 for local access to the SQL Server instance |

---

## Key SQL Queries and Actions
| Query/Action | Purpose | Result |
|--------------|---------|--------|
| **CREATE DATABASE EmployeeDB** | Create a new database | Creates the `EmployeeDB` database |
| **CREATE TABLE Employees** | Define the table structure | `Employees` table created within the database |
| **INSERT INTO Employees** | Populate sample data | Sample data inserted into the `Employees` table |
| **SELECT * FROM Employees** | Query data | Returns all data from the `Employees` table |
| **UPDATE Employees SET Status = 'Inactive' WHERE EmployeeID = 100** | Update data | Changes the status of a specific employee |
| **DELETE FROM Employees WHERE EmployeeID = 101** | Delete data | Removes a specific record from the table |

---

## Technical Highlights
- Installed and configured **SQL Server 2022** on **Windows Server 2022**  
- Created the `EmployeeDB` database for storing employee information  
- Populated `Employees` table with sample data for testing queries  
- Executed SQL commands using **SQL Server Management Studio (SSMS)** for querying, updating, and deleting data  
- Demonstrated the process of querying and filtering data using **SQL SELECT statements**

---

## Validation Tasks
☑ SQL Server installed and configured successfully on VM01  
☑ EmployeeDB database created in SQL Server  
☑ Employees table created and populated with sample data  
☑ Basic SQL queries executed and data verified  
☑ Data manipulation operations (INSERT, UPDATE, DELETE) tested successfully  

---

## Screenshots
| Image | Description |
|--------|-------------|
| SCREENSHOT-HERE | Windows Server 2022 VM with SQL Server 2022 installed |
| SCREENSHOT-HERE | SQL Server Management Studio (SSMS) interface |
| SCREENSHOT-HERE | EmployeeDB database created in SSMS |
| SCREENSHOT-HERE | Employees table schema definition in SSMS |
| SCREENSHOT-HERE | Running SELECT query to fetch data from Employees |
| SCREENSHOT-HERE | Sample data inserted into Employees table |
| SCREENSHOT-HERE | Executing UPDATE query to change employee status |
| SCREENSHOT-HERE | Deleting a record from the Employees table |
| SCREENSHOT-HERE | Final validation of the data and table in SSMS |

---

## Resource Allocation
| VM | OS | vCPU | RAM | Disk | Role |
|----|----|------|-----|------|------|
| **VM01** | Windows Server 2022 | 2 | 4GB | 40GB | SQL Server Host |

---

## Estimated Cost (if applicable)
| Resource | Type | Approx. Cost/hr |
|-----------|------|-----------------|
| **VM01** | B2s VM | $0 |
| **SQL Server 2022** | Standard | $0 |
| **Total** |  | **$0/hr** |

---

## Results
☑ SQL Server installed and configured successfully  
☑ EmployeeDB database and Employees table created and populated  
☑ Basic SQL queries validated (SELECT, UPDATE, DELETE)  
☑ Data manipulation operations successfully executed  
☑ Firewall access verified for local communication  

---

## Summary
A **SQL Server setup lab** built using **Windows Server 2022** and **SQL Server 2022**, designed to demonstrate **SQL Server installation, database creation, and data manipulation**.  

Showcases **SQL querying and data management**—ideal for **students and IT professionals** interested in learning database management and SQL Server operations.
