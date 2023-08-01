# WebAuth
Starter kit to begin building your app with user register, login and other services using `ASP .Net Core 7` Service to enable load testing on different types of network calls.

## Instructions

Run below steps to start from the beginning

```
// Install code generator
dotnet tool install -g dotnet-aspnet-codegenerator

// Create new App
dotnet new webapp --auth Individual -o WebAuth

// Add relevant packages
dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore
dotnet add package Microsoft.AspNetCore.Identity.UI
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools

// Genearate relevant pages
dotnet aspnet-codegenerator identity -dc WebAuth.Data.ApplicationDbContext --files "Account.Register;Account.Login;Account.Logout;Account.RegisterConfirmation" --useSqLite

```

### Details
For more details, please refer [here](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-7.0&tabs=netcore-cli)

```
### License
Free for non-commercial use, but please read ![LICENSE](LICENSE) for commercial use, other(s) and support.

### Customizations/ Support
<a href="https://sites.google.com/view/garden-systems" target="_blank"><img src="Garden-Systems-logos_transparent.svg" style="width:100px;height:100px"></a>

### Donations
If you like using this repository and like to donate, please visit the below link. This work is made possible with donations like yours. PM for customizations and implementations .

<a href="https://www.buymeacoffee.com/ragavendra"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a pop&emoji=🥃&slug=ragavendra&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" /></a>

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ZKRHDCLG22EJA)
