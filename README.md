# 🍽️ Digital Table Management System (DTMS)

A web application for restaurants to manage **tables, reservations, walk-ins, and waitlists** in real time.  
The goal is to reduce wait times, improve table turnover, and give managers and staff an easy tool to organize seating.

---

## ✨ Features (MVP)
- Table layout & status (free / occupied / cleaning / payment)
- Reservation management (create, edit, cancel, no-shows)
- Walk-in handling with dynamic waitlist
- Real-time dashboard of table occupancy
- Role-based access (Host, Staff, Manager)

---

## 🛠 Tech Stack
- **Backend:** ASP.NET Core (C#)
- **Frontend:** Razor Pages, HTML, CSS, JavaScript
- **Database:** SQL Server (relational model)
- **Testing:** xUnit (unit & integration tests)
- **CI/CD:** GitHub Actions

---

## 📂 Repository Structure

src/ # Source code
DTMS.Web/ # Main web application
DTMS.Tests/ # Unit & integration tests

docs/ # Documentation (requirements, use cases, backlog, architecture)

.github/workflows/ # GitHub Actions (CI/CD pipelines)

DTMS.sln # Visual Studio solution file
README.md # Project overview
LICENSE # Open-source license

---

## 🚀 Getting Started

### Prerequisites
- .NET 8 SDK (or latest stable)
- Visual Studio 2022 / VS Code
- SQL Server (local or Docker)

### Setup
```bash
# Build the solution
dotnet build

# Run the web app
dotnet run --project src/DTMS.Web

# Run tests
dotnet test