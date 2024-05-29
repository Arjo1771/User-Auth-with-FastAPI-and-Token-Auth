I have created a project in python using FastAPI that creates a hash password, authenticates user then creates an access token for 30 minutes and lets user get information about himself using "/users/me/" tag  and about hypothetical "items" using "users/me/items".
As i have not created front end for this project i generated password by running pwd = get_password_hash("demetre1234") and ran the program and got the hash password and input that in my db to test out the endpoints.

Dependencies:pip install fastapi
             Server to run on:pip install uvicorn[standard]
             Decoding JSON data:pip install python-multipart
             Password hashing and Token auth:pip install python-jose[cryptography]
             Passowrdhashing:pip install passlib[bcrypt]
