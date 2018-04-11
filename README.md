Engineering Project
=======

Dependencies
- postgres

# Setup

- ensure DB is setup with your user creds
> see `config/application.yml`

- You'll also need to setup your rails secret key

# Install

- Install ruby 2.2.5
- Install gems `bundle install`
- DB `bundle exec rake db:create db:migrate`

# Running

- Start rails server
`bundle exec rails s`

- Visit site @ http://localhost:3000
