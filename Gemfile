source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Asset template engines
gem 'compass', :git => "git://github.com/chriseppstein/compass.git", :branch => "rails31"
# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem "haml-rails"
gem 'jquery-rails'

gem 'airbrake'
gem 'unicorn'
gem 'omniauth', :git => 'git://github.com/intridea/omniauth.git'
gem "mongo_mapper"
gem "bson_ext"
gem "i18n"
gem "twitter"
gem "pony"
gem "rdiscount"
gem "ostatus", "~>0.0.9"
gem "osub", "~>0.0.6"
gem "opub"
gem "redfinger"
gem "nokogiri"
gem "tzinfo"
gem "rsa"
gem "exceptional"
gem "newrelic_rpm"
gem "draper"
gem "twitter-text"

# background job queue
gem "delayed_job", :git => "git://github.com/collectiveidea/delayed_job.git", :tag => "v2.1.4"
gem "delayed_job_mongo_mapper", :git => "git://github.com/earbits/delayed_job_mongo_mapper.git"
gem "whenever"

group :development, :test do
  gem "database_cleaner"
  gem "fabrication"
  gem "capybara"
  gem "show_me_the_cookies"
  gem "rocco", :git => "git://github.com/rtomayko/rocco.git"
  gem "pygmentize"
  gem "mocha"
  gem "vcr"
  gem "simplecov", "~> 0.4.0", :require => false
  gem "launchy"
end

group :test do
  gem "webmock"
end
