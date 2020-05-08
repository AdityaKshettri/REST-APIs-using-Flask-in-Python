# Stores REST Api

This is REST API developed in python and built with Flask, Flask-RESTful, Flask-JWT, and Flask-SQLAlchemy and finally deployed on Heroku. The testing is done using Postman.

# Link : 
https://python-flask-rest-api-stores.herokuapp.com/

# REST APIs :

> POST /register : to signup an a new user.

> POST /login : to login as an existing user.

> POST /logout : to logout from the existing session.

> POST /refresh : to refresh the access token.

> GET /user/<id> : to get the details of a user with given id.
  
> DELETE /user/<id> : to delete a user with given id

> GET /items : to get the list of all Items.

> GET /item/<name> : to the the item with given name.
  
> POST /item/<name> : to add an item to the list.
  
> DELETE /item/<name> : to delete an item from the list.

> PUT /item/<name> : to update/add an item in the list.
  
> GET /stores : to get the list of all the stores along with its items.
  
> GET /store/<name> : to get the details of store with given name.
  
> POST /store/<name> : to add a new store in the list.
  
> DELETE /store/<name> : to delete a store with given name.
