source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
ruby '2.0.0'
gem 'rails', '4.0.1'
gem 'coffee-rails', '~> 4.0.0'

# Use postgresql as the database for Active Record
gem 'pg'
gem 'haml'

gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

group :development, :test do
  #testing gems
  gem 'annotate'

  gem 'quiet_assets'
  gem 'binding_of_caller'
  gem 'meta_request'
end

group :development do
  #causes problem in conjunction with rspec test
  gem 'better_errors' #do not put this in production or everyone will be able to mess around with variables
end

group :production, :development do
    gem 'pry-debugger'
    gem 'pry-stack_explorer'
end