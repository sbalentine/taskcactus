source 'https://rubygems.org'

# Ruby version
ruby '2.1.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 4.0.3'

# Use Puma as the appserver
gem 'puma', '~> 2.8.0'

# Use Faraday as the HTTP client
gem 'faraday', '~> 0.9.0'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Bootstrap for templating
gem 'bootstrap-sass', '~> 3.1.1'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# Use jQuery as the JavaScript library
gem 'jquery-rails', '~> 3.1.0'

# Use Ember as the Javascript framework
gem 'ember-rails', '~> 0.14.1'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '~> 2.4.0'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '~> 2.2.1'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0.3'

# Javascript Runtime
gem 'execjs'
gem 'therubyracer'

group :production do

  # Use Postgres as the production database for Active Record
  gem 'pg', '~> 0.17.1'

  # Use Heroku as deployment target
  gem 'heroku', '~> 3.4.1'

end

group :development, :test do

  # Use sqlite3 as the development database for Active Record
  gem 'sqlite3', '~> 1.3.9'

  # Use pry for debugging
  gem 'pry', '~> 0.9.12.6'

  # Use better_errors for development ease
  gem 'better_errors', '~> 1.1.0'
  gem 'binding_of_caller', '~> 0.7.2' # Needed for better_errors advanced features

  # Use rspec for testing
  gem 'rspec', '~> 2.14.1'

  # Use simplecov for test result reporting
  gem 'simplecov', '~> 0.8.2'

end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', '~> 0.4.0', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'
