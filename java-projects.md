# Java Projects

## 1. Weather API
Create an API that returns current weather.  This API will call openweather api to get current weather, transform the result and return the result to the user.

URL:  http://localhost:8080/weather/v1?city={city}&state={state}&country={country}
Request Method:  GET
Response (200):
```
{
      "city" : "Chicago",
      "state" : "IL",
      "country" : "US",
      "currentTemperature" : 80.0,
      "feelsLike" : 85.00
}
```

Response (404) - Invalid City
```
{
      "code" : 404,
      "message" : "City not found"
}
```

Response (500) - Failure to process request
```
{
      "code" : 500,
      "message" : "Unable to process request, please try again"
}
```

## 2. Customer API
Create an API to perform CRUD operations (create, read, update, delete) on a database table called "customer".

You may use your choice of database(Postgres, MySQL etc.) to store this information. 
Table will have the following attributes:
 + id:  integer
 + first_name: string
 + last_name: string
 + address1: string
 + address2: string
 + city: string
 + state: string
 + postal_code: string
 + country: string


### 2.1 Create customer
URL:  http://localhost:8080/weather/v1?customers

Request Method:  POST

Request:
```
{
      "firstName" : "John",
      "lastName" : "Doe",
      "address1" : "1 Main Street",
      "city" : "Chicago",
      "state" : "IL",
      "postalCode" : "55111",
      "country" : "US"
}
```

Response (201):
```
{
      "id" : 12345,
      "firstName" : "John",
      "lastName" : "Doe",
      "address1" : "1 Main Street",
      "city" : "Chicago",
      "state" : "IL",
      "postalCode" : "55111",
      "country" : "US"
}
```

### 2.2 Get customer
URL:  http://localhost:8080/weather/v1?customers/{id}

Request Method:  GET

Response (200):
```
{
      "id" : 12345,
      "firstName" : "John",
      "lastName" : "Doe",
      "address1" : "2 Main Street",
      "city" : "Chicago",
      "state" : "IL",
      "postalCode" : "55111",
      "country" : "US"
}
```

### 2.3 Update customer
URL:  http://localhost:8080/weather/v1?customers/{id}

Request Method:  POST

Request:
```
{
      "firstName" : "John",
      "lastName" : "Doe",
      "address1" : "2 Main Street",
      "city" : "Chicago",
      "state" : "IL",
      "postalCode" : "55111",
      "country" : "US"
}
```

Response (200):
```
{
      "id" : 12345,
      "firstName" : "John",
      "lastName" : "Doe",
      "address1" : "2 Main Street",
      "city" : "Chicago",
      "state" : "IL",
      "postalCode" : "55111",
      "country" : "US"
}
```

### 2.4 Delete customer
URL:  http://localhost:8080/weather/v1?customers/{id}

Request Method:  DELETE

Response:
```
{
    "code" : 200,
    "message" : "Customer deleted successfully"
}
```

## 3. Customer API (Firebase DB)
Convert the above API to use Google Firebase DB as the persistence layer.

See https://www.youtube.com/watch?v=ScsID2yPB8k to learn about Google Firebase DB

## 4. Products API
TBD


