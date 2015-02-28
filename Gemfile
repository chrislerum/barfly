source 'https://rubygems.org'
gem 'rails', '4.2.0'
gem 'sqlite3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end
ruby '2.2.0'
gem 'slim-rails'
gem 'bootstrap-sass', '~> 3.3.1'
gem 'autoprefixer-rails'
gem 'awesome_print'
gem 'devise'
gem 'pg'
group :test do
  gem 'shoulda-matchers', require: false
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'selenium-webdriver'
  gem 'launchy'
end
#only for heroku:
gem 'rails_12factor', group: :production
group :development do
  gem 'guard-rails'
  gem 'guard-rspec'
  gem "spring-commands-rspec"
end
group :development, :test do
  gem 'database_cleaner'
  gem "rb-fsevent"# if `uname` =~ /Darwin/
  gem 'quiet_assets'
  gem 'factory_girl_rails'
  gem 'rspec-rails', '~> 3.0'
end
