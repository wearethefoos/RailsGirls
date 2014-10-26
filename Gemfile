source 'https://rubygems.org'


gem 'rails', '4.1.6'
gem 'sqlite3'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'

# Use Bootstrap when we generate stuff
gem 'bootstrap-generators', '~> 3.2.0'
# WYSIWYG Editor
gem "wysiwyg-rails"
# Popular icons font
gem "font-awesome-rails"
# Draper for decorating objects!
gem 'draper'

# We use FriendlyId for slugs
#
# See: https://github.com/norman/friendly_id
gem 'friendly_id', '~> 5.0.0'

# Devise is the standard for authentication.
gem 'devise'

group :development do
  gem 'spring'
end

group :development, :test do
  gem 'spring-commands-rspec'
  gem 'rspec-rails', '~> 3.0.2'
  gem 'guard-rspec'
  gem 'rb-fsevent' if `uname` =~ /Darwin/
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'shoulda-matchers', require: false
end
