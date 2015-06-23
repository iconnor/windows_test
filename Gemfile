source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
ruby '2.0.0'
gem 'rails', '4.2.0'
# Use sqlite3 as the database for Active Record
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.


# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end


gem 'bootstrap-sass'
gem 'devise'
gem 'gibbon'
gem 'payola-payments'
gem 'pg'
gem 'nested-hstore'
gem 'squeel'
gem 'slim-rails'
gem 'sucker_punch'

platforms :ruby do 
# linux
gem 'unicorn'
gem 'unicorn-rails'
gem "therubyracer"
end

platforms :mingw, :mswin, :x64_mingw do
# gems specific to windows
gem 'tzinfo-data'
end

#gem 'grape'
gem 'grape', '0.9.0'
gem 'grape-entity', '~> 0.4'
gem 'grape-swagger', '~> 0.7.2'
gem 'grape-swagger-ui', '0.0.4'
gem 'grape-rails-cache'
gem 'tilt', '1.4.1'

gem 'compass', "0.12.7"
gem 'compass-rails'
gem 'nested-hstore'
gem 'inherited_resources', '~> 1.4'
gem 'cached_web'
gem 'koala'
gem 'rmagick'
gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-google-oauth2'
gem 'omniauth-twitter'
gem 'omniauth-instagram'
gem 'omniauth-github'
gem 'omniauth-bitbucket'
gem 'omniauth-gitlab'
gem 'omniauth-heroku'
gem 'fog'
gem 'google-api-client'

gem "acts_as_follower"

gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'carrierwave'
gem 'carrierwave_backgrounder'
gem 'carrierwave-processing'
gem 's3'

gem 'sidekiq'
gem 'sidekiq-failures'
gem 'nokogiri'
gem 'premailer-rails'

gem "github_api"
gem 'platform-api' #heroku api
gem "octokit", "~> 3.0"

#gem 'bitbucket_rest_api', path: '/Users/iconnor/workspace/bitbucket'
gem "bitbucket_rest_api", github: 'projectlounge/bitbucket'
gem 'circleci'
gem "travis"
#gem 'droplet_kit'
gem 'vultr', github: 'iconnor/vultr.rb'

gem "chartkick"
gem 'aws-sdk', '~> 2'

gem 'intercom-rails', '~> 0.2.21'
gem 'intercom', "~> 2.2.1"
gem 'newrelic_rpm'
gem 'raygun4ruby'
gem 'rack-attack'
  
gem "rack-google-analytics"
gem "brakeman", '~> 3.0.2'
gem "metric_fu"
gem "hirefire-resource", github: 'projectlounge/hirefire-resource'
gem 'yamldiff'
gem 'mechanize'
gem 'cached_web'

gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby'
gem "slack-notify"
gem 'hipchat'

gem 'quiet_assets'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_20]
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'haml2slim'
  gem 'html2haml'
  gem 'quiet_assets'
  gem 'rails_apps_pages'
  gem 'rails_apps_testing'
  gem 'rails_layout'
  gem 'rb-fchange', :require=>false
  gem 'rb-fsevent', :require=>false
  gem 'rb-inotify', :require=>false
  gem 'spring'
  gem 'ffaker'
  gem 'annotate'
  gem 'spring-commands-rspec'
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rspec-rails'
end

group :production do
  gem 'rails_12factor'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'selenium-webdriver'
end

