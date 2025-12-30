**Changes**

_docker-compose.yml_

Had to change the gateway platform to run on macbook

Commented out the auth service

Commented out the files service

_Authentication Bypass_

in all the mutation files added user as given below (hardcoded bypass for the authentication)

user = {
        "role": "cc", 
        "uid": "idk"
    }

Commented out all calls to authentication and files (where ever it was checking for user in the data base
like GetUser)

_in nginx_

Commented out auth and files upstream blocks and location blocks
