# 💰 Payroll — Excel Practice Project

## 📌 Overview

This project is part of my Excel learning journey.

I created a payroll spreadsheet to practice the fundamentals of Microsoft Excel using a real-world business scenario: calculating employee wages based on hourly rates and hours worked.

This project is based on the payroll exercise from the **Microsoft Excel Tutorial for Beginners – Full Course** by freeCodeCamp.

🎥 **Course:** [Microsoft Excel Tutorial for Beginners – Full Course](https://www.youtube.com/watch?v=Vl0H-qTclOg)

---

## 🎯 Project Objective

The objective of this project is to build a simple payroll system that can be used to:

* Record employee information
* Record hourly wages
* Record hours worked
* Calculate employee pay
* Calculate total hours worked
* Calculate total payroll
* Find the minimum and maximum pay
* Calculate average pay
* Extend the payroll to multiple weeks
* Calculate overtime hours and overtime pay

---

## 📊 Dataset

The spreadsheet contains employee payroll information such as:

| Column       | Description                 |
| ------------ | --------------------------- |
| Last Name    | Employee's last name        |
| First Name   | Employee's first name       |
| Hourly Wage  | Employee's hourly pay rate  |
| Date         | Beginning of the pay period |
| Hours Worked | Number of hours worked      |
| Pay          | Calculated employee pay     |

The employee data used in this exercise is fictional and is intended only for learning purposes.

---

## 🧮 Excel Skills Practiced

### Basic Calculations

I practiced using Excel formulas to calculate employee pay.

The basic calculation is:

```text
Pay = Hourly Wage × Hours Worked
```

For example:

```excel
=C4*D4
```

---

### SUM

I used `SUM` to calculate totals such as:

* Total hours worked
* Total wages paid

Example:

```excel
=SUM(D4:D20)
```

---

### MAX

I used `MAX` to identify the highest employee pay.

```excel
=MAX(E4:E20)
```

---

### MIN

I used `MIN` to identify the lowest employee pay.

```excel
=MIN(E4:E20)
```

---

### AVERAGE

I used `AVERAGE` to calculate the average employee pay.

```excel
=AVERAGE(E4:E20)
```

---

## 💵 Currency Formatting

I practiced formatting numerical values as currency.

Currency formatting was applied to:

* Hourly wages
* Regular pay
* Overtime pay
* Total payroll

This makes the spreadsheet easier to read and more appropriate for a payroll context.

---

## 🔄 Fill Down

One important Excel skill practiced in this project was copying a formula to multiple rows.

Instead of manually writing the same formula for every employee, I created the formula once and filled it down.

For example:

```excel
=C4*D4
```

The formula can then be filled down so Excel automatically adjusts the row references:

```text
=C4*D4
=C5*D5
=C6*D6
...
```

This was useful for calculating the pay of multiple employees efficiently.

---

## 📈 Payroll Summary

The spreadsheet includes summary calculations such as:

* Maximum pay
* Minimum pay
* Average pay
* Total hours worked
* Total wages paid

These calculations provide a quick overview of the payroll.

---

## ⏱️ Multiple Weeks & Overtime

The project was later extended to cover multiple weeks.

The extended version introduces:

* Multiple weekly periods
* Weekly hours worked
* Overtime hours
* Regular pay
* Overtime pay
* Total weekly pay

This allowed me to practice working with a larger and more complex spreadsheet.

---

## 🎨 Formatting & Organization

I also practiced improving the readability of the spreadsheet by:

* Adjusting column widths
* Formatting currency
* Using cell colors
* Organizing related columns
* Formatting dates
* Separating different types of information visually

---

## 🧠 What I Learned

Through this project, I practiced several important Excel fundamentals:

* How Excel cells are organized
* How to reference cells in formulas
* Basic arithmetic formulas
* Using `SUM`
* Using `MAX`
* Using `MIN`
* Using `AVERAGE`
* Formatting numbers as currency
* Filling formulas down
* Adjusting column widths
* Organizing a large spreadsheet
* Working with dates
* Calculating employee wages
* Working with multiple pay periods
* Understanding overtime calculations

---

## ⚠️ Challenges

One of the challenges I encountered was understanding how cell references change when a formula is copied to another row or column.

For example:

```excel
=C4*D4
```

When filled down, Excel automatically changes the references:

```excel
=C5*D5
=C6*D6
=C7*D7
```

Understanding this behavior helped me better understand **relative cell references**.

---

## 💡 Personal Practice

After following the tutorial, I am using this project to practice the concepts independently.

My goal is not only to reproduce the tutorial but also to understand why each formula works and eventually modify the spreadsheet to create my own payroll scenarios.

Possible future improvements include:

* Employee IDs
* Department information
* Different overtime rates
* Overtime thresholds
* Tax deductions
* Net salary
* Employee summary reports
* Pivot Tables
* Payroll dashboard

---

## 📁 Files

```text
payroll/
│
├── README.md
│
└── payroll.xlsx
```

---

## 📚 Learning Resource
## 🚀 Learning Progress

This project represents one of the first steps in my Excel learning journey.

Next topics I plan to practice include:

* More Excel functions
* Data cleaning
* Lookup functions
* Pivot Tables
* Charts
* Dashboards
* Real-world data analysis projects

---

## 📌 Note

This repository is a personal learning portfolio. The data used in the payroll exercise is fictional and does not represent real employees or real payroll information.


excel-learning-portfolio
│
├── README.md
│
└── 01-excel-basics
    ├── README.md
    └── exercises
        └── your-first-exercise.xlsx
