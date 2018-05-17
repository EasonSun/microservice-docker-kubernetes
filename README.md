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

TODO: 

work on fe

use kubernetes