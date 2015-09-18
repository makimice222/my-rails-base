source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

####################################################
# Customize
####################################################

# Flexible authentication solution for Rails with Warden.
gem 'devise'

# Rails engine that provides an easy-to-use interface for managing your data
gem "rails_admin"

# Nokogiri (鋸) is an HTML, XML, SAX, and Reader parser with XPath and CSS selector support.
gem 'nokogiri'

# A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for modern web app frameworks and ORMs
gem 'kaminari'

# twitter bootstrap rails gem that allows easy customization of bootstrap's less and javascript components
gem 'twitter-bootswatch-rails' , '~> 3.3.2.0'

# rails controller and view helpers for twitter bootstrap's alerts and breadcrumbs
gem 'twitter-bootswatch-rails-helpers' , '~> 3.3.2.0'

# The dynamic stylesheet language for the Rails asset pipeline.
gem 'less-rails'

group :development, :test do
  # Better error page for Rack apps
  gem 'better_errors'
  # Retrieve the binding of a method's caller in MRI 1.9.2+
  gem 'binding_of_caller'
  # a code metric tool for rails projects
  gem "rails_best_practices"

  # Guard::RSpec automatically run your specs (much like autotest)
  gem 'guard-rspec'
  # rspec-rails is a testing framework for Rails 3.x and 4.x.
  gem 'rspec-rails'
  # Guard::LiveReload automatically reload your browser when 'view' files are modified.
  gem 'guard-livereload'
end
