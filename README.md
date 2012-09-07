# Rails Reverse Db [![Build Status](https://secure.travis-ci.org/cmckni3/rails_reverse_db.png)](http://travis-ci.org/cmckni3/rails_reverse_db) [![Code Climate](https://codeclimate.com/badge.png)](https://codeclimate.com/github/cmckni3/rails_reverse_db)

Gem for reverse engineering an existing database using ActiveRecord

Runs the rails scaffolding command with the appropriate arguments
to generate models, controllers, tests, etc from an existing database

## Installation

    gem 'rails_reverse_db'

## Usage

`bundle exec rake reverse_engineer OPTIONS` OR `rake reverse_engineer OPTIONS`
    
By default this will run `rails generate scaffold TableName column:string`

## Copyright

Copyright (c) 2012 Chris McKnight and Anthony Heukmes (2009). Licensed under the MIT License

## Contributions

Inspired by and uses a little modified code from [Anthony Heukmes](https://github.com/ahe/) [Reverse Scaffold Script](https://github.com/ahe/reverse_scaffold)