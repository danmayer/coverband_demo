source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0'

# Moved above coverband so I can debug coverband during rails startup
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry-byebug', platforms: [:mri, :mingw, :x64_mingw]
  # gem 'pry-rails'
end

# You must require awk explicitly if you want to use S3 reports
# which are less common than the web reports
# gem 'aws-sdk-s3'
# gem 'aws-sdk', '~> 1'

gem 'pg', platforms: [:mri, :mingw, :x64_mingw]
gem 'activerecord-jdbcpostgresql-adapter', platforms: [:jruby]

# Use Puma as the app server
gem 'puma', '~> 4.3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby
gem 'material_icons'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# When explaining observability
gem 'newrelic_rpm'
gem "sentry-raven"
# exploring dumping all lines
gem 'binding_dumper'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

gem 'sidekiq'

# show a gem that is never used but loaded
# gem 'rainbows'

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  # gem 'web-console', '>= 3.3.0', platforms: [:mri, :mingw, :x64_mingw]
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop'

  # Spring makes it hard to debug and develop coverband locally
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  # gem 'spring'
  # gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15', '< 4.0'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
  gem 'minitest-ci'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'nokogiri', '>= 1.10.4'


# move coverband to current development branch to see if that has an impact
# gem 'coverband', '>= 4.2.2.rc.1', git: 'https://github.com/danmayer/coverband.git', branch: 'view_tracker', require: false
# gem 'coverband', '>= 4.2.2.rc.1', git: 'https://github.com/danmayer/coverband.git', branch: 'master', require: false

# Current Coverband Release
gem 'coverband', '= 5.1.0'

# Current Coverband development release candidate
# gem 'coverband', '= 4.2.5.r'

# For local gem file testing
# gem 'coverband', '>= 5.0.3', path: '../coverband'
