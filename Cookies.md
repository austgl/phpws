# Introduction #

Since the phpws server runs outside the webserver there is no support for sessions. Authenthication needs a different approach.

However, you can still do authenthication by Cookies.

# Retreiving Cookies #

Each WebSocketUser implements the getCookies() method. Returning the cookies as an key-value array.

To use data from the cookie for authentication we need to override the onConnect() function in the server.

# Sessions #

PHP sessions (by using $