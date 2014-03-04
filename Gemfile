source 'https://rubygems.org'

#gem 'spork', :github => 'sporkrb/spork'
#gem 'spork-rails', :github => 'sporkrb/spork-rails'

gem 'rails', '4.0.2'
gem 'sqlite3'


group :development, :test do
  gem 'rspec-rails', '~> 2.12.2'
  #gem 'spork', '~> 0.9.2'
  gem 'spork', :github => 'sporkrb/spork'
  gem 'spork-rails', :github => 'sporkrb/spork-rails'
end

group :test do
  gem 'cucumber-rails', '~> 1.3.0', require:false
  gem 'database_cleaner', '~>0.9.1'
end



group :assets do
  gem 'sass-rails', '~> 4.0.0'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.0.0'
end

# Use jquery as the JavaScript library
gem 'jquery-rails'


group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
