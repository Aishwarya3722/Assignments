# Programming Assignments Repository

A collection of academic and practice assignments developed using **C# (.NET)** and **SQL**. The repository covers core programming concepts, object-oriented design, exception handling, collections, LINQ, database querying, and basic application development.

## Repository Overview

The assignments are organized into separate folders, with each folder focusing on a specific concept or problem statement.

### SQL Assignments

* User management database with validation constraints and analytical queries
* Customer, product, and order management using different join operations
* Sales reporting and aggregation queries
* Shipment tracking and delivery analysis

### Object-Oriented Programming (C#)

* Drone surveillance management system
* Shopping application with customers, agents, orders, and payments
* Employee reporting system using inheritance and polymorphism
* Discount calculation system using the Strategy Design Pattern

### Exception Handling

* Exam form submission validation using custom exceptions
* Cab booking system with location and GPS-related exception handling

### Collections, LINQ, and Sorting

* Playlist management application
* Age-based sorting using `IComparable`
* Employee sorting using custom `IComparer` implementations
* Anagram grouping and collection-based exercises

### Utility Programs

* Password encoding and decoding
* Password strength analysis
* Age calculation from date of birth
* Hour-to-day conversion
* Number guessing challenge
* FizzBuzz variation with prime number handling

### Notes and Documentation

* Collection Framework concepts
* Object methods (`Equals`, `ToString`, `GetHashCode`)
* SDLC, ORM, EF Core, HTML, CSS, ER modeling, and database design fundamentals

### Entity Framework Core Project

* Expense sharing application built using EF Core
* SQLite-based implementation for easy setup and execution

---

## Running the C# Programs

Most folders contain a standalone `Program.cs` file.

### Using .NET CLI

```bash
dotnet new console -n temp -o . --force
dotnet run
```

Alternatively, individual assignments can be converted into separate SDK-style projects if required.

### Online Execution

You can also run the programs using online C# environments such as .NET Fiddle by copying the contents of the corresponding `Program.cs` file.

---

## Running the SQL Scripts

The SQL scripts can be executed in:

* SQL Server Management Studio (SSMS)
* Azure Data Studio
* DBeaver
* Any compatible SQL client

Each script includes:

* Table creation statements
* Sample data insertion
* Required queries and outputs

Most scripts are written using SQL Server syntax and may require minor adjustments for MySQL or PostgreSQL.

---

## EF Core Expense Sharing Application

To run the EF Core project:

```bash
cd 25_expense_sharing_efcore
dotnet restore
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run
```

The application uses SQLite as its default database, making setup simple without requiring a dedicated database server.

---

## Learning Areas Covered

* Object-Oriented Programming
* Inheritance and Polymorphism
* Encapsulation and Abstraction
* Exception Handling
* Design Patterns
* Collections Framework
* LINQ
* SQL Queries and Joins
* Database Design
* Entity Framework Core
* Basic Application Development

---

## Author

**Priyam Kundu**
