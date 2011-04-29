source 'http://rubygems.org'

gem 'rails',     :git => 'git://github.com/rails/rails.git'
gem 'arel',      :git => 'git://github.com/rails/arel.git'
gem 'rack',      "1.2.1", :git => 'git://github.com/rack/rack.git'
gem 'sprockets', :git => 'git://github.com/sstephenson/sprockets.git'
gem 'sqlite3'
gem 'thin'

gem 'high_voltage'

# Asset template engines
gem 'sass'
gem 'coffee-script'
gem 'uglifier'

group :test, :cucumber, :development do
  gem 'ruby-debug19', :require => 'ruby-debug'
  gem 'rspec-rails'
  gem 'shoulda'
  gem 'factory_girl_rails'
end

group :cucumber do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'cucumber-rails'
  gem 'cucumber'
  gem 'spork'
end
