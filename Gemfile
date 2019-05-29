source 'https://rubygems.org'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end
ruby '2.3.3'
gem 'rails', '~> 5.1.7'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '2.15'
  gem 'selenium-webdriver'
end
group :development do
  gem 'web-console', '>= 3.3.0'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'administrate'
gem 'bootstrap', '~> 4.0.0'
gem 'bourbon'
gem 'devise'
gem 'devise_invitable'
gem 'high_voltage'
gem 'jquery-rails'
gem 'pg', '~> 0.18'
gem 'pundit'
gem 'binding_of_caller'
group :development do
  gem 'better_errors'
  gem 'hub', :require=>nil
  gem 'rails_apps_pages'
  gem 'rails_layout'
end
group :development, :test do
  gem 'pry-rails'
  gem 'pry-rescue'
  gem 'rubocop'
end
