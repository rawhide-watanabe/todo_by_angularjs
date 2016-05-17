# A sample Gemfile
source "https://rubygems.org"

# rails
gem 'rails', '4.2.0'

# db
gem 'mysql2'

# rails-assets
source 'https://rails-assets.org' do
  gem 'rails-assets-angular', "=1.3.17"
  gem 'rails-assets-angular-animate', "=1.3.17"
  gem 'rails-assets-angular-sanitize', "=1.3.17"
  gem 'rails-assets-angular-mocks' # TODO 後でdevelopment groupへ移動する
  gem 'rails-assets-angular-ui-router', "=0.2.15"
  gem 'rails-assets-ng-sortable', "=1.2.2"
  gem 'rails-assets-lodash', "=3.10.0"
  gem 'rails-assets-ngDialog', "=0.4.0"
  gem 'rails-assets-ng-file-upload', "=6.0.3"
  gem 'rails-assets-color', "=2.5.0"
end

# js
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem "coffee-script-source", "~> 1.8.0"
gem 'therubyracer',  platforms: :ruby
gem "jquery-slick-rails"
gem 'smokejs_rails'
gem 'angulartics-rails'

# api
gem 'grape', '~> 0.9.0'
gem 'grape-entity'
gem 'grape_logging'

gem 'grape-swagger'
gem 'rack-cors', :require => 'rack/cors'

group :development, :test, :staging do
  gem 'byebug'
  gem 'web-console', '~> 2.0'

  gem 'metric_fu'

  gem 'github-markup', '= 0.7.5', group: :doc
  gem 'github-markdown', '= 0.5.3', group: :doc

  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'rails-erd'

  gem 'awesome_print'
  gem 'hirb-unicode'
  gem 'rails_best_practices'
end
