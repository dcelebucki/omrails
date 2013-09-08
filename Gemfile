source 'https://rubygems.org'

gem 'rails', '4.0.0.rc2'
gem 'jquery-rails'

group :production do
	gem 'pg'
end
# Use sqlite3 as the database for Dev and Test Only
group :development, :test do
	gem 'sqlite3'
end

group :assets do
	# Use SCSS for stylesheets
	gem 'sass-rails', '~> 4.0.0.rc2'
	# Use Uglifier as compressor for JavaScript assets
	gem 'uglifier', '>= 1.3.0'
	# Use CoffeeScript for .js.coffee assets and views
	gem 'coffee-rails', '~> 4.0.0'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
