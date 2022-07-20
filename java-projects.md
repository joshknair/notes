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

