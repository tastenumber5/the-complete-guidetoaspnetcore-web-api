# the-complete-guidetoaspnetcore-web-api" 
https://www.youtube.com/watch?v=HCqHBFJKe44&list=PL2Q8rFbm-4ru6hExDbfrN3QZNKI7n3p0N
video 04 title Default ASP.NET Core Web API Project Files
>SOLUTION EXPLORER
>Connected Services + Add Service Dependencies | + Add Service References(OpenAPI, gRPC) | OtherServices
  ??? what is OPENAPI?
  >Consume web services which conform to the OpenAPI Specification
  ??? what is gRPC?
  >Consume and produce web services which conform to gRPC open source universal RPC Framework
>DEPENDENCIES +Add NuGet packages are CUSTOM | Frameworks from Microsoft Default 
>PROPERTIES
  !!!launchSettings.json <Create custom profiles eg development / production / new configuration>
>CONTROLLERS <this is where you add your custom controller >
  !!!WeatherForcastControllers
>appsettings.json >store connect streams
>Program.cs is the entry point
video 05. Testing Asp.Net Core Web APIs with Swagger and Postman
video 07  Building Your First Asp.Net Core API - Getting Start
  What You Will Learn
  .Data Models
  .Entity Framework Core Database Context
  .Entity Framework Core Migrations and Seeding Your Database
  Working with Data
  .Adding Data [HttpPpst]
  .Getting Data [HttpGet]
  .Updating Data [HttpPut]
08. Adding a Model to an Asp.Net Core Web API
    Entity Framework uses EDM(Entity Data Model)
    EDM is a model that decribes the entities and the relationships between them
    Models are just c# classess
09. Adding Your Entity Framework Core DbContext File to Web API
    Entity Framework Database Context - The most important EF class
    This is a bridges between Entity classes(c# classes) and the database table (sql).
  >Add Microsoft.EntityFrameworkCore
  >Add Microsoft.EntityFrameworkCore.Design
  1.create a new class > rename AppDbContext
  2.ctor >   public AppDbContext(DbContextOptions<AppDbContext> options) : base(options)
  3. public DbSet<Books> Books {get; set;} <define table names for c#>
  4. appsettings.json >  
  "ConnectionStrings": {
     "DefaultConnectionString": "fake-db-connection"
  5.Startup.cs file is missing
  Solution: ASP.NET Core 6 - How to deal with the missing Startup.cs file 
  https://www.youtube.com/watch?v=vhNhcuht0J0
  Author Tony Spencer
  

  
  
 
