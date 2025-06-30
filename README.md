# 💼 Employee Payroll System (Java OOPs Project)

This is a simple **Employee Payroll System** developed in **Java** using core **Object-Oriented Programming** concepts like **abstraction**, **inheritance**, and **polymorphism**.

---

## ✨ Features

- ➕ Add full-time and part-time employees
- 💰 Automatically calculate salaries using dynamic method dispatch
- ❌ Remove employees by their ID
- 📋 Display employee details including calculated salary

---

## 🧱 Class Structure

### 🧑‍💼 `Employee` *(Abstract Class)*
- Common attributes:
  - 🆔 `id`
  - 🧾 `name`
- 🧠 Abstract method: `calculateSalary()`

### 🏢 `FullTimeEmployee` *(Extends Employee)*
- 💵 `monthlySalary`
- ✔️ Implements `calculateSalary()` to return fixed monthly pay

### 🕒 `PartTimeEmployee` *(Extends Employee)*
- 🕰️ `hoursWorked`
- 💸 `hourlyRate`
- ✔️ Implements `calculateSalary()` as `hoursWorked * hourlyRate`

### 📊 `PayRollSystem`
- 📁 Maintains a list of employees
- 🔧 Functions:
  - `addEmployee()`
  - `removeEmployee(id)`
  - `displayEmployees()`

### ▶️ `main` *(Driver Class)*
- Creates employee objects
- Adds/removes employees to/from the payroll
- Displays current employee data

------------------------------------------------
------------------------------------------------
🧪 Sample Output

Initial Employee Details: 
Employee [name=subham, id=1, salary=50000.0]
Employee [name=banti, id=2, salary=16000.0]
Removing Employees
Remaining Employees Details: 
Employee [name=subham, id=1, salary=50000.0]

-------------------------------------------------
🧠 Concepts Used
🔍 Abstraction & Inheritance

🔁 Polymorphism via method overriding

🔒 Encapsulation of employee data

📚 Working with Java Collections (ArrayList)

