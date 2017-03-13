# ASPNETCore-customErrorPages
Code sample detailing how to create and use custom error pages in ASP.NET Core 1.0.
Article detailing the steps to take can be found [here](https://gooroo.io/GoorooThink/Article/17086/Creating-Custom-Error-Pages-in-ASPNET-core-10)

## This application consists of:

*   Sample pages using ASP.NET Core MVC
*   [Gulp](https://go.microsoft.com/fwlink/?LinkId=518007) and [Bower](https://go.microsoft.com/fwlink/?LinkId=518004) for managing client-side libraries
*   Theming using [Bootstrap](https://go.microsoft.com/fwlink/?LinkID=398939)

## Run & Deploy

restore the .NET core packages described in the `package.json`, install the npm and bower dependencies,and then update database with the migrations and run the project:

```bash
dotnet restore
npm install
bower install
dotnet ef database update
dotnet run

```

The `dotnet restore` command first restores the necessary packages required to run the application, 
the `dotnet run` command simultaneously re-compiles and runs the `kestrel-server`.

I would love to hear your [feedback](https://temilajumoke.com)
