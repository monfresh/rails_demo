# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby "2.6.3"

gem "autoprefixer-rails"
gem "bootsnap", require: false
gem "bourbon", ">= 5.0.1"
gem "delayed_job_active_record"
gem "faraday"
gem "fast_jsonapi"
gem "figaro"
gem "high_voltage"
gem "neat", ">= 3.0.1"
gem "oj"
gem "pg"
gem "puma"
gem "rack-canonical-host"
gem "rack-timeout"
gem "rails", "~> 5.2.3"
gem "recipient_interceptor"
gem "sassc-rails"
gem "simple_form"
gem "sprockets", ">= 3.0.0"
gem "title"
gem "typhoeus"
gem "tzinfo-data", platforms: %i[mingw x64_mingw mswin jruby]
gem "uglifier"
gem "webpacker"

group :development do
  gem "bummr", require: false
  gem "fasterer", require: false
  gem "listen"
  gem "rack-mini-profiler", require: false
  gem "spring"
  gem "spring-commands-rspec"
  gem "web-console"
end

group :development, :test do
  gem "awesome_print"
  gem "bullet"
  gem "bundler-audit", ">= 0.5.0", require: false
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "pry-byebug"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.6"
  gem "rubocop", "~> 0.70", require: false
  gem "rubocop-performance"
  gem "rubocop-rails"
  gem "suspenders"
end

group :test do
  gem "capybara"
  gem "formulaic"
  gem "launchy"
  gem "shoulda-matchers"
  gem "simplecov", require: false
  gem "timecop"
  gem "webdrivers"
  gem "webmock"
end
