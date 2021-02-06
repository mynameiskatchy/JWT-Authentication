# JWT-Authentication

# generate ranodm list of characters 
node
require('crypto').randomBytes(64).toString('hex')

eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoiS3lsZSIsImlhdCI6MTYwOTY2NDUzNX0.zUqAN3uyqwe0h6512eZz5USfOW-ZNT_ZmSSuepOeeMU


session-based authentication is saved on a particular server
but with jwt, all the information is in the token so you can use it across multiple servers

impliment refresh tokens
take authentication server, move it outside of our other server
we have on server that handles all out creation of tokens & refreshing of tokens
and other server to handle specific case of getting post, saving post, api related tasks (everything but authentication)


deauthenticate refresh tokens

status codes