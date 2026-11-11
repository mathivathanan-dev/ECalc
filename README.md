# ECalc – Expense Calculator

## 1. Project Introduction
ECalc is a desktop-based Expense Calculator application developed using C# and Windows Presentation Foundation (WPF).

It helps users manage their daily expenses, store expense records, and view monthly, weekly, and yearly expense summaries.

## 2. Objective
- To manage daily expenses.
- To store expense details securely.
- To calculate total expenses.
- To view expense history.
- To provide individual user accounts.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| C# | Programming language |
| WPF | Desktop application UI |
| XAML | Designing application screens |
| .NET | Application framework |
| JSON | Data storage |
| System.Text.Json | JSON serialization |

## 4. Main Modules

### 1. Login Module
- User enters email and password.
- Validates login credentials.
- Provides access to the application.

### 2. Registration Module
- New users can create an account.
- Collects name, email and password.
- Saves user information in JSON.

### 3. Home / Expense Module
- Enter expense reason.
- Select expense date.
- Enter expense amount.
- Save expense details.
- Display expenses in DataGrid.

### 4. Dashboard Module
- Displays monthly expenses.
- Displays weekly expenses.
- Displays yearly expenses.
- Shows expense summary.

## 5. Generic Collections

A Generic Collection is a collection used to store and manage multiple objects of a particular data type.

Example:

`List<User>` – Stores user records.

`List<Expense>` – Stores expense records.

## 6. JSON Storage

JSON stands for JavaScript Object Notation.

It is a lightweight data format used to store and exchange information.

ECalc uses two JSON files:

- users.json – Stores registered user details.
- expenses.json – Stores expense details.

## 7. Important C# Concepts

### Class
A class is a blueprint for creating objects.

### Object
An object is an instance of a class.

### List<T>
List is a generic collection used to store multiple objects.

### LINQ
LINQ is used to query and filter data.

### Serialization
Converting C# objects into JSON format.

### Deserialization
Converting JSON data back into C# objects.

### Namespace
A namespace organizes related classes.

## 8. WPF Concepts

### WPF
Windows Presentation Foundation is a framework used to develop Windows desktop applications.

### XAML
XAML stands for Extensible Application Markup Language. It is used to design the user interface.

### Window
A Window represents an application screen.

### Grid
Grid arranges controls using rows and columns.

### StackPanel
StackPanel arranges controls vertically or horizontally.

### Border
Border provides background, border and rounded corners.

### TextBox
Used to enter text.

### PasswordBox
Used to enter passwords.

### Button
Used to perform actions.

### DataGrid
Used to display tabular data.

### Click Event
Executes code when a button is clicked.

## 9. Application Workflow

1. Start the application.
2. Register a new account.
3. Login using email and password.
4. Open the Home screen.
5. Add expense details.
6. Save expense records.
7. View expense history.
8. Open Dashboard.
9. View weekly, monthly and yearly summaries.

## 10. Conclusion

ECalc is a user-friendly expense management application developed using C# and WPF. It demonstrates object-oriented programming, generic collections, JSON storage, data handling and desktop UI development.
