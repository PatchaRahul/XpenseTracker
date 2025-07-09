#  Expense Tracker App

A simple, interactive, and user-friendly web application that helps users track their daily expenses by category, date, and amount. It provides an organized way to manage spending habits with live updates and total calculations.

---

##  Overview

The **Expense Tracker App** allows users to:

- Record new expenses with specific categories
- View all added expenses in a tabular format
- Automatically calculate the total amount spent
- Delete individual expense entries

It is built entirely using **HTML**, **CSS**, and **JavaScript** with no external dependencies or frameworks, ensuring it is lightweight and easy to deploy.

---

##  Features

-  Categorize expenses (e.g., Rent, Transport, Food & Beverage)
-  Input amount and date of expense
-  Display all expenses in a table format
-  Auto-update total expenses on each entry or deletion
-  Delete any entry instantly
-  Responsive design for desktop and mobile

---

##  Why Use This App

- Track daily/monthly spending habits
- Stay within budget and monitor savings
- Use it offline without internet dependency
- Ideal for students, freelancers, or individuals managing basic finances

---

##  Technologies Used

| Tech       | Purpose              |
|------------|----------------------|
| HTML5      | Structure of the app |
| CSS3       | Styling and layout   |
| JavaScript | Dynamic functionality|

---

##  Core Functions

### 1. `Add Expense`
- Takes **category**, **amount**, and **date**
- Validates input
- Adds to internal list (`expenses[]`)
- Appends a row in the table
- Updates total amount

### 2. `Delete Expense`
- Removes the selected row
- Updates the `expenses[]` array
- Recalculates the total

### 3. `Live Total Display`
- Shows current total spending in the table footer

---

