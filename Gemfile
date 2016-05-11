source 'https://rubygems.org'

ruby '2.2.3'
gem 'rails', '3.2.21'
gem 'scoped_search', '~> 2.6.0'
gem 'RedCloth', '~> 4.2.9'
gem 'dynamic_form', '~> 1.1.4'
gem 'jquery-rails', '~> 3.0.4'
gem 'thin', '~> 1.5.0'

group :production do
  gem 'pg', '~> 0.15.0'
end

group :test do
  gem 'test-unit'
  gem 'shoulda-matchers'
end

group :development, :test do
  gem 'sqlite3'
  gem 'factory_girl'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'coveralls', require: false
end

group :assets do
  gem 'sass-rails',   '~> 3.2.6'
  gem 'coffee-rails', '~> 3.2.2'

  gem 'uglifier', '>= 1.3.0'
end
