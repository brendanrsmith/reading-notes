# Event Driven Applications

Event driven programming is a programming paradigm in which an main event loop is used to handle user inputs, processing, and outputs. User events are triggered and handled with returned promises inside callback functions.

## Why is access control important?

To protect sensitive resources from being accessed or manipulated by users.

## Describe an application that would need access control

Any web server with a database should utilize access control in order to protect the db from unintended manipulation.

## What is a role used for?

A role is used to specify programatically the permissions granted to a given user. Roles are mutable.

## Why is role based access control more scalable than discretionary or mandatory access control?

Because you can change user roles at any point, it allows significantly simpler and easier management of user permissions over time.

## Document the following Vocabulary Terms

**Authorization** - the act of specifying access priveledges and giving those priveledges to users.

**Role Based Access Control** - an authorization paradigm in which permissions are granted via a role attribute for each user specifying specific permissions.

**Capabilities** - The specific abilities granted to each user in a role based access control paradigm (i.e. Create, Read, Update, or Delete).
