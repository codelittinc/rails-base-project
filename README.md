This is a rails 5 base project.

## Getting started

1. Clone the project
2. [Install docker](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04) and docker-compose
3. Inside the project folder run `sh bin/dev`
4. Inside the docker console run:
```
  bundle exec rails db:create
  bundle exec rails db:migrate
  bundle exec rails db:seed
  yarn install

  rails s -b `hostname -i`
```
5. Go to your browser and access `http://localhost:3000`

## Here we have the following tools installed:

### Devise
Repo: https://github.com/plataformatec/devise

Devise is a flexible authentication solution for Rails based on Warden.

You can customize all devise views running the following generator:

```
  rails generate devise:views
```

### Rspec Rails
Repo: https://github.com/rspec/rspec-rails

How to execute it:

```
  bundle exec rspec
```
