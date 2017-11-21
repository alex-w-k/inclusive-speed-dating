source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.4'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'redis', '~> 3.0'
gem 'kaminari'
gem 'materialize-sass'
gem 'devise'
gem 'omniauth-facebook'
gem 'figaro'

# gem 'bcrypt', '~> 3.1.7'

group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  gem 'shoulda-matchers'
  gem 'factory_bot_rails', '~> 4.0'
  gem 'pry-rails'
  gem 'pry'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

