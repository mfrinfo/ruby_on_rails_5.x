# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


http://localhost:3005/admins_backoffice/info/routes
http://localhost:3005/admins_backoffice/admins
http://localhost:3005/users_backoffice/welcome/index

Comandos Rails:
rails g model subject description:string
rails g model answer description:text question:references correct:boolean

rails db:migrate 