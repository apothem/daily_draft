source 'https://rubygems.org'

gem 'rails', '3.2.9'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'newrelic_rpm'

# Use unicorn as the app server
gem 'unicorn'

# gem 'capistrano'
# To use debugger

# gem 'debugger'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
end

group :production do
  gem 'pg'
end
