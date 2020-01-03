# Setup

## Linux

Make sure that you UID is exported:

`export -p | grep UID`

If it's not exported, then you need to run:

`export UID`

## node-auth

## curl

```sh
curl -v -X POST localhost:5000/register -H 'Content-Type: application/json' \
-d '{"email": "ricardo@gmail.com", "name": "Ricardo", "password": "secret12", "passwordConfirmation": "secret12"}'
```
