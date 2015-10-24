source 'https://rubygems.org'
ruby "2.1.2"


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'
# Use Bootstrap from Twitter as initial Styler
gem 'bootstrap-sass',       '3.2.0.0'
gem 'bootstrap-datepicker-rails'
#date validator gem
gem 'date_validator'
#user Auth
gem 'sorcery'
#navigation gem for menus
#gem 'simple-navigation'
gem 'simple_navigation_renderers'
#gem 'simple-navigation-bootstrap'
# Use Unicorn as the app server
# gem 'unicorn'
#geocoder
gem 'geocoder'
gem 'gmap_coordinates_picker', github: "gtrujillop/gmap_coordinates_picker"
#gem for countries
gem 'countries'
gem 'cities'
#jquery chosen
gem 'chosen-rails'
#for image handling
gem 'paperclip', '~> 4.2'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
# add pagination on pages
gem 'will_paginate'

group :test do
  gem 'shoulda'
end

gem 'codeclimate-test-reporter', group: :test, require: nil

group :development, :test do
  #gem 'webmock'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # Use mysql2 as the database for Active Record
  gem 'mysql2'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'rspec-rails', '~> 3.0'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'capybara', '~> 2.4.4'
  gem "capybara-webkit"
end

group :cucumber do
  gem 'cucumber'
end

group :production do
  gem 'pg',             '0.17.1'
  gem 'rails_12factor', '0.0.2'
end

