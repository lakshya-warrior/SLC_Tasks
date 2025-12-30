**Changes**

_docker-compose.yml_

Had to change the gateway platform to run on macbook

Commented out the auth service section.

Commented out the files service section.

Commented out auth and files upstream blocks and location blocks

Authentication Bypass

in the mutation file added user

user = {
        "role": "cc", 
        "uid": "idk"
    }

Commented out all calls to authentication   

_in nginx_

Commented out auth and files upstream blocks and location blocks
