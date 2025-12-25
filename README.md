# Dot-NET-web-project

## Prerequisites
.NET SDK (download from microsoft.com/net/download)
Git (download from git-scm.com)
A GitHub account

## 1. Create a new .NET web project
    PS F:\demo-web-app> dotnet new mvc
The template "ASP.NET Core Web App (Model-View-Controller)" was created successfully.
This template contains technologies from parties other than Microsoft, see https://aka.ms/aspnetcore/8.0-third-party-notices for details.

Processing post-creation actions...
Restoring F:\demo-web-app\demo-web-app.csproj:
  Determining projects to restore...
  Restored F:\demo-web-app\demo-web-app.csproj (in 57 ms).
Restore succeeded.


    PS F:\demo-web-app> dir


Directory: F:\demo-web-app


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        25/12/2025     21:23                Controllers
d-----        25/12/2025     21:23                Models
d-----        25/12/2025     21:23                obj
d-----        25/12/2025     21:23                Properties
d-----        25/12/2025     21:23                Views
d-----        25/12/2025     21:23                wwwroot
-a----        25/12/2025     21:23            127 appsettings.Development.json
-a----        25/12/2025     21:23            151 appsettings.json
-a----        25/12/2025     21:23            268 demo-web-app.csproj
-a----        25/12/2025     21:23            670 Program.cs

## 2. Initiate Git and push to Github or Azure Repo

    PS F:\demo-web-app> git init
Initialized empty Git repository in F:/demo-web-app/.git/
  PS F:\demo-web-app> dotnet new gitignore
The template "dotnet gitignore file" was created successfully.

PS F:\demo-web-app> git add .
PS F:\demo-web-app> git status
PS F:\demo-web-app> git commit -m "created Dotnet webproject"
PS F:\demo-web-app> git remote add origin https://cloudbyvenkat@dev.azure.com/cloudbyvenkat/DotNetWebApp/_git/demo-web-app
PS F:\demo-web-app> git branch -M main
PS F:\demo-web-app> git push -u origin main

This is .NET web project zero to hero and deploy in azure webapp using Azure DevOps
