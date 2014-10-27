# encoding: utf-8

source 'https://rubygems.org'

gem 'berkshelf',  '~> 3.1'
gem 'chef',       '>= 11.14'

group :test do
  gem 'rake'
  gem 'chefspec',   '~> 4.1.1'
  gem 'foodcritic', '~> 4.0'
  gem 'thor-foodcritic'
  gem 'rubocop',    '~> 0.26.1'
  gem 'coveralls',  require: false
end

group :development do
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-kitchen'
  gem 'guard-rubocop'
  gem 'guard-foodcritic'
end

group :integration do
  gem 'test-kitchen', '~> 1.2'
  gem 'kitchen-vagrant'
  gem 'kitchen-sharedtests', '~> 0.2.0'
end

group :openstack do
  gem 'kitchen-openstack'
end
