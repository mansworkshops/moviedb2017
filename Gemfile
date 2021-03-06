source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# dotenv allows us to place environment variables in .env files.
gem 'dotenv-rails', groups: [:development, :test]

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'
# Bootsnap for faster application bootup time
gem 'bootsnap'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# FontAwesome provides a convenient icon font.
# http://fontawesome.io/
# https://github.com/bokmann/font-awesome-rails
gem 'font-awesome-rails'

# We're accessing an external API for movie posters, and we're
# using HTTParty as the client.
gem 'httparty'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri

  # RSpec is one of the most popular testing tools in the Ruby world.
  gem 'rspec-rails'

  # FactoryBot provides factory blueprints that help us easily generate records.
  gem 'factory_bot_rails'

  # This provides some convenience functionality for controller tests that was
  # extracted from Rails at some point.
  gem 'rails-controller-testing'

  # Faker provides convenience methods to generate all kinds of random data.
  gem 'ffaker'

  # Lovely Capybara will help us write feature/integration specs.
  gem 'capybara'

  # We'll use headless Chrome (through Selenium) for browser-based feature specs.
  gem 'selenium-webdriver'

  # webmock will prevent actual HTTP requests to external sites to be
  # executed during testing, and instead allow us to stub or mock them.
  gem 'webmock'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  # gem 'pg', '~> 0.18'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
