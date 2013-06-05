source 'https://rubygems.org'

gem 'rails', '3.2.12'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Choose your weapon
gem 'sqlite3'
#gem 'pg'
#gem 'mysql'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # You should use Node.js on production
  gem 'therubyracer', :platforms => :ruby
  gem "less-rails"
  gem "twitter-bootstrap-rails"

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'haml-rails'
gem 'rein'
gem 'devise'
gem 'cancan'
gem 'simple_form'
gem 'show_for'
gem 'inherited_resources'
gem 'localized_country_select'
gem "active_hash"
gem 'cocoon'
gem 'ransack'
gem 'kaminari'
gem 'carrierwave'
gem 'daemons'
gem 'delayed_job_active_record'
gem 'date_validator'
gem 'auditor'
gem 'prawn_rails'
# As gem is not updated since Jan-2012, git version in order to use not-so-new features as YARD integration.
gem "state_machine", :git => "https://github.com/pluginaweek/state_machine"
# Added to avoid an error in every rake execution caused by lib/tasks/doc.rake
# (at least until we figure out a cleaner solution)
gem "yard"

group :production do
  gem 'exception_notification'
end

group :development do
  gem "rspec-rails"
  gem "yard-activerecord"
  gem 'ruby-graphviz'
  gem "redcarpet", :require => false
end

group :test do
  gem "rspec-rails"
  gem "capybara"
  gem "capybara-email"
  gem "capybara-webkit"
  gem "shoulda-matchers"
#  gem "database_cleaner"
  gem "database_cleaner", :git => 'git@github.com:bmabey/database_cleaner.git'
#  gem "delorean"
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
