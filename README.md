### JWT Token Implementation in a Golang

In this code we will create a three handlers <br>
-> Login Handler: Which checks for user login and generates the JWT token. <br>
-> Home Handler: This Page loading is succeded if JWT token is valid. <br>
-> Refresh Handler: This handler is used to regenerate the token at last 30 secs expiring time of live token.


#### What JWT is?

JSON Web Tokens(JWT) are an open, industry standard RFC 7519 method for representing claims securely between two parties (Read more here https://jwt.io/introduction).

