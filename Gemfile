source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails'
gem 'pg'
gem 'puma'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
gem 'active_model_serializers'
gem 'rack-cors', :require => 'rack/cors'

group :development, :test do
  gem 'rspec-rails'
  gem 'byebug', platform: :mri
  gem 'pry'
  gem 'database_cleaner'
end

group :development do
  gem 'web-console'
  gem 'listen'
end

group :test do
  gem 'shoulda-matchers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
