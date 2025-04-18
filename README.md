<h1 align="center">
  <img src="https://img.icons8.com/fluency/96/money.png" width="50" />
  Expenscape API
</h1>

<p align="center">
  🌐 A modern .NET Web API for tracking personal expenses, built with <strong>ASP.NET Core</strong> and <strong>EF Core</strong>.  
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ASP.NET%20Core-8.0-blue?logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/EF%20Core-8.0-green?logo=database&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger-Enabled-brightgreen?logo=swagger&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey" />
</p>

---

## 📦 Features

- 🔐 JWT-based Authentication & Authorization
- 📊 Add, edit, and delete expenses and incomes
- 📁 Category management
- 📈 Monthly summaries and reports
- 🔍 Filtering by date and category
- 🧪 Unit testing with xUnit / NUnit
- 🌐 Swagger UI for exploring endpoints

---

## 🚀 Getting Started

### Prerequisites

- [.NET SDK 8.0+](https://dotnet.microsoft.com/en-us/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) or SQLite
- [Visual Studio / VS Code](https://code.visualstudio.com/)

### Setup

```bash
git clone https://github.com/yourusername/expenscape.git
cd expenscape
dotnet restore
dotnet ef database update
dotnet run
