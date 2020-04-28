# NETCore-CommandAPI
  A small utility to remember dotnet commands based on book "The Complete ASP.NET Core Web API'
  
  After reading some reviews and learned about problems with setting up the project with PostgreSQL, decided to do it myself.
  
   - Implemented .NET Core API CRUD
   - Used PostgreSql and DBWeaver
   - Added XUnit Test but didn't write any 
   - Implemented UserSecrets (to keep username/password for database hidden)
   
   Notes: If you find a problem with creating migrations and database using EF code first, you probably didn't save  
   connection strings into appsettings.json or in this particular case appsettings.Development.json
   After successfull migration and database creation, for some reason it's not visible in DBWeaver automatically(feature?)
   You need to connect manually to particular database (CommandsAPI) from start->new connnection-choose postgre provider and 
   database name, username and password.
