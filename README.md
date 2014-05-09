== README

This is the repo for the Belgian Ruby UserGroup website ([BRUG](http://brug.be))
Please fork or ask for project access so we can make this even better.

* Ruby version
  * production runs on 1.9.3+
  * Also works on Ruby 2

* Configuration

Copy .env.example to .env and fill in all the keys. You need to create a twitter application at [http://dev.twitter.com/apps/new](http://dev.twitter.com/apps/new)

* Database creation

We used mysql, copy the config/database.yml.example to config/databae.yml, fill in all the required fields and run these default rails commands

    rake db:create:all
    rake db:migrate
    rake db:seed

* How to run the test suite

We used minitest, so just run **rake** or **rake test**

* Deployment instructions

Runs on [Openminds](http://openminds.be). Contact us if you would like to be able to deploy. We only need your public ssh key.
