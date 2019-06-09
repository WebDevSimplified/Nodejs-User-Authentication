GET http://localhost:3000/users

###

POST http://localhost:3000/users
Content-Type: application/json

{
  "name": "Kyle",
  "password": "password"
}

###

POST http://localhost:3000/users/login
Content-Type: application/json

{
  "name": "Kyle",
  "password": "password"
}