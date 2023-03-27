source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

gem "rails", "~> 7.0.4", ">= 7.0.4.2"
gem 'active_storage_validations'
gem 'mini_magick', '>= 4.9.5'
gem "image_processing"
gem 'bcrypt', '~> 3.1.7'
gem 'bootstrap'
gem 'jquery-rails'
gem "puma", "~> 5.0"
gem 'sass-rails'
gem 'webpacker'
gem 'turbolinks'
gem 'jbuilder'
gem 'bootsnap', require: false
gem "importmap-rails", "~> 1.1"
gem 'faker', "~> 3.1.1"
gem 'will_paginate', '~> 3.3'
gem 'will_paginate-bootstrap-style'

group :development, :test do
  gem 'sqlite3', "~> 1.4"
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
  gem 'rails-controller-testing'
  gem 'minitest'
  gem 'minitest-reporters'
  gem 'guard'
  gem 'guard-minitest'
end

group :production do
  gem 'pg'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# Uncomment the following line if you're running Rails
# on a native Windows system:
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
