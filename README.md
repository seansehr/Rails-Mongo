Rails-Mongo
===========

A Store using Rails and Mongo

Followed [RailsCast #238](http://railscasts.com/episodes/238-mongoid-revised?view=asciicast) with the following exception due to being on Rails 4.

- Linked to the Github version of Mongoid
  - `gem 'mongoid', '~>4.0.0.beta1', github: 'mongoid/mongoid'`
- When they talk about `attr_accessible :name, :price, :released_on`, those should be strong parameters in Rails 4.