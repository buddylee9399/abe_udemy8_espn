# THINGS IN HERE

## GEMS

```
gem "sassc-rails"
gem 'simple_form'
gem 'devise'
gem 'bootstrap-sass'
```
- sassc for scss
- didnt use bootstrap
- devise set for turbo, rails 7
- from: https://dev.to/efocoder/how-to-use-devise-with-turbo-in-rails-7-9n9

## MODELS
- devise user
- user has many messages and comments
- comments belongs to users and messages

## OTHER
- used custom stylings
- imported fonts via the app.scss

```
@import url(https://fonts.googleapis.com/css?family=Lato);
```