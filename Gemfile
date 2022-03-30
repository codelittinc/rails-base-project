# frozen_string_literal: true

source 'https://rubygems.org'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'devise'
gem 'gelf'
gem 'jbuilder', '~> 2.7'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.3'
gem 'rails', '>= 6'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'
gem 'webpacker'

group :test do
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
end

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker', '~> 1.9', '>= 1.9.3'
  gem 'rspec-rails', '~> 3.8'
  gem 'rubocop', require: false
  gem 'rubocop-rspec'
  gem 'scss_lint', require: false
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end
