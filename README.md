# 💰 ExpenseIt – WPF Desktop Application

This repository contains a WPF desktop application named **ExpenseIt**, created by following and extending the Microsoft Learn tutorial **“Walkthrough: My first WPF desktop application”**.

🔗 Official tutorial link:
[https://learn.microsoft.com/en-us/dotnet/desktop/wpf/get-started/walkthrough-my-first-wpf-desktop-application](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/get-started/walkthrough-my-first-wpf-desktop-application)

---

## 📌 About the Project

**ExpenseIt** is a sample **WPF (Windows Presentation Foundation)** application that demonstrates how to build a simple expense tracking UI using XAML and C#.

The project focuses on:

* WPF application structure
* Navigation between multiple pages
* XAML-based UI design
* Code-behind logic (`.xaml.cs`)
* Using images and resources in WPF
* Event handling and page interaction

---

## 🧩 Application Pages

The application consists of multiple pages:

* **ExpenseItHome** – The main/home page of the application
* **ExpenseReportPage** – Displays expense report details
* **MainWindow** – Hosts and manages navigation between pages

---

## 🛠 Technologies Used

* **.NET (WPF)**
* **C#**
* **XAML**
* **Visual Studio**

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/USERNAME/REPOSITORY_NAME.git
   ```

2. Open the solution in **Visual Studio**

3. Build and run the project using the **Run (▶️)** button

---

## 📂 Project Structure

```text
├── App.xaml
├── App.xaml.cs
├── MainWindow.xaml
├── AssemblyInfo.cs
├── ExpenseItHome.xaml
├── ExpenseItHome.xaml.cs
├── ExpenseReportPage.xaml
├── ExpenseReportPage.xaml.cs
├── Images/
│   └── (application images)
├── Properties/
└── README.md
```

* **ExpenseItHome.xaml** – Home page UI
* **ExpenseReportPage.xaml** – Expense report UI
* **MainWindow.xaml** – Main window and navigation container
* **Images/** – Image resources used in the application

---

## 🎯 Purpose

The purpose of this project is to:

* Learn the fundamentals of WPF
* Understand page-based navigation in WPF
* Practice XAML layouts and resource usage
* Serve as a foundation for more advanced WPF applications

---

## 📖 Reference

This project is based on the official Microsoft documentation:

* Microsoft Learn – Walkthrough: My First WPF Desktop Application

---

## 📌 Notes

* This project is created **for learning purposes**
* The architecture uses **code-behind** as in the tutorial
* It can be improved by applying the **MVVM pattern**, data binding, and validation
