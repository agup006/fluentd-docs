source 'https://rubygems.org'

# https://devcenter.heroku.com/articles/ruby-versions
ruby '2.4.0'

gem 'sinatra', '1.3.6'
gem 'sinatra-assetpack', '0.3.5'
gem 'rdiscount', '~> 2.2.0'
gem 'rest-client', '1.2.0'
gem 'sass'
gem 'haml'
gem 'coderay'
gem 'rack-codehighlighter', '>= 0.5.1'
gem 'sanitize'
gem 'jemalloc', '~> 0.1.8'
gem 'minitest'

# Compressor
gem 'yui-compressor', :require => 'yui/compressor'

# Webserver
gem 'unicorn', '~> 5.2.0'
gem 'unicorn-worker-killer', '~> 0.4.4'

# Addons
gem 'newrelic_rpm', '~> 3.4.1'
gem 'indextank', '~> 1.0.12'
gem 'airbrake', '~> 3.1.5'

# Dev
group :development do
  gem 'rake'
  gem 'shotgun', '~> 0.9', '>= 0.9.2'
end

# Production
group :production do
  gem 'rack-cache', '>= 1.7.0'
  gem 'dalli', '~> 2.1.0'
end
