# ClickSharp

## EF Basic Startup Migrations
dotnet ef migrations add FirstInit --startup-project ClickSharp --project ClickSharp.DataLayer -- --environment DEBUG </br>
dotnet ef database update --startup-project ClickSharp --project ClickSharp.DataLayer -- --environment DEBUG </br>