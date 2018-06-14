# General Walkthrough

* Create Gemfile and bring in gems
* `bundle`
* create config.ru file
* create models dir
* create controllers dir
* create model file
* create controller file
* link both model and controller in config
* Bring in Rack::Reloader and Rack::MethodOverride
* run controller

* Create 7 RESTful routes and test them using sinatra/postman
* Seed your file using `psql -d <DBNAME> -f seed.sql`
* Start with READ
* INDEX controller and Model methods (def self.all)
* SHOW controller and Model methods (def self.find id)
* Test they work

* Move on to CREATE
* create NEW Form ERB, build out controller and Model (save)

* Move on to UPDATE
* edit def save method in Model depending on whether ID exists
* Create edit form

*Join forms together and test

* Create self.destroy method in Model, link to it in the delete controller

*Add delete button
