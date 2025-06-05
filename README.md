# prime-number-api
Express Server API using NodeJS that takes a number as input and returns whether it's a prime number or not.

--- Node JS needed to be installed in the computer

1. Go to Project Repo, Clone it Locally 
  ```bash
  git clone git@github.com:paul-abhirup/prime-number-api.git                                cd prime-number-api
  npm install
  ```
2. Run Server
  ```
  node server.js
  ```  
3. Testing Endpoint
  We can Test the API endpoint using different strategies
    1. Testing using Web Browser
    Visit: http://localhost:3000/isprime/7 (replace 7 with any number)

    2. Testing using cURL
    `curl http://localhost:3000/isprime/13`

    3. Testing using Postman 
    Send a GET request to http://localhost:3000/isprime/29


Expected Response:
For a prime number (e.g., 7):
```
{
  "number": 7,
  "isPrime": true
}
```

For a non-prime number (e.g., 8):
```
{
  "number": 8,
  "isPrime": false
}
```

For invalid input (e.g., 'abc'):
```
{
  "error": "Please provide a valid number"
}
```


