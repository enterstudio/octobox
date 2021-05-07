source 'https://rubygems.org'
ruby '2.4.1'

gem 'rails', '~> 5.2', '>= 5.2.4.6'
gem 'bootstrap-sass'
gem 'jquery-rails', '>= 4.3.1'
gem 'kaminari'
gem 'local_time', git: 'https://github.com/twalpole/local_time', branch: 'turbolinks5'
gem 'octicons_helper', '>= 3.0.1'
gem 'octokit', '~> 4.7'
gem 'omniauth-github'
gem 'pg'
gem 'puma', '3.6.2'
gem 'sassc-rails', '>= 1.3.0'
gem 'turbolinks'
gem 'typhoeus'
gem 'uglifier'
gem 'pg_search'
gem 'jbuilder'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv-rails', '>= 2.2.2'
  gem 'rails-controller-testing', '>= 1.0.1'
end

group :test do
  gem 'rake', '~> 12.0'
  gem 'factory_girl'
  gem 'simplecov'
  gem 'codeclimate-test-reporter'
  gem 'webmock'
  gem 'mocha'
end

group :development do
  gem 'web-console', '>= 3.5.0'
  gem 'listen'
  gem 'rubocop', require: false
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :production do
  gem 'newrelic_rpm'
  gem 'lograge', '>= 0.9.0'
  gem 'rails_safe_tasks'
  gem 'bugsnag'
  gem 'puma_worker_killer'
end
