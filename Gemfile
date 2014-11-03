source 'https://rubygems.org'
fury_url = ENV['GEMFURY_URL'] # IDK how much we care whether people know the jsl-identity url, but we'll inject it just in case
source fury_url if fury_url

gem 'rails', '4.1.7'
gem 'sqlite3'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'haml'
#gem "compass", "0.12.5"
gem 'compass-rails'
#gem 'sass', '3.2.19'
gem 'redcarpet'
gem 'formtastic'
gem 'carrierwave'

gem 'jsl-identity', '= 0.0.7', require: 'jsl/identity' # for accessing user identities (comes from Gemfury)
gem 'deject'                                           # dependency injection

group :development, :test do
  gem 'rspec-rails', '~> 3.0.0'
  gem 'pry'
end