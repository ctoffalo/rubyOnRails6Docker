# frozen_string_literal: true

source "https://www.rubygems.org"

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.1"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'

gem "rails", "~> 6.0.3", ">= 6.0.3.6"
gem 'sassc-rails'

# Install webpack
gem 'webpacker'

# Rack-based rate limit
gem "rack-attack"
# Use postgres as the database for Active Record
gem "pg"

# Use Puma as the app server
gem "puma", "~> 4.1"
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.7'

## Cron section

gem "whenever"
gem "tzinfo"

# #####End cron section #####


# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.4.2", require: false

gem "sidekiq", "~> 6.1.3"
gem "redis"

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem "rack-cors"

group :staging do
  gem "byebug"
end
group :development, :test do
  # debugging gems
  gem "pry"
  gem "pry-doc"
  gem "pry-byebug"
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]

  gem "factory_bot", "~> 6.1"
  gem "factory_bot_rails", "~> 6.1"
  gem "simplecov", require: false
end

group :development do
  gem "listen", "~> 3.2"
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "rubocop", "~> 0.91.0"
  gem "rubocop-packaging", "~> 0.5.0"
  gem "rubocop-rails", "~> 2.8"
  gem "rubocop-performance", "~> 1.8"
  gem "letter_opener"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "jwt", "~> 2.2"

gem "bcrypt", "~> 3.1"

gem "activerecord-import"

gem "aasm"

gem "cancancan"

gem "database_cleaner-active_record", "~> 1.8"

gem "httparty"

gem "premailer-rails"

gem "noticed"

gem "phonelib"

gem "twilio-ruby"

# Settings
gem "ledermann-rails-settings"

gem "webpush"
