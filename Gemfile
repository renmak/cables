source 'https://rubygems.org'
ruby '2.1.5'

# BACK END
gem 'rails', '4.0.0'
gem 'pg', '~>0.16.0'
gem 'thin', '~>1.5.1'
gem 'newrelic_rpm'

# APPLICATION
gem 'spreadsheet', '~> 0.8.8'
# gem 'omniauth-att', :git => 'https://github.com/att-innovate/omniauth-att'
gem 'omniauth', '>= 1.0.0'
gem 'omniauth_crowd'
gem 'carrierwave', '~> 0.9.0'
gem 'fog', '~> 1.3.1'
#gem 'ransack', '~> 1.0.0'
gem 'workflow', '~> 1.0.0'
gem 'seed_dump'
gem 'tire'
gem 'yajl-ruby', require: 'yajl'

# FRONT END
gem 'slim-rails'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'jetpack-rails', '~> 0.11.1'
gem 'simple_form', '>= 3.0.0.beta1'
gem 'ejs', '>= 1.1.1'
gem 'redcarpet', '~> 3.0.0'

# CLOUD FOUNDRY SPECIFIC
gem 'rails_12factor'
gem 'foreman', :require=>false  #for managing processes on deployed server
gem 'rb-readline'
gem 'minitest-rails'
gem 'pry-rails'
gem 'pry'
#gem 'paper_trail', '~> 3.0.2'
gem 'capistrano', '~> 2.15', :require=>false
gem 'capistrano_colors'
gem 'rest-client', :require=>false

group :development, :test do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'quiet_assets'
  gem 'turn'
  gem 'guard-minitest'
  gem 'database_cleaner', '>= 1.1.1'
  gem 'fabrication'
  gem 'awesome_print'
  # gem 'capistrano', :require=>false
  # gem 'capistrano_colors'
  gem 'rvm-capistrano'
  gem 'capistrano-multistage'
  gem 'railroady'
end

# Gems for analytics on Jenkins
group :test do
  gem 'flog'
  gem 'brakeman'
  gem 'simplecov'
  gem 'simplecov-rcov'
end

