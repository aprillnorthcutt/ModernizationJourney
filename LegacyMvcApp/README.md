🗂️ Project Structure (Legacy Monolith)
/Controllers
    AccountController.cs
    TaskController.cs
    ReportController.cs

/Models
    User.cs
    TaskItem.cs

/Views
    /Account
    /Task
    /Report

/App_Start
    RouteConfig.cs

/Content
    Bootstrap, CSS

/Scripts
    jQuery, AJAX

    
🛠️ Tech Stack
ASP.NET MVC 5

Entity Framework 6

SQL Server LocalDB

Razor Views

Bootstrap for UI

Web API 2 (optional) for AJAX or future API calls


🔄 Future Microservice Mapping

Legacy           Module	Microservice	  Notes
AccountController	AuthService	          Move to ASP.NET Core Identity\n
TaskController	  OrderService	        Tasks = Orders
ReportController	ReportingService	    Use APIs to aggregate task data
