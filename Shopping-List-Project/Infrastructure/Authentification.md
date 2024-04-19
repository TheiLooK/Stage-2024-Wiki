# Request header

- it works (replace '...' with the API_KEY)
```
curl --location --request GET 'http://localhost:8080/users' --header 'X-API-KEY: ...'
```
- it doesn't work
```
curl --location --request GET 'http://localhost:8080/users'
```