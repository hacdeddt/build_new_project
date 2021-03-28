source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.4.4'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # gem binding.pry to debug
  gem 'pry', '~> 0.14.0'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  #Security: gem use to check security for app
  gem 'brakeman', '~> 5.0'
  #help to kill N+1 queries and unused eager loading.
  gem 'bullet', '~> 6.1', '>= 6.1.4'
  gem 'better_errors'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
# gem config for variables
gem 'config'
# config environment variable
gem 'dotenv-rails'
#redis
gem 'redis'
gem 'hiredis'
#export file pdf
# gem 'wicked_pdf'
# gem 'wkhtmltopdf-binary'
# Security: check for gem patches and updates
gem 'bundler-audit', '~> 0.6.1'
# font-awesome
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.7'
#This gem protects against typical web attacks. Should work for all Rack apps, including Rails.
gem 'rack-protection', '~> 2.1'
gem 'devise'
gem 'pundit'
gem 'carrierwave'
gem 'annotate', '~> 3.1', '>= 3.1.1'
