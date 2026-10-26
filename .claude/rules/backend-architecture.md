## Backend Rules 
- Use Vertical Slicing Architecture
- Use Postgresql as the Database
- Use the DB First Approach
- Use the local instance of Postgresql for development and testing. The password for the local instance of Postgresql is `jelim209`
- Use DBUP for the Database Migrations
- User Dapper for the Data Access Layer
- Store the documents in Azure Blob Storage and use Azure Storage SDK for the access
- For the local development, use the Azure Storage Emulator for testing the Blob Storage access which listens at 'http://127.0.0.1:10000'
- ASP.NET Core Web APIs version .NET 10 
- ASP.NET APIs must have proper REST conventions
- Scalar for OpenAPI documentation
- Business logic belongs in Application layer
- Use async/await everywhere
- Avoid async void
- Use DTOs between layers
- Repository pattern required



