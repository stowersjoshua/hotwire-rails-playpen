source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'rails', '~> 6.1.0'
gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'jbuilder', '~> 2.7'  # TODO: Deprecate this
gem 'redis', '~> 4.0'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'hotwire-rails'
gem 'haml-rails', "~> 2.0"
gem 'webpacker'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'listen', '~> 3.3'
  gem 'spring'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
