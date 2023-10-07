source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.2'

# Rails and Web Server
gem 'rails', '~> 7.0.7', '>= 7.0.7.2'
gem 'puma', '~> 5.0'

# Asset Pipeline
gem 'sprockets-rails'

# Database
gem 'pg', '~> 1.1'

# JavaScript and Frontend
gem 'importmap-rails'
gem 'turbo-rails'
gem 'stimulus-rails'
gem 'jbuilder'

# Background Jobs (if needed)
# gem 'sidekiq'

# Authentication and Authorization
gem 'devise'
gem 'cancancan'

# Testing
group :development, :test do
  gem 'rspec-rails'
  gem 'web-console'
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
  gem 'rubocop', '>= 1.0', '< 2.0'
end

# Development and Debugging
group :development do
  gem 'bullet'
  # gem 'rack-mini-profiler'
  # gem 'spring'
  # gem 'sassc-rails'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Caching for Boot Time
gem 'bootsnap', require: false
