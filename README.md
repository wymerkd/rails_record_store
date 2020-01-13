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

https://github.com/nvm-sh/nvm/blob/master/README.md

Run:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash

nvm install v12.14.0

brew install yarn (if needed)

rails s (to start server)


To fix no database error
Epicodus-7A:rails_record_store Guest$ rails db:migrate
Epicodus-7A:rails_record_store Guest$ rails db:prepare
Epicodus-7A:rails_record_store Guest$ rails s
