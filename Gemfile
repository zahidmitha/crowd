source 'http://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'
gem 'thin'

# External Authentication gems
gem 'omniauth-identity'
gem 'omniauth-twitter'
gem 'omniauth-facebook'
gem 'omniauth-google-oauth2'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'bootstrap-sass'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem "curb", "~> 0.8.3"

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
gem 'debugger'

group :development, :test do
  # gem 'capybara'
  gem 'launchy'
  gem 'database_cleaner'

  #gem 'capybara-webkit'

  # gem 'capybara-webkit'
  gem "mocha", :require => false

end

group :development do
  gem 'annotate'
  gem 'taps'
  gem 'guard'
  gem 'guard-livereload', :require => false
  gem 'rack-livereload'
  gem 'guard-rails'
  # Added for Guard
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', :require => false
  gem 'rb-fchange', :require => false
  gem 'quiet_assets'

end

group :tools do
  gem 'guard-test'
end




