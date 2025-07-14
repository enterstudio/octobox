source 'https://rubygems.org'
ruby '2.4.1'

gem 'rails', '~> 7.1', '>= 7.1.0'
gem 'bootstrap-sass'
gem 'jquery-rails', '>= 4.3.2'
gem 'kaminari', '>= 1.1.0'
gem 'local_time', git: 'https://github.com/twalpole/local_time', branch: 'turbolinks5'
gem 'octicons_helper', '>= 13.0.0'
gem 'octokit', '~> 4.8', '>= 4.8.0'
gem 'omniauth-github', '>= 2.0.0'
gem 'pg'
gem 'puma', '3.6.2'
gem 'sassc-rails', '>= 2.0.0'
gem 'turbolinks'
gem 'typhoeus', '>= 1.3.0'
gem 'uglifier'
gem 'pg_search', '>= 2.1.0'
gem 'jbuilder', '>= 2.6.4'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv-rails', '>= 2.7.6'
  gem 'rails-controller-testing', '>= 1.0.3'
end

group :test do
  gem 'rake', '~> 12.0'
  gem 'factory_girl', '>= 4.8.1'
  gem 'simplecov'
  gem 'codeclimate-test-reporter', '>= 1.0.9'
  gem 'webmock'
  gem 'mocha'
end

group :development do
  gem 'web-console', '>= 3.5.1'
  gem 'listen', '>= 3.2.0'
  gem 'rubocop', '>= 0.49.0', require: false
  gem 'spring'
  gem 'spring-watcher-listen', '>= 2.1.0'
end

group :production do
  gem 'newrelic_rpm'
  gem 'lograge', '>= 0.9.0'
  gem 'rails_safe_tasks'
  gem 'bugsnag'
  gem 'puma_worker_killer', '>= 0.3.1'
end
