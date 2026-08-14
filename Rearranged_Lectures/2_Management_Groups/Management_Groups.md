Software background is somewhat needed to understand the components and why they matter.

Layers of Software development:

### Presentation layer:

The user interface and user experience components of an application. This layer is responsible for displaying information to the user and capturing user input.

- Web Front Ends (hosted in web environments in Azure)
  - PHP
  - ASP.NET/ MVC
  - JavaScript front end frameworks (e.g., Express, React, Angular, Vue.js)
  - Python web frameworks (e.g., Django, Flask)
  - Java web frameworks (e.g., Spring, Struts)

### Business logic layer:

The core functionality of an application, which processes data and implements business rules.
The core functionality of an application, which processes data and implements business rules.

- Sample business logic components include:
  - Authentication and authorization
  - Data validation and processing
  - Workflow management
  - Integration with external services and APIs
- Business layers can talk to front ends directly or via Web APIs.

### Data access layer:

The layer responsible for interacting with the database or other data storage systems. You can think of these as SQL wrapper parts of the application.

### NOTE: Not Hosted But Connected to Azure via Web API:

Please note that the following are NOT hosted in Azure but can be connected to Azure services or Web APIs:

- Windows desktop applications (e.g., WPF, WinForms)
- Mobile applications (e.g., iOS, Android, Xamarin)
- Command-line applications (e.g., .NET Core, Python, Node.js)
