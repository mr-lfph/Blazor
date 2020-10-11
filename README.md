# Blazor

```
dotnet new blazorserver -o BlazorApp --no-https 
cd BlazorApp
```
### What do these commands mean?
* The __dotnet__ new blazorserver command creates a new Blazor Server app for you.
* The __-o__ parameter creates a directory named BlazorApp where your app is stored and populates it with the required files.
* The __--no-https__ flag specifies not to enable HTTPS.
* The __command cd__ BlazorApp changes your directory to the one you just created.

### What files were created?
Several files were created in the BlazorApp directory, to give you a simple Blazor app that is ready to run.

* **Program.cs** is the entry point for the app that starts the server.
* **Startup.cs** is where you configure the app services and middleware.
* **App.razor** is the root component for the app.
* The **BlazorApp/Pages** directory contains some example web pages for the app.
* **BlazorApp.csproj** defines the app project and its dependencies.

`dotnet new razorcomponent -n Todo -o Pages` 
Component should start with capital letter (Todo)





