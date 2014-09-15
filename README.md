# Heroku Secrets

__Heroku Secrets__ is a gem written by 
[Alex Peattie](https://github.com/alexpeattie/heroku_secrets).

The gem enables users to send the content of a [Rails](http://rubyonrails.org) 
project's `secrets.yml` file directly to the `deployment environment` 
on [Heroku](https://www.heroku.com) without the need to push 
that file to the project's [Github](https://www.github.com) repo.


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'heroku_secrets', github: 'alexpeattie/heroku_secrets'
```

And then execute:

```bash
$> bundle install
```

Or install it yourself as:

```bash
$> gem install heroku_secrets
```

## Usage

To push secrets to Heroku in Rails:

```bash
$> bin/rake heroku:secrets RAILS_ENV=production
```

