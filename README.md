# Server
A web api application which provides restful apis using .Net Core 3.1

Architecture: n-player
  - Core: contains Entities and EntityConfigurations
  - Infratructure: contains DbContext, Migrations, Repositories and UnitOfWork
  - Application: contains Services, Models, Extensions,..
  - Web Application

Technicals:
  - Sql Server
  - Ef Core
    - Fluent Api
    - Lazy loading
    - Eager loading
  - FLuent validation
  - Auto mapper
  - Resize image

Technicals (in coming):
  - Docker
  - Apply github CI/CD
