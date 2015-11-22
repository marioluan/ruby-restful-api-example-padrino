# Padrino's RESTFul API example

[![Code Climate](https://codeclimate.com/github/marioluan/ruby-web-frameworks-examples/badges/gpa.svg)](https://codeclimate.com/github/marioluan/ruby-web-frameworks-examples)
[![Test Coverage](https://codeclimate.com/github/marioluan/ruby-web-frameworks-examples/badges/coverage.svg)](https://codeclimate.com/github/marioluan/ruby-web-frameworks-examples/coverage)
***

## Getting Started:

pre-requisites:
- ruby 2.2.3
- bundler
- sqlite

### install dependencies
```shell
$ bundle install
```

### run the migrations
```shell
$ padrino ar:migrate
```

### run unit tests
```shell
$ rspec
# Test coverage report will be available at ./coverage/index.html
```

### check code style
```shell
$ rubocop -S
```

# start the app
```shell
$ ./bin/restful-api
```

TODOs:
- associations
- translations
- searcheble api
- pageable api
- cache
- basic auth and JWT ( https://github.com/jwt/ruby-jwt, https://scotch.io/tutorials/authenticate-a-node-js-api-with-json-web-tokens, https://auth0.com/blog/2014/12/02/using-json-web-tokens-as-api-keys/)
- add repository as a submodule to ruby-web-frameworks-example

### Recommended Sublime Text plugins:
- GitGutter
- BeautifyRuby
- DocBlockr
- RSpec

Move the following description to ruby-web-frameworks-example's README.md
```
# ruby-web-frameworks-examples
Building a API with popular ruby web frameworks: padrino, sinatra, rails-api, grape, etc.
```