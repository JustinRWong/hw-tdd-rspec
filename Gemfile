source 'https://rubygems.org'

ruby '2.7.0'
gem 'rails', '4.2.9'


# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'launchy'
  gem 'rspec-rails'
  gem 'ZenTest'
end

group :test do
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels'
  gem 'simplecov', :require => false
end
group :production do
  gem 'pg', '~> 1.2.3'
end

# Gems used only for assets and not required
# in production environments by default.

  #gem 'therubyracer', '~> 0.12.0'
gem 'sass-rails'
gem 'coffee-rails'
gem 'uglifier'

gem 'jquery-rails'
gem 'haml'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'
