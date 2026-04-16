# ExpenseManagement

- CREATE DATABASE ExpensesDb;
- GO

- USE ExpensesDb;
- GO

- CREATE TABLE Transactions (
    - Id INT PRIMARY KEY IDENTITY(1,1),
    - Type NVARCHAR(50),
    - Amount DECIMAL(18,2),
    - Category NVARCHAR(100),
    - CreatedAt DATETIME,
    - UpdatedAt DATETIME
- );