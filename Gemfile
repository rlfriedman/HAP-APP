source 'https://rubygems.org'

gem 'rails', '3.2.19'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg', group: :production
gem 'rails_12factor', group: :production

gem 'will_paginate', '~> 3.0.4'

gem 'sunspot_rails'
gem 'gravatar_image_tag', '0.1.0'
gem 'paperclip'

gem 'thin'

gem 'fancybox-rails'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :production do
	ruby '1.9.3'
end

group :development, :test do
	gem 'sqlite3'
end

group :test, :development do
  	gem 'turn'
  	gem 'rspec-rails', '2.4.1'
 	gem 'capybara'
  	gem 'guard-rspec'
	gem 'sunspot_solr'
end

gem 'gon'
gem 'geocoder'
gem 'gmaps4rails'


# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
