source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.3'
# Use sqlite3 as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development do
  # sabisu gems
  gem 'sabisu_rails', github: "IcaliaLabs/sabisu-rails"
  gem 'compass-rails', '~> 2.0.2'
  gem 'furatto'
  gem 'font-awesome-rails'
  gem 'simple_form'

  # Faker
  gem 'faker'
  gem 'populator'
end

group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'rspec-rails', '~> 3.0'
end

group :test do
  gem 'factory_girl_rails'
  gem 'ffaker'
  gem 'shoulda-matchers'
end

gem 'devise'
gem 'active_model_serializers', '0.10.0.rc2'
gem 'kaminari'