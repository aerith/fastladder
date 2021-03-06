source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'
gem 'mysql2'
gem 'haml'

# current release version has no `feed.description` method. this is why :git used
gem 'feedzirra', github: 'pauldix/feedzirra'
gem 'opml', github: 'fastladder/opml'
gem 'feed_searcher', '>= 0.0.6'
gem 'nokogiri'
gem "mini_magick"
gem "addressable", require: "addressable/uri"
gem "settingslogic"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  gem 'i18n-js', github: 'fnando/i18n-js'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'annotate'
  gem 'quiet_assets'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'factory_girl_rails'
  gem 'simplecov'
  gem 'simplecov-rcov'
  gem 'coveralls', require: false
end

group :test do
  gem 'webmock'
end

group :test, :development do
  gem 'konacha'
  gem 'poltergeist'
  gem 'sinon-rails'
end


# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
