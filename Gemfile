source 'http://rubygems.org/'

gem 'rails', '3.2.2'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.0.1'
gem 'bootstrap-sass', '2.0.0'
gem 'will_paginate', '3.0.3'
gem 'bootstrap-will_paginate', '0.0.5'
gem 'jquery-rails', '3.1.5'

# Markdown
gem "rdiscount", "~> 1.6.8"

# User model
gem "devise", "~> 2.0.4"

# Deployment 
gem "unicorn", "~> 4.2.1"

group :production do
  gem "pg", "~> 0.13.2"
end

group :development do
  gem "capistrano", "~> 2.11.2"
end

group :development, :test do
	gem 'sqlite3', '~> 1.3.5'
	gem 'rspec-rails', '2.8.1'
end

group :test do
	gem 'capybara', '1.1.2'
	gem 'spork', '0.9.0'
	gem 'factory_girl_rails', '1.4.0'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

