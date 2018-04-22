source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.5.0'

gem 'rails', '~> 5.2.0'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'devise'
gem 'rubocop', require: false

group :development, :test do
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 3.7'
end

group :test do
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'
  gem 'factory_bot'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'simplecov', require: false
  gem 'cucumber-rails', require: false
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'annotate', git: 'https://github.com/ctran/annotate_models.git'
end
