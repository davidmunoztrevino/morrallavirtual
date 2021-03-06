source 'https://rubygems.org'

gem 'cancan'
gem 'devise'
gem 'bootstrap-sass', '~> 3.2.0'
gem 'autoprefixer-rails'
gem 'rails', '4.2.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'twitter-bootstrap-rails'
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

gem 'haml'

group :test do
  gem 'rspec'
  gem 'rspec-rails'
  gem 'spring-commands-rspec'
  gem 'rb-fsevent' if `uname` =~ /Darwin/
  gem 'factory_girl'
  gem 'factory_girl_rails'
  gem 'fuubar'
  gem 'shoulda-matchers', require: false
  gem 'faker'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'simplecov', require: false
end

gem 'puma'

group :development do
  gem 'pry'
  gem 'pry-doc'
  gem 'pry-rails'
  gem 'guard'
  gem 'guard-rspec', require: false
  gem 'guard-bundler', require: false
  gem 'guard-shell', require: false
  gem 'guard-livereload', require: false
  gem "rack-livereload"
  gem 'guard-spring'
  gem 'rspec-nc'
  gem 'sqlite3'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
