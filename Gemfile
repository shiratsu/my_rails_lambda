source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails'

gem 'aws-sdk-ssm'
gem 'active_model_serializers'
gem 'closure-compiler', '~> 1.1', '>= 1.1.12'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'mysql2'
gem 'nokogiri'
gem 'dotenv-rails', require: 'dotenv/rails-now'
gem 'jbuilder'
gem 'lamby', require: false
gem 'sass-rails', '>= 6'
gem 'mini_racer', platforms: :ruby
gem 'turbolinks', '~> 5'
gem 'redis', '~> 4.3.1'
gem 'redis-store'
gem 'redis-actionpack'

gem 'active_decorator'
gem 'activerecord-import'
gem 'amoeba'
gem 'autoprefixer-rails'
gem 'axlsx'
gem 'aws-sdk-polly'
gem 'browser'
gem 'cancancan'
gem 'caxlsx_rails'
gem 'chosen-rails', '~> 1.5', '>= 1.5.2'
gem 'clockwork'
gem 'clockwork_web'
gem 'cocoon'
gem 'webpacker', github: "rails/webpacker"
gem 'daemons', '~> 1.3.1'
gem 'mongoid'
gem 'bson_ext', '~> 1.5.1'
gem 'delayed_job', '~> 4.1', '>= 4.1.5'
gem 'delayed_job_web', '~> 1.4', '>= 1.4.3'
gem 'delayed_job_mongoid', :git => 'git@github.com:geekcojp/delayed_job_mongoid.git', :branch => "master"
gem 'devise'
gem 'devise_masquerade', '~> 0.6.1'
gem 'dropzonejs-rails'
gem 'enum_help'
gem 'exception_notification'
gem 'fullcalendar-rails'
gem 'google-apis-drive_v3'
gem 'google-api-client', require: 'google/apis/calendar_v3'
gem 'ice_cube'
gem 'json'
gem 'puma'
gem 'kaminari'
gem 'letter_opener'
gem 'letter_opener_web'
gem 'lodash-rails', '~> 3.10', '>= 3.10.1' # for ie8
gem 'mechanize'
gem 'mimemagic'
gem 'mixpanel-ruby'
gem 'momentjs-rails'
gem 'natto'
gem 'oauth2', "1.4.4"
gem 'paper_trail', "11.1.0"
gem 'paper_trail-association_tracking'
gem 'paperclip'
gem 'parallel'
gem 'paranoia'
gem 'prawn'
gem 'prawn-table'
gem 'ragoon', git: 'git@github.com:geekcojp/ragoon.git'
gem 'ransack'
gem 'remotipart'
gem 'rest-client', '~> 2.0'
gem 'ruby-duration'
gem 'ruby_outlook', :git => 'git@github.com:shiratsu/ruby_outlook.git', :branch => "master"
gem 'seed-fu'
gem 'webdrivers', '~> 4.0'
gem 'semantic-ui-sass', git: 'https://github.com/doabit/semantic-ui-sass.git'
gem 'slack-notifier'
gem 'telephone_number'
gem 'toastr-rails'
gem 'tribute', '~> 3.1', '>= 3.1.3.0'
gem 'turnout'
gem 'twilio-ruby', '>= 5.31.1'
gem 'whenever'
gem 'ancestry', '~> 3.0', '>= 3.0.2'
gem 'acts_as_list', '~> 0.9.15'
gem 'uglifier', '~> 4.1', '>= 4.1.16'
gem 'google_drive'
gem 'retryable', '~> 3.0', '>= 3.0.2'
gem 'rqrcode', '~> 0.10.1'
gem 'yen', '~> 0.0.2'
gem 'rounding', '~> 1.0', '>= 1.0.1'
gem 'roo-xls'
gem 'roo', '~>2.8'
#gem 'ar-octopus', :git => 'git@github.com:geekcojp/octopus.git', :branch => "master"
gem 'brakeman'
gem "net-sftp", '~> 3.0.0'
gem 'spreadsheet'

gem 'sinatra', require: false

gem 'mini_magick'
gem 'intl-tel-input-rails'
gem 'bigdecimal', '1.3.5'
gem "aws-sdk-s3", require: false
gem 'image_processing'
gem 'active_storage_validations'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

source 'http://insecure.rails-assets.org' do
  gem 'rails-assets-riot', '~> 3.6.1'
end

group :development do
  gem 'web-console'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'foreman', require: false
  gem 'guard'
  gem 'guard-livereload', '~> 2.4', require: false
  gem 'i18n_generators'
  gem 'listen', '~> 3.0.5'
  gem 'rack-dev-mark'
  gem 'rails-i18n'
  gem 'rubocop', require: false
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'memory_profiler'
  gem 'view_source_map'
end

group :development, :test do
  gem 'byebug'
  gem 'pry-byebug'
  # gem 'pry-coolline', github: 'owst/pry-coolline', branch: 'support_new_pry_config_api'
  gem 'pry-rails'
  gem 'pry-stack_explorer'
  gem 'rspec-rails'
  gem 'guard-rspec', require: false
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'

  gem 'database_rewinder'
  gem 'factory_bot_rails'
  gem 'ffaker'
  gem 'rspec-its'
  gem 'rspec-request_describer'
  gem 'rspec_junit_formatter'

  # waiting for v3.1.3
  # see: https://github.com/thoughtbot/shoulda-matchers/pull/965
  gem 'shoulda-matchers', git: 'https://github.com/thoughtbot/shoulda-matchers.git', branch: 'rails-5'

  gem 'simplecov', require: false
  gem 'timecop'
  gem 'rails-controller-testing'
  gem 'rspec-collection_matchers'
end

group :production do
  gem 'lograge'
end
