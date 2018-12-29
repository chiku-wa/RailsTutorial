source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails'       , '5.2.2'
gem 'puma'        , '3.9.1'
gem 'sass-rails'  , '5.0.6'
gem 'uglifier'    , '3.2.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks'  , '5.0.1'
gem 'jbuilder'    , '2.6.4'

# SQLite3は開発環境でのみ使用する
group :development, :test do
  gem 'sqlite3','1.3.13'
  gem 'byebug' ,'9.0.6' , platforms: [:mri, :mingw, :x64_mingw]
end

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development do
  gem 'web-console', '3.5.1'
  gem 'listen', '3.1.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows環境ではzoneinfoが含まれていないため、「tzinfo-data」gemを追加する必要がある
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
