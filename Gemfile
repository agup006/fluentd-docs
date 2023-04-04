source 'https://rubygems.org'

# https://devcenter.heroku.com/articles/ruby-versions
ruby '2.4.0'

gem 'sinatra', '2.2.3'
gem 'sinatra-assetpack', '0.3.5', :require => 'sinatra/assetpack'
gem 'rdiscount', '~> 2.2.0'
gem 'rest-client', '1.7.3'
gem 'sass'
gem 'haml', '>= 5.0.0'
gem 'coderay'
gem 'rack-codehighlighter'
gem 'sanitize', '>= 5.2.1'
gem 'jemalloc', '~> 0.1.8'
gem 'minitest'

# Compressor
gem 'yui-compressor', :require => 'yui/compressor'

# Webserver
gem 'unicorn', '~> 5.2.0'
gem 'unicorn-worker-killer', '~> 0.4.4'

# Addons
gem 'newrelic_rpm', '~> 3.5.3', '>= 3.5.3.25'
gem 'indextank', '~> 1.0.13'
gem 'airbrake', '~> 3.1.5'

# Dev
group :development do
  gem 'rake', '>= 12.3.3'
  gem 'shotgun', '~> 0.9', '>= 0.9.2'
end

# Production
group :production do
  gem 'rack-cache'
  gem 'dalli', '~> 3.2.3'
end
