📊 Excel Formula Examples – Real World Scenarios

This repository contains basic to intermediate Excel formula examples with real-world use cases, formulas, and outputs.
It is useful for students, freshers, data analysts, and interview preparation.

🧩 1. IF Function – Salary Eligibility
📌 Scenario

Check if an employee is eligible for a lottery when salary > 50,000

📊 Data
Name	Salary
Prajwal	65000
Rahul	42000
🧮 Formula

=IF(B2>50000,"Eligible for Lottery","Not Eligible")

✅ Output

Prajwal → Eligible for Lottery

Rahul → Not Eligible

🧩 2. CONCAT – Create Message
📌 Scenario

Create a congratulation message for eligible employees

🧮 Formula

="Congratulations "&A2&", you are getting a lottery"

✅ Output

Congratulations Prajwal, you are getting a lottery

🧩 3. IF + CONCAT – Combined Logic
📌 Scenario

Send message only if salary > 50,000

🧮 Formula

=IF(B2>50000,
"Congratulations "&A2&", you are getting a lottery",
"")

✅ Output

Message appears only for eligible employees

🧩 4. COUNTIF – Count High Salary Employees
📌 Scenario

Count employees whose salary is greater than 50,000

🧮 Formula

=COUNTIF(B2:B10,">50000")

✅ Output

Returns total count of high-salary employees

🧩 5. SUMIF – Department-wise Salary
📌 Scenario

Calculate total salary of IT department

🧮 Formula

=SUMIF(C2:C10,"IT",B2:B10)

🧩 6. VLOOKUP – Fetch Salary Using ID
📌 Scenario

Get employee salary using Employee ID

🧮 Formula

=VLOOKUP(E2,A2:C10,3,FALSE)

🧩 7. COUNTBLANK – Data Cleaning
📌 Scenario

Find missing values in a column

🧮 Formula

=COUNTBLANK(A2:A20)

🧩 8. TEXT – Format Salary
📌 Scenario

Display salary in Indian currency format

🧮 Formula

=TEXT(B2,"₹#,##0")

✅ Output

₹65,000

🎯 Interview One-Liners

IF → Apply business logic

CONCAT → Create dynamic messages

COUNTIF → Count based on condition

SUMIF → Conditional totals

VLOOKUP → Fetch data from tables
