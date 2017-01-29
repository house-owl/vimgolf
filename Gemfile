source 'http://rubygems.org'
ruby '2.1.5'

gem 'rails', '3.1.0'
gem 'mongo', '1.1.5'
gem 'bson', '1.1.5'
gem 'bson_ext', '1.1.5'
gem 'mongoid', '2.0.0.beta.20'
gem 'json', '1.8.2'
gem 'memcachier'
gem 'dalli'
gem 'omniauth'
gem 'omniauth-twitter'
gem 'tweet-button'
gem 'newrelic_rpm'
gem 'unicorn'
gem 'rack-timeout'
gem 'rails3_serve_static_assets', github: 'heroku/rails3_serve_static_assets'
gem 'test-unit'

gem 'vimgolf', path: 'lib/vimgolf'
#
# Needed for the new asset pipeline
group :assets do
  # Leaving them out for now until we start using asset pipeline
  #gem 'sass-rails',   '~> 3.1.7'
  #gem 'uglifier',     '>= 1.0.3'
end

# jQuery is the default JavaScript library in Rails 3.1
# Leaving this out for now until we start using asset pipeline
#gem 'jquery-rails'

group :test, :development do
	%w[rspec rspec-core rspec-expectations rspec-mocks rspec-support rspec-rails].each do |lib|
	  gem lib, git: "git://github.com/rspec/#{lib}.git"
	end
  gem "shoulda-matchers"
  gem "database_cleaner", "1.5.1"
  gem 'simplecov', :require => false
  gem "codeclimate-test-reporter", "~> 1.0.0"
  gem "capybara"
  gem "pry-byebug"
  gem 'poltergeist'
  gem 'phantomjs', :require => 'phantomjs/poltergeist'
end
