source 'https://rubygems.org'
ruby '2.3.4'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'jbuilder', '~> 2.5'
gem 'devise_token_auth'
gem 'rack-cors', require: 'rack/cors'

group :development, :test do
 gem 'pry'
 gem 'pry-byebug'
 gem 'rspec-rails'
 gem 'shoulda-matchers'
 gem 'factory_bot_rails'
 gem 'rails_12factor'
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
