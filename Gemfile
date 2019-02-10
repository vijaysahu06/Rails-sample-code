source 'https://rubygems.org'
ruby "2.4.1"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1', '>= 5.1.4'
# Use postgresql as the database for Active Record
gem 'pg'
# Use Puma as the app server
gem 'puma'
# Use SCSS for stylesheets
gem 'sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
gem 'rails-erd'
# Use CoffeeScript for .coffee assets and views
# gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# gem 'active_model_serializers', github: 'rails-api/active_model_serializers', branch: '0-8-stable'
gem 'active_model_serializers', '~> 0.10.0'
gem 'paper_trail'
gem 'activerecord-diff'
gem 'devise'
gem 'pundit' # Note this gem is overridden and code can be found in namespaced_pundit
gem 'spreadsheet'
gem 'to_xls'
gem 'roo'
gem 'auto_strip_attributes'
gem 'kaminari'
gem 'twilio-ruby'
gem 'aws-sdk-s3'
gem 'aasm'
gem 'msg91ruby'
gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby'
gem 'razorpay'
gem 'braintree', :git => 'https://github.com/braintree/braintree_ruby'
gem 'pdfkit'
gem 'wkhtmltopdf-binary'
gem 'to_words'
gem 'geocoder'
gem 'delayed_job_active_record'
gem "breadcrumbs_on_rails"
# gem 'delayed_job_web'
gem 'offsite_payments'
gem 'sourcify'
gem 'paranoia'
gem 'jwt'
gem 'grim'
gem 'gruff'
gem 'geokit-rails'
gem 'rack-timeout'
gem 'figaro'
gem 'amoeba'
gem "omniauth-google-oauth2"
gem 'omniauth-facebook'
gem 'google-api-client'
gem 'rmagick'

gem 'fusioncharts-rails'
gem "cocoon"
# Gem to upload files
gem 'remotipart'
gem 'carrierwave'
gem 'fog'
gem 'friendly_id'
gem 'any_login'
gem 'wicked'
gem 'simple_command'
gem 'rack-attack'
gem 'exception_notification'
# Use Exception Handler for Implementation of custom error page
gem 'exception_handler'
gem 'bootsnap', require: false

# Gem for editor
gem 'ckeditor'
gem 'mini_magick'

# Gems needs to be integrated
# gem 'jwt_keeper'
# gem 'has_scope'
# gem 'validates'
# gem 'peek'

gem 'public_activity'
gem 'rack-cors', require: 'rack/cors'


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'pry'
  # gem 'letter_opener'
  # gem 'brakeman', require: false
  # gem 'meta_request'
  # gem 'bullet'
  gem 'rspec-rails', '~> 3.8'
  gem 'factory_bot_rails'
  gem 'shoulda-matchers', '4.0.0.rc1'
  gem 'rails-controller-testing'
  gem 'simplecov', require: false
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  gem 'guard'
  gem 'guard-livereload'

  gem 'rails-erd', require: false

  # For security vulnerabilities
  gem 'brakeman', require: false

  gem 'foreman', require: false
  gem 'letter_opener'
  gem 'rubocop', require: false

  # Profiling
  gem 'rack-mini-profiler' # For database profiling
  gem 'memory_profiler' # For memory profiling
  # For call-stack profiling flamegraphs
  gem 'flamegraph'
  gem 'stackprof'
end

# UI Dependencies
gem 'jquery-rails'
gem 'bootstrap-sass'
gem 'font-awesome-rails'
gem 'jquery-validation-rails'
gem 'underscore-rails'
gem 'select2-rails' # Dont use this gem as bower dependency because it is making root path to load exactly three times.
gem 'browser-timezone-rails'

source 'https://rails-assets.org' do
  gem 'rails-assets-jquery-ui'
  gem 'rails-assets-ez-plus'
  gem 'rails-assets-toastr'
  gem 'rails-assets-webcamjs'
  gem 'rails-assets-datatables.net-bs'
  gem 'rails-assets-fusioncharts'
  gem 'rails-assets-perfect-scrollbar'
  gem 'rails-assets-js-cookie'
  gem 'rails-assets-malihu-custom-scrollbar-plugin'
  gem 'rails-assets-moment'
  gem 'rails-assets-bootstrap-datetimepicker-3'
  gem 'rails-assets-jquery-mousewheel'
  gem 'rails-assets-bootstrap-star-rating'
  gem 'rails-assets-arboshiki--lobibox'
end

gem 'rollbar'
