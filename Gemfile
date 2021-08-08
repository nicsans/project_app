source 'https://rubygems.org'

ruby '2.7.3'
#gem 'sqlite3', '~> 1.4'

# Default gems
gem 'rails', '~> 5.2.6'
gem 'pg'

gem "active_model_serializers"

# Use SCSS for stylesheets
gem 'bootstrap-sass', '3.4.1'
gem 'sass-rails', '~> 6.0'
gem 'sprockets', '~> 4.0.0'

# Datepicker
gem 'momentjs-rails', '>= 2.9.0'
gem 'bootstrap3-datetimepicker-rails', '~> 4.17.47'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 5.0.0'

# Social Medias
gem 'twitter'

# charts
gem 'd3-rails', '~> 3.5.17'
gem 'c3-rails'
gem 'chartkick',                 '>= 3.3.1'

# Date grouping gem
gem 'groupdate'

# Paranoid Deletion
gem "paranoia", "~> 2.2"

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Google Maps
gem 'underscore-rails'
gem 'gmaps4rails'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Add React and webpacker
gem 'webpacker'
gem 'react-rails', "~> 2.6.1"

# JQuery plugin for mentions
gem 'jquery-atwho-rails'

# Backgrounding Emails
gem 'sidekiq'
gem 'sidekiq-delay'

# pagination Library
gem 'kaminari'

# Email Styling
gem 'premailer-rails'
gem 'nokogiri'

# Integrations: Customer IO for email
gem 'customerio', '~> 2.2.0'

# Outgoing http requests
gem 'faraday'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '~> 5.2.1'

# Render JSON-API-structured responses
gem 'acts_responsible', '0.0.4'
gem 'rabl'
gem 'jsonapi-serializer', '~> 2.1.0'

# User authentication
gem 'devise',           '4.7.1'

# External CRM Integrations
gem 'restforce' # Salesforce

# Fulltext Searching
gem 'pg_search'

# Notify when a company signs up
gem 'slack-notifier'

# Cron job scheduler
gem 'whenever', require: false

# Payments
gem 'stripe'

# DateDropper
gem 'datedropper-rails'

# Cross-origin resource scripting
gem 'rack-cors', require: 'rack/cors'

# Storage on S3
gem 'aws-sdk', '~> 2'

# Error notification via Email
gem 'exception_notification'

# setup calendar events on clients devices and pc
gem 'icalendar', '~> 2.3'

# Performance
gem 'newrelic_rpm'

# Spreadsheet processing
gem 'roo', '2.5.1'

# S3 interactions
gem 'fog-aws', '3.6.6'
              # ^^^^^^ !!! DO NOT UPDATE THIS UNLESS IMAGE UPLOADS
              #        HAVE BEEN TESTED IN ANDROID APP !!!

# Caching
gem 'dalli'
gem 'connection_pool'

# Browser/platform detection
gem 'browser'

# Support for Ruby 3.0.0
gem 'rexml'

# Distance measurements between lat/long cooreds
gem 'geokit', '~> 1.13.1'

# PDF Generation
gem 'wicked_pdf'
gem 'wkhtmltopdf-binary', '~> 0.12.6'

# Spreadsheet parsing
gem 'spreadsheet'

# Heroku requirements as per https://devcenter.heroku.com/articles/getting-started-with-rails4
group :production do
  gem 'rails_12factor'
  gem 'puma'
end

group :development do
  gem 'web-console'
end

group :development, :test do
  gem 'byebug'
  gem 'spring'
  gem 'bullet'
  gem 'brakeman'
  gem 'bundler-audit'
end

group :test do
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'guard-rspec'
  gem 'capybara'
  gem 'shoulda-matchers', require: false
  gem 'rspec-collection_matchers', require: false
  gem 'json-schema'
  gem 'simplecov', require: false
  gem 'rspec-rabl'
  gem 'timecop'
  gem 'rails-controller-testing'
  gem 'benchmark'
end

group :script do
  gem 'highline'     # Input handling
end

install_if -> { RUBY_PLATFORM =~ /darwin/ } do
  gem "derailed"
end
