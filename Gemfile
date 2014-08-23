source 'http://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.1.0'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'spring',        group: :development
## gem 'bootstrap-sass', github: 'thomas-mcdonald/bootstrap-sass', branch: '3'
gem 'bootstrap-sass', '~> 3.2.0'
gem 'devise', '~> 3.0.3'
# gem 'paperclip', '~> 3.0'
gem 'paperclip', github: 'thoughtbot/paperclip'
gem 'aws-sdk', '~> 1.20.0'
gem 'masonry-rails', '~> 0.2.0'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]


group :development, :test do
     gem 'sqlite3'
end

group :production do
     gem 'pg'
     gem 'rails_12factor'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
