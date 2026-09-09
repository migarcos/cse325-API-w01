# API  with ASP.NET Core Controllers
A RESTful service with ASP.NET Core controllers that supports create, read, update, and delete (CRUD) operations.
## Set Up
The first command to create the project is:
````
dotnet new webapi -controllers -f net10.0
````
## Testing endpoints
Open a Terminal view, and **execute the APP** using:
````
dotnet run
````
- Openin the VScode editor **ContosoPizza.http** file:
- Click on the **Send Request** command above the enpoint to test

   (here an example to retrieve all data using GET)
````
 Send Request 
GET {{ContosoPizza_HostAddress}}/pizza/
Accept: application/json
````
- Output (to the GET initial endpoint)
````
HTTP/1.1 200 OK
Connection: close
Content-Type: application/json; charset=utf-8
Date: Wed, 09 Sep 2026 14:21:38 GMT
Server: Kestrel
Transfer-Encoding: chunked

[
  {
    "id": 1,
    "name": "Classic Italian",
    "isGlutenFree": false
  },
  {
    "id": 2,
    "name": "Veggie",
    "isGlutenFree": true
  }
]
````