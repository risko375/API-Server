# API-Server
An API server with authentication

Creating an API server with authentication using Bcrypt and JWT token

Allows for 3 possible user flows:

Signing up -> Verify Email is not in use -> return token

Signing in -> Verify Email/Password -> return token

Authorised request -> Verify token -> resource access
