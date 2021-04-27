# Bearer Authorization

## Write the following steps in the correct order

Receive access token
Redirect to a third party authentication endpoint
Register your application to get a client_id and client_secret
Make a request to a third-party API endpoint
Ask the client if they want to sign in via a third party
Receive authorization code
Make a request to the access token endpoint

## What can you do with an authorization code?

An authorization code allows you to make a request for an access token.

## What can you do with an access token?

An access token is used to authenticate access to an api. The token informs the api that the bearer has been authroized to access and perform specific actions specified by the scope that was granted during authorization. [Auth0 docs](https://auth0.com/docs/tokens/access-tokens)

## What’s a benefit of using OAuth instead of your own basic authentication?

It is standardized across the web, and allows you to grant other websites or services access to a users info without sending them their username or password. 

## Term

Client ID - the read-only, unique property of the Client object. public, but encoded.
Client Secret - a secret known only to the application and the auth server. Allows for server and client verification of authorizations.
Authentication Endpoint - endpoint which grants authorization code to client.
Access Token Endpoint - endpoint which grants the client identity and access tokens
API Endpoint - any endpoint which interacts with the client.
Authorization Code - code granted from server authorization endpoint which allows client to request access token.
Access Token - code granted from server access token endpoint.

## Preparation Materials

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

[Intro to JWT](https://jwt.io/introduction/)

[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)