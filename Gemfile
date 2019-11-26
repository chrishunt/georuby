source 'https://rubygems.org'

gem 'rake'

group :test do
  gem 'dbf', '2.0.7'
  gem 'json'
  gem 'nokogiri'

  gem 'rspec'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-rubocop'

  if ENV['CI']
    gem 'coveralls', require: false
  end
end
