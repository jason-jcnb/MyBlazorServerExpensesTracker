# MyBlazorServerExpensesTracker

Welcome to the **MyBlazorServerExpensesTracker** project! This repository contains the code for building a web-based **Expenses Tracker** using **Blazor Server**, **SQLite**, and **Syncfusion** components. The application allows users to track their expenses with an intuitive interface, manage categories, and keep track of their finances.


## Technologies Used

This project utilizes the following technologies:

- **.NET Blazor**: A framework for building interactive web applications with C#. The **Blazor Server** hosting model is used, meaning the application runs on the server and updates the UI in real-time via SignalR.
- **SQLite**: A lightweight, file-based database engine used to store and retrieve expense data.
- **Syncfusion Components**: A set of UI components that enhance the user experience with advanced controls such as charts, grids, and more.
- **Entity Framework Core (EF Core)**: An ORM (Object-Relational Mapping) library used to interact with the SQLite database, including migrations for database schema management.
- **C#**: The primary language used for logic and backend development.

## Features

- **Track Expenses**: Add and manage your daily, weekly, or monthly expenses.
- **Categorize Expenses**: Group expenses by categories such as food, transport, entertainment, etc.
- **Syncfusion UI Components**: Leverage Syncfusion’s powerful controls like Data Grids, Charts, and more to present data in an interactive way.
- **Real-time Updates**: Experience real-time UI updates through the Blazor Server hosting model.
- **SQLite Database**: Lightweight, fast, and portable database for storing all the data.
- **Service-based Architecture**: Services to handle the business logic and database operations, injected into Blazor components.

### Prerequisites

Before you can run the application, ensure you have the following installed on your machine:

- [.NET 6.0 SDK or later](https://dotnet.microsoft.com/download)
- Visual Studio 2022 or later with the **Blazor** and **SQLite** extensions
- [Syncfusion Blazor components](https://www.syncfusion.com/products/blazor)

### Steps to Install

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/MyBlazorServerExpenses.git
   cd MyBlazorServerExpenses
   Open the project in Visual Studio Code or Visual Studio.
   dotnet restore
   dotnet run
