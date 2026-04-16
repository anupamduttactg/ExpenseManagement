# 📘 API Development using EF Core (DB First Approach)

'This guide walks through building an ASP.NET Core Web API using Entity Framework Core (Database-First approach).

# ✅ Step 1: Create Database (SQL Server)

## Run the following SQL in SQL Server Management Studio (SSMS):
'CREATE DATABASE ExpensesDb;
GO

USE ExpensesDb;
GO

CREATE TABLE Transactions (
    Id INT PRIMARY KEY IDENTITY(1,1),
    Type NVARCHAR(50),
    Amount DECIMAL(18,2),
    Category NVARCHAR(100),
    CreatedAt DATETIME,
    UpdatedAt DATETIME
);'