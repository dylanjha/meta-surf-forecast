# frozen_string_literal: true
source 'https://rubygems.org'

ruby `cat .ruby-version`.strip

gem 'rails', '~> 5.0.0'

gem 'bootstrap', '~> 4.0.0.alpha3'
gem 'coffee-rails', '~> 4.2.0'
gem 'jquery-rails'
gem 'nokogiri'
gem 'pg', '~> 0.18'
gem 'puma'
gem 'slim-rails'
gem 'sprockets', '~> 4.0.0.beta2'
gem 'turbolinks'
gem 'uglifier', '>= 1.3.0'
gem 'chartkick'
gem 'friendly_id', github: 'norman/friendly_id'

group :development, :test do
  gem 'dotenv-rails'
end

group :development do
  gem 'guard'
  gem 'guard-bundler', require: false
  gem 'guard-rubocop', require: false
  gem 'spring'
  gem 'terminal-notifier-guard'
  gem 'web-console', '~> 3.0'
  gem 'invoker'
end

group :production do
  gem 'newrelic_rpm'
  gem 'rails_12factor'
end
