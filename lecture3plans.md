#LECTURE 3: 
##REVIEW, DATAMODELLING, OBJECTS, ACTIVE RECORD, WORKSHOP

###MVC PATTERN REVIEW
- Draw MVC patter
- walkthrough together
- identify files
- walkthrough by students

###RAILS REVIEW
- how to make new rails project
- how to scaffold
- what does scaffold give us
- how do we run this?
  - gemfile review/ bundle install
  - migrations/ rake db:migrate
  - server/ rails s

###DATAMODELLING
- what is data modelling
- what are objects
  - collections of data and behavior
  - these obejcts are made from classes, will be the tables in our database
  - objects are instances of the class, they are the rows
  - they have properties, these are the columns
- what objects does our application need
- has_many, belongs_to
- join tables

###ACTIVERECORD
- activerecord is a way for us to build our databass
- creates instructions that are run in time order
- can add table, drop table, add column, drop column
- every column needs a type, unlike in ruby

- rake db:migrate
- rake db:reset

###WORKSHOP
- get into groups
- sketch out a basic application
- what objects will you need?
- hard code some objects you think you might need
- use scaffold to create