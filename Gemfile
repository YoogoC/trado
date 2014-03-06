source 'http://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Production gems
group :production do
  gem 'mysql2'
  gem 'lograge'
end

# Development gems
group :development do
    gem 'better_errors'
    gem 'binding_of_caller'
    gem 'meta_request'
    gem 'haml-rails'
    gem 'quiet_assets'
    gem 'rack-mini-profiler'
    gem 'capistrano', '~> 2.15'
    gem 'bullet'
    gem 'haml'
    gem 'metric_fu'
    platforms :ruby do
      gem 'capistrano-unicorn', :require => false
    end
end

group :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'capybara'
  # gem 'selenium-webdriver'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'faker'
  gem 'spork'
  gem 'guard-rspec', :require => false
  gem 'guard-spork'
  # Testing postgresql on Travis CI
  gem 'pg'
end

group :development, :test do
  gem 'pry'
  gem 'sqlite3'
  gem 'terminal-notifier-guard', :platforms => :ruby
end
# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'compass-rails'
  gem 'jquery-rails'
  gem 'uglifier', '>= 1.0.3'
  gem 'asset_sync'
end

platforms :ruby do
  gem 'unicorn'
end

# Logging/Monitoring
gem 'rollbar'
gem 'newrelic_rpm'

# Search
gem 'searchkick'

# Datepicker
gem 'bootstrap-datepicker-rails'

gem 'wicked'

gem 'foreman',   '~> 0.61.0'

# Transaction handler
gem 'activemerchant'

# RTE
gem 'redactor-rails'

# Authenication
gem 'devise'
gem 'cancan'

# Friendly URLs
gem 'friendly_id', '~> 4.0.10'

# Image uploader
gem 'mini_magick'
gem 'carrierwave'
gem 'fog'
gem 'unf' # Dependency for fog

# Administration
gem 'rails_admin'

# Sitemap
gem 'sitemap_generator'

# Global
gem 'global'

# Processing
gem 'whenever', :require => false

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', git: 'https://github.com/codahale/bcrypt-ruby.git', :require => 'bcrypt'