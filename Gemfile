source 'https://rubygems.org'
ruby '2.4.1'

gem 'rails', '~> 6.1', '>= 6.1.7.3'
gem 'bootstrap-sass', '>= 3.4.0'
gem 'jquery-rails', '>= 4.4.0'
gem 'kaminari', '>= 1.2.1'
gem 'local_time', git: 'https://github.com/twalpole/local_time', branch: 'turbolinks5'
gem 'octicons_helper'
gem 'octokit', '~> 4.7', '>= 4.7.0'
gem 'omniauth-github', '>= 2.0.0'
gem 'pg'
gem 'puma', '4.3.12'
gem 'sassc-rails'
gem 'turbolinks'
gem 'typhoeus'
gem 'uglifier'
gem 'pg_search'
gem 'jbuilder', '>= 2.6.4'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv-rails', '>= 2.7.6'
  gem 'rails-controller-testing', '>= 1.0.3'
end

group :test do
  gem 'rake', '~> 12.3', '>= 12.3.3'
  gem 'factory_girl'
  gem 'simplecov'
  gem 'codeclimate-test-reporter'
  gem 'webmock'
  gem 'mocha'
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'rubocop', '>= 0.49.0', require: false
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :production do
  gem 'newrelic_rpm'
  gem 'lograge', '>= 0.9.0'
  gem 'rails_safe_tasks'
  gem 'bugsnag'
  gem 'puma_worker_killer', '>= 0.1.1'
end
