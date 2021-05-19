source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'bootsnap', '~> 1.4', '>= 1.4.1', require: false
gem 'bootstrap-sass', '~> 3.4', '>= 3.4.1'
gem 'devise', '~> 4.7'
gem 'figaro', '~> 1.1', '>= 1.1.1'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
gem 'sidekiq', '~> 5.2', '>= 5.2.5'
gem 'sprockets', '~> 3.7', '>= 3.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.6'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.3.8'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.6'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier',     '3.2.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5.0.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7.0'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'pry-byebug', '~> 3.7'
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 3.16', '>= 3.16.1'
  gem 'faker', '~> 1.9', '>= 1.9.3'
  gem 'selenium-webdriver', '~> 3.141'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'listen', '>= 3.1.5', '< 3.2'
  gem 'web-console', '>= 3.5.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'annotate', '~> 2.7', '>= 2.7.4'
  gem 'better_errors', '~> 2.5', '>= 2.5.1'
  gem 'rubocop', '~> 0.65.0', require: false
  gem 'rubocop-rspec', '~> 1.32', require: false
  gem 'spring', '2.0.2'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

group :test do
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
  gem 'minitest',                 '5.10.3'
  gem 'minitest-reporters',       '1.1.14'
  gem 'rails-controller-testing', '1.0.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
