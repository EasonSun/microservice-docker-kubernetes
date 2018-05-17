nginx: router to 3 servers

api

- model: db set up as objects using sqlalchemy
- view: CRUD using flask MethodView
- server: lifecycle hooks and request dispatch using flask

fe 

mailer

- model: ActiveRecord
- controller: 
 - create: enque SendEmail into resque as a bg rake tasks 

dev env 

` docker-compose up `

prod env

kubernetes

![alt text](https://github.com/EasonSun/microservice-docker-kubernetes/overall.png)

TODO: 

work on fe

use kubernetes

borrowed from https://resources.oreilly.com/examples/0636920048244/

ref

https://docs.docker.com/compose/networking/#links
https://github.com/resque/resque
https://github.com/resque/resque
