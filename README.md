node-red-contrib-thingsboard-rest-api-auth
================

Node-RED node for thingsboard-rest-api-auth

 ThingsBoard open-source IoT platform REST API documentation.

## Install

To install the stable version use the `Menu - Manage palette - Install` 
option and search for node-red-contrib-thingsboard-rest-api-auth, or run the following 
command in your Node-RED user directory, typically `~/.node-red`

    npm install node-red-contrib-thingsboard-rest-api-auth

## Usage

### Methods

#### POST /api/auth/login

Login method used to authenticate user and get JWT token data.

Value of the response **token** field can be used as **X-Authorization** header value:

`X-Authorization: Bearer $JWT_TOKEN_VALUE`.

    body : 
     
    Accept : 'application/json'
    Content-Type : 'application/json'


## License

#### Apache License Version 2.0

https://github.com/thingsboard/thingsboard/blob/master/LICENSE