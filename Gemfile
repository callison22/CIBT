source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'jquery-rails'
gem 'bootstrap-sass', '~> 2.3.1.3'
gem 'devise'
gem "gibbon"
gem 'simple_form'
gem "rspec-rails", :group => [:development, :test]
gem "database_cleaner", :group => :test
gem "email_spec", :group => :test
gem "cucumber-rails", :group => :test, :require => false
gem "launchy", :group => :test
gem "capybara", :group => :test
gem "factory_girl_rails", :group => [:development, :test]
gem "cancan"
gem "rolify"
gem "quiet_assets", :group => :development
gem "figaro"
gem "better_errors", :group => :development
gem "binding_of_caller", :group => :development, :platforms => [:mri_19, :rbx]

group :production do
	gem 'pg'
end	

group :development, :test do
	gem 'sqlite3'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

