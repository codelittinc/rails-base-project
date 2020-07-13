# frozen_string_literal: true

source 'https://rubygems.org'

gem 'webpacker'
gem 'rails', github: 'rails/rails'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.12'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'devise'
gem 'gelf'

group :test do
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
end

group :development, :test do
  gem 'factory_bot_rails'
  gem 'faker', '~> 1.9', '>= 1.9.3'
  gem 'rubocop', require: false
  gem 'rubocop-rspec'
  gem 'scss_lint', require: false
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'rspec-rails', '~> 3.8'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'web-console', '>= 3.3.0'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
