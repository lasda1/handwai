# Handwai Project

Used Technologies:

- Nodejs
- Flask
- Reactjs
- Python

# Development

### Requirements:

- docker
- docker-compose

### How to run it

```sh
# go to the root folder and run
$ docker compose up
# it may takes some minutes you can get a coffee :p
```

then you need to add an admin by calling a rest api : Post: http://localhost:3000/users/register
and you can use this object:

```json
{
  "email": "admin@gmail.com",
  "password": "test",
  "isAdmin": true
}
```

(if you are using postman you will find a collection with all the rest apis )
