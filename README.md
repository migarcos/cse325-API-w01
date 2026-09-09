# API  with ASP.NET Core Controllers
A RESTful service with ASP.NET Core controllers that supports create, read, update, and delete (CRUD) operations.
## Set Up
The first command to create the project is:
````
dotnet new webapi -controllers -f net10.0
````
## Testing endpoints
Open a Terminal view, an execute using:
````
dotnet run
````
- Open ContosoPizza.http:
- Select the Send Request command above the enpoint to test

   (here an example to retrieve all data using GET)
````
** Send Request ** 
GET {{ContosoPizza_HostAddress}}/pizza/
Accept: application/json
````