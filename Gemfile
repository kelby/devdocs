source 'https://rubygems.org'
ruby '2.3.0'

gem 'rake'
gem 'thor'
gem 'pry', '~> 0.10.0'
gem 'activesupport', '~> 4.2', require: false
gem 'yajl-ruby', require: false

group :app do
  gem 'rack'
  gem 'sinatra'
  gem 'sinatra-contrib'
  gem 'thin'
  gem 'sprockets'
  gem 'sprockets-helpers'
  gem 'erubis'
  gem 'browser'
  gem 'sass'
  gem 'coffee-script'
end

group :production do
  gem 'uglifier'
end

group :development do
  gem 'better_errors'

  gem 'capistrano', '~> 3.6'
  # gem 'capistrano-rails', '~> 1.2'
  gem 'capistrano3-puma'
  gem 'capistrano-rbenv', '~> 2.0'
  gem 'capistrano-bundler', '~> 1.2'
  # gem 'capistrano-secrets-yml', '~> 1.0.0'
end

group :docs do
  gem 'typhoeus'
  gem 'nokogiri'
  gem 'html-pipeline'
  gem 'progress_bar', require: false
  gem 'unix_utils', require: false
  gem 'tty-pager', require: false
end

group :test do
  gem 'minitest'
  gem 'rr', require: false
  gem 'rack-test', require: false
end

if ENV['SELENIUM'] == '1'
  gem 'capybara'
  gem 'selenium-webdriver'
end
