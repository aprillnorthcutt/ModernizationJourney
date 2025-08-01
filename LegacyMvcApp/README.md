# 🗂️ Task Management System (Legacy to Modern MVC Project)

## 📌 Overview

This project demonstrates the transformation of a legacy ASP.NET MVC 5 application into a modern ASP.NET Core MVC architecture using microservices. It serves as a portfolio piece to showcase skills in software modernization, API development, and microservice architecture.

---

## 🏗️ Legacy App Features (ASP.NET MVC 5)

- User registration and login
- Role-based access (Admin/User)
- Task creation, editing, deletion
- Assign tasks to users
- Basic reporting (tasks by user/status)
- Razor views with Bootstrap styling
- Entity Framework 6 for data access

---

## 🚀 Modernization Goals

- Upgrade to ASP.NET Core MVC (.NET 8)
- Implement microservices:
  - `AuthService`: Authentication and user management
  - `OrderService`: Task management and assignment
  - `ReportingService`: Task analytics and reporting
- Use Entity Framework Core
- Add RESTful APIs
- Optional: Docker support and cloud deployment
---

## 🧱 Tech Stack

### Legacy Version
- ASP.NET MVC 5
- Entity Framework 6
- SQL Server LocalDB
- Razor Views
- Bootstrap

### Modern Version
- ASP.NET Core MVC (.NET 8)
- Entity Framework Core
- RESTful APIs
- Microservices architecture
- Swagger (API documentation)
- Docker (optional)
- Azure or AWS (optional)

---

## 📁 Project Structure

/LegacyApp /Controllers /Models /Views /Scripts /Content

/ModernApp /AuthService /OrderService /ReportingService


---

## 📊 Reporting Features

- Tasks by completion status
- Tasks by assigned user
- Task counts and trends

---

## 🧪 How to Run (Legacy Version)

1. Clone the repo
2. Open in Visual Studio
3. Restore NuGet packages
4. Update connection string in `Web.config`
5. Run the app

---

## 📦 Future Enhancements

- Add unit and integration tests
- Add JWT-based authentication
- Add frontend SPA (React or Vue)
- Deploy microservices with Docker

---

## 📸 Screenshots

_Add screenshots of legacy and modern UI here_

---

## 📚 License

MIT License

---

## 🙋‍♀️ Author

**April Northcutt**  
[LinkedIn](#) • Portfolio • Email
