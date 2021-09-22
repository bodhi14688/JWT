# JWT
SpringBoot with JWT security


Note: As of now not connected to any database with actual user data, provisionally hardcoded


Request for Post to generate JWT token:
http://localhost:8080/authenticate

{
	"userName" : "foo",
	"password" : "foo"
}

After generating the token we need to added the token to the Authorization tab when doing the GET request
http://localhost:8080/hello

need to add JWT with the below specified string:

"Bearer "
