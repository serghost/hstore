source 'https://rubygems.org'

# Backend
gem 'rails', '~> 5.0.0'
gem 'rails-i18n', '~> 5.0.0'

gem 'puma', '~> 3.0'

# Auth* related
gem 'devise'
gem 'devise-i18n'
gem 'rolify'

# Frontend related
gem 'sassc-rails' # Using C implementation
gem 'autoprefixer-rails'
gem 'uglifier', '>= 1.3.0'
# gem 'jquery-rails' # using bower
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'haml'
gem 'haml-rails'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

group :development, :test do
  gem 'sqlite3'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'capistrano',         require: false
  gem 'capistrano-rvm',     require: false
  gem 'capistrano-rails',   require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano3-puma',   require: false
end
