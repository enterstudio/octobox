source 'https://rubygems.org'
ruby '2.4.1'

gem 'rails', '~> 7.0', '>= 7.0.8.1'
gem 'bootstrap-sass'
gem 'jquery-rails', '>= 4.3.2'
gem 'kaminari', '>= 1.1.0'
gem 'local_time', git: 'https://github.com/twalpole/local_time', branch: 'turbolinks5'
gem 'octicons_helper', '>= 4.0.1'
gem 'octokit', '~> 4.7'
gem 'omniauth-github', '>= 1.3.0'
gem 'pg'
gem 'puma', '3.6.2'
gem 'sassc-rails', '>= 2.0.0'
gem 'turbolinks'
gem 'typhoeus'
gem 'uglifier'
gem 'pg_search'
gem 'jbuilder'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv-rails', '>= 2.7.6'
  gem 'rails-controller-testing', '>= 1.0.3'
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
  gem 'web-console', '>= 3.5.1'
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
