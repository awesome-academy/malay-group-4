source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.7.1"

gem "config", "~> 2.2", ">= 2.2.1"
gem "rails", "~> 6.0.3", ">= 6.0.3.2"
gem "mysql2", ">= 0.4.4"
gem "bcrypt", "~> 3.1", ">= 3.1.16"
gem "faker", "~> 2.14"
gem "i18n", "~> 1.8", ">= 1.8.5"
gem "puma", "~> 4.1"
gem "sass-rails", ">= 6"
gem "bootsnap", ">= 1.4.2", require: false
gem "jbuilder", "~> 2.7"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 4.0"
gem "bootstrap-sass", "~> 3.4", ">= 3.4.1"
gem "jquery-rails", "~> 4.4"
gem "kaminari", "~> 0.16.3"
gem "kaminari-bootstrap", "~> 3.0", ">= 3.0.1"
gem "figaro", "~> 1.2"


group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "rubocop", "~> 0.74.0", require: false
  gem "rubocop-rails", "~> 2.3.2", require: false
end

group :development do
  gem "listen", "~> 3.2"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
