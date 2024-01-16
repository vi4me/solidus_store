source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "rails", "~> 7.0.4"
# gem "ruby-vips"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem 'solidus', github: 'solidusio/solidus'
gem "jbuilder"
gem "redis", "~> 4.0"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false
gem "solidus_admin", "~> 0.0.0"
gem "solidus_auth_devise", "~> 2.5"
gem "solidus_paypal_commerce_platform", "~> 1.0"
gem "responders"
gem "canonical-rails"
gem "solidus_support"
gem "truncate_html"
gem "view_component", "~> 3.0"
gem "tailwindcss-rails"

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "capybara-screenshot", "~> 1.0"
  gem "database_cleaner", "~> 2.0"
end

group :development, :test do
  gem "rspec-rails"
  gem "rails-controller-testing", "~> 1.0.5"
  gem "rspec-activemodel-mocks", "~> 1.1.0"
  gem "factory_bot", ">= 4.8"
  gem "factory_bot_rails"
  gem "ffaker", "~> 2.13"
  gem "rubocop", "~> 1.0"
  gem "rubocop-performance", "~> 1.5"
  gem "rubocop-rails", "~> 2.3"
  gem "rubocop-rspec", "~> 2.0"
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end
