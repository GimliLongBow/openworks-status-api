source 'https://rubygems.org'


gem 'rails', '4.2.3'

#gem 'jsonapi-resources'

# API Gems
gem 'active_model_serializers', '~> 0.10.x'

gem 'rack-cors', :require => 'rack/cors'

group :production do
  gem 'pg'
end

group :development do
  gem 'pry'
  gem 'sqlite3'
end

group :development, :test do
  gem 'spring'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem "factory_girl_rails", "~> 4.0"
  gem 'simplecov', '~> 0.11'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano', :group => :development

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
