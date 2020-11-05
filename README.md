# auth-service
Auth service is the initial version of jwt auth server. There are two url provides one is to get the token and another dummy api to test the token.

To get the jwt token

POST http://localhost:8080/authenticate
{
    "username":"admin",
    "password":"admin"
}

To test the token with below api

GET http://localhost:8080/hellouser
Set the Bearer token in the authorization header.
