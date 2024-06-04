source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.6'

gem "rails", "~> 7.1.3", ">= 7.1.3.3"
gem 'puma'
gem 'sass-rails'
gem 'webpacker'
gem 'turbolinks'
gem 'jbuilder'
gem 'bootsnap', require: false
gem 'importmap-rails'

group :development, :test do
  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console'
  gem 'rack-mini-profiler'
  gem 'listen'
  gem 'spring'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

group :production do
  gem 'pg', '1.2.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# Uncomment the following line if you're running Rails
# on a native Windows system:
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]