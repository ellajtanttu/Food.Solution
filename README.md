# _Pierre's Treat Tracker_

#### By _**Ella Tanttu**_

#### _An mvc application that allows the user to track treat and flavor relationships using authentication with identity_

## Technologies Used

* _HTML_
* _C#_
* _.Net5_
* _ASP.Net Core MVC_
* _ASP.Net Identity_
* _Razor View Engine_
* _CSS_
* _Markdown_
* _Bootstrap_
* _HtmlHelper_
* _SQL_
* _MySQL_
* _EntityFrameworkCore_

## Description

<img src="Treat/wwwroot/img/TBD.png" height="275px">
Application that allows baker entrepreneur Pierre owner to keep track of treats and flavors in his bakery. Practice with many to many relationships and authentication with identity. Add, delete, edit, and otherwise control both treats and flavors, and which are connected to which.

## Setup/Installation Requirements

### **Package Installations:**
1. _Download .NET 5 [here](https://dotnet.microsoft.com/en-us/download/dotnet/5.0)_
2. _You can find the Treat.Solution github repository [here](https://github.com/ellajtanttu/Treat.Solution)_
3. _Click the green code button, and copy the https link_
4. _In your preferred git terminal navigate to the directory you would like to store the project_
5. _Enter: "git clone" followed by the copied https link_
6. _Now that the repository is cloned to your computer, right click on the folder and click open with vs code_
7. _Once in the project, navigate to the `Treat` directory within the terminal_
8. _Add the following packages in terminal:_
   - `dotnet add package Microsoft.EntityFrameworkCore -v 5.0.0`
   - `dotnet add package Pomelo.EntityFrameworkCore.MySql -v 5.0.0-alpha.2`
   - `dotnet add package Microsoft.EntityFrameworkCore.Proxies -v 5.0.0`
   - `dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore -v 5.0.0`
   - `dotnet tool install --global dotnet-ef --version 3.0.0`

### **Database Setup & Running the Application:**
1. _In terminal, navigate to the `Treat` directory_
2. _Type `dotnet restore` to install dependencies_
3. _Type `dotnet build` to build project_
4. _In order to initalize a database you will need to create an appsettings.json file that looks like this*_
```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database={YOUR DATABASE NAME HERE};uid={YOUR USER ID HERE};pwd={YOUR PASSWORD HERE};"
  }
}
```
   _*NOTE: change {YOUR X} with corresponding information_

5. _Once you have the appsettings.json file— to create a database type: `dotnet ef add initial`_
6. _To update the database in MySQL type: `dotnet ef database update`_
7. _Initialize localhost:3306 in MySQL Workbench (download [here](https://dev.mysql.com/downloads/workbench/))_
8. _At this point you will now be able to view the project by typing `dotnet run` in the terminal_

## Known Bugs

No known issues

## License

_MIT Copyright (c) 2021 Ella Tanttu_
_https://opensource.org/licenses/MIT_

## Contact Information

_Ella Tanttu ellajtanttu@gmail.com_