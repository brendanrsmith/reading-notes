# Access Control

## When is Basic Authorization used vs. Bearer Authorization?

Basic auth would be used for sign-up functionality before the client's identity can be verified.

## What does the JSON Web Token package do?

It handles the creation and verification of JWTs in an express server.

## What considerations should we make when creating and storing a SECRET?

SECRETs should not be easily guessable, as someone could brute force a series of commonly used passwords into an encryption in order to pass your auth verification.

## Term

**encryption** - the process of encoding information from plaintext into cyphertext

**token** - a portion of data passed between computers in a token-ring network. If a computer has a token, it can talk to other computers in a network. [src](https://www.computerhope.com/jargon/t/token.htm)

**bearer** - a system of authenticaion in which the bearer carries authentication details that are checked by the recipient.

**secret** - a secret known only to the application and the authentication server

**JSON Web Token** - a compact and self-contained way for securely transmitting information between parties as a JSON object [src](https://jwt.io/introduction/)

[RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

[5 steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

[wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)
