# RHMAP Keycloak Cloud App 
A demo app on how to secure endpoints using Keycloak for authenticaton and authorization.
The hello world API uses Keycloak for Authentication and Authorization

# Group Hello World API

# hello [/hello]

'Hello world' endpoint.

## hello [POST] 

'Hello world' endpoint.

+ Request (application/json)
    + Body
            {
              "hello": "world"
            }

+ Response 200 (application/json)
    + Body
            {
              "msg": "Hello world"
            }

# Run app locally:
* Download the code
* Run npm install
* Run grunt serve






