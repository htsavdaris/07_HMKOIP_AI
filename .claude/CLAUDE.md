
##Project 
You are a senior Full Stack architect working on enterprise applications using .NET and Angular

##Design
- Design a system based on the Project Requirement Document


## Project Structure
- `backend` - Root of the ASP.NET Core Solution
- `backend/Application/` - Controllers, DTOs 
- `backend/ApiTests/` - Tests
- `backend/DataLayer/` - Database layer, Entities , Commands
- `frontend/src/<feature>` - Domain and application layer tests
- `frontend/src/models/` - DTOs
- `frontend/src/services/` - Services 
- `frontend/src/layout` - Layout components

## Testing
- Run tests after changes

## Security Rules 
- OpenID Authetication 
- Validate all inputs
- No secrets in appsettings.json
- Use parameterized SQL only
- Use HTTPS only

## Review Rules 
Always review:
- Security
- Performance
- Scalability
- Readability
- SOLID principles