source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.0.beta2'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0.rc1'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc',          group: :doc, require: false

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

group :test do
    gem 'factory_girl_rails' #https://github.com/thoughtbot/factory_girl_rails
    gem 'coveralls', require: false
end

group :development do
    gem 'guard-rspec' #https://github.com/guard/guard-rspec
    gem 'guard-spork' #https://github.com/guard/guard-spork
    gem 'annotate' #https://github.com/ctran/annotate_models
    gem 'better_errors' #https://github.com/charliesome/better_errors
    gem 'spring' # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/jonleighton/spring
end

group :development, :test do
	gem 'rspec-rails'
	gem 'capybara'
end