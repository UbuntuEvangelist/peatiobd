# encoding: UTF-8
# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo_slug| "https://github.com/#{repo_slug}" }

gem 'rails', '~> 6.1.7', '>= 6.1.7.3'
gem 'websocket-rails', github: 'moaa/websocket-rails', branch: 'sync_fixes'

gem 'rails-i18n', '~> 6.0.0'
gem 'puma', '~> 3.12.6'
gem 'mysql2', '~> 0.4.10'
gem 'redis-rails', '~> 5.0.2'

gem 'redis', '3.2.0'
gem 'rubocop-performance'

gem 'jbuilder', '~> 2.7.0'
gem 'oauth2', github: 'oauth-xx/oauth2'
gem 'omniauth', '~> 2.1.0'
gem 'omniauth-auth0', '~> 2.0.0', require: false
gem 'omniauth-google-oauth2', '~> 0.5.4', require: false
gem 'omniauth-barong', '~> 0.1.4', require: false
gem 'figaro', '~> 1.1.1'
gem 'hashie', '~> 3.5.7'
gem 'aasm', '~> 5.0.0'
gem 'bunny', '~> 2.11.0'
gem 'cancancan', '~> 2.2.0'
gem 'enumerize', '~> 2.2.2'
gem 'kaminari', '~> 1.2.1'
gem 'gon', '~> 6.4.0'
gem 'sassc-rails', '~> 1.3.0'
gem 'coffee-rails', '~> 4.2.2'
gem 'uglifier', '~> 4.1.17'
gem 'jquery-rails', '~> 4.4.0'
gem 'angularjs-rails', '~> 1.3.15'
gem 'bootstrap', '~> 4.1.3'
gem 'font-awesome-sass', '~> 5.2.0'
gem 'rbtree', '~> 0.4.2'
gem 'grape', '~> 1.1.0'
gem 'grape-entity', '~> 0.7.1'
gem 'grape-swagger', '~> 0.30.1'
gem 'grape-swagger-ui', '~> 2.2.8'
gem 'grape-swagger-entity', '~> 0.2.5'
gem 'grape_logging', '~> 1.8.1'
gem 'rack-attack', '~> 5.4.2'
gem 'easy_table', '~> 0.0.10'
gem 'faraday', '~> 0.14.0'
gem 'jwt', '~> 2.1.0'
gem 'email_validator', '~> 1.6.0'
gem 'validate_url', '~> 1.0.8'
gem 'clipboard-rails', '~> 1.7.1'
gem 'god', '~> 0.13.7', require: false
gem 'mini_racer', '~> 0.2.0', require: false
gem 'arel-is-blank', '~> 1.0.0'
gem 'sentry-raven', '~> 2.7.3', require: false
gem 'memoist', '~> 0.16.0'
gem 'method-not-implemented', '~> 1.0.1'
gem 'passgen', '~> 1.0.2'
gem 'validates_lengths_from_database', '~> 0.7.0'
gem 'jwt-multisig', '~> 1.0.2'
gem 'cash-addr', '~> 0.1.1', require: 'cash_addr'
gem 'digest-sha3', '~> 1.1.0'
gem 'scout_apm', '~> 2.4', require: false
gem 'peatio', '~> 0.4.3'

group :development, :test do
  gem 'faker',        '~> 1.8'
  gem 'pry-byebug',   '~> 3.6'
  gem 'quiet_assets', '~> 1.1', '>= 1.1.0'
  gem 'bullet', '~> 5.9', '>= 5.9.0'
end

group :development do
  gem 'annotate', '~> 2.7', '>= 2.7.5'
  gem 'ruby-prof', '~> 0.17.0', require: false
end

group :test do
  gem 'rspec-rails', '~> 3.8', '>= 3.8.2'
  gem 'rspec-retry',         '~> 0.5'
  gem 'rack_session_access', '~> 0.2', '>= 0.2.0'
  gem 'webmock',             '~> 3.3'
  gem 'database_cleaner',    '~> 1.6'
  gem 'mocha',               '~> 1.4', require: false
  gem 'factory_bot_rails', '~> 4.11', '>= 4.11.1'
  gem 'timecop',             '~> 0.9'
  gem 'rubocop-rspec',       '~> 1.30', require: false
end

# Load gems from Gemfile.plugin.
Dir.glob File.expand_path('../Gemfile.plugin', __FILE__) do |file|
  eval_gemfile file
end
