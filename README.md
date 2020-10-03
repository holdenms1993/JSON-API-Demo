# JSON-API-Demo

This is an API demonstration that shows POST/GET and authentication methods for an API. It demonstrates a simple JSON structure and how to create items and update prices.

Use https://www.postman.com/ as an easy way to test this API if you run the app.py API.

app.py: The main API app. Includes GET and POST methods.

security.py: Includes variables to store a User class with a User ID, username, and password. For now, only one is included. The authenticate function checks if the posted username and password match, if not it returns None. The identity function will take the created JSON web token and make sure that the identity matches.

user.py: Creates a user class so users can easily be created or updated in the security.py file.
