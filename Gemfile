source 'https://rubygems.org'

ruby '3.0.2'

##-- base gems for rails --##
gem 'rack-cors', require: 'rack/cors'
gem 'rails', '>= 6.1.7.5'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

##-- rails application helper gems --##
gem 'acts-as-taggable-on', '>= 9.0.0'
gem 'attr_extras'
gem 'browser'
gem 'hashie'
gem 'jbuilder', '>= 2.11.3'
gem 'kaminari', '>= 1.2.2'
gem 'responders', '>= 3.1.0'
gem 'rest-client'
gem 'telephone_number'
gem 'time_diff'
gem 'tzinfo-data'
gem 'valid_email2', '>= 4.0.1'
# compress javascript config.assets.js_compressor
gem 'uglifier'
##-- used for single column multiple binary flags in notification settings/feature flagging --##
gem 'flag_shih_tzu'
# Random name generator for user names
gem 'haikunator'
# Template parsing safely
gem 'liquid'
# Parse Markdown to HTML
gem 'commonmarker'
# Validate Data against JSON Schema
gem 'json_schemer'
# Rack middleware for blocking & throttling abusive requests
gem 'rack-attack'

##-- for active storage --##
gem 'aws-sdk-s3', require: false
gem 'azure-storage-blob', require: false
gem 'google-cloud-storage', require: false
gem 'image_processing'

##-- gems for database --#
gem 'groupdate', '>= 5.2.3'
gem 'pg'
gem 'redis'
gem 'redis-namespace'
# super fast record imports in bulk
gem 'activerecord-import', '>= 1.3.0'

##--- gems for server & infra configuration ---##
gem 'dotenv-rails', '>= 2.8.0'
gem 'foreman'
gem 'puma'
gem 'rack-timeout'
gem 'webpacker', '~> 5.4', '>= 5.4.1'
# metrics on heroku
gem 'barnes'

##--- gems for authentication & authorization ---##
gem 'devise', '>= 4.8.1'
gem 'devise-secure_password', '~> 2.0'
gem 'devise_token_auth', '>= 1.2.1'
# authorization
gem 'jwt'
gem 'pundit', '>= 2.1.1'
# super admin
gem 'administrate', '>= 0.17.0'

##--- gems for pubsub service ---##
# https://karolgalanciak.com/blog/2019/11/30/from-activerecord-callbacks-to-publish-slash-subscribe-pattern-and-event-driven-design/
gem 'wisper', '2.0.0'

##--- gems for channels ---##
# TODO: bump up gem to 2.0
gem 'facebook-messenger'
gem 'telegram-bot-ruby'
gem 'twilio-ruby', '~> 5.32.0'
# twitty will handle subscription of twitter account events
# gem 'twitty', git: 'https://github.com/chatwoot/twitty'
gem 'twitty'
# facebook client
gem 'koala'
# slack client
gem 'slack-ruby-client'
# for dialogflow integrations
gem 'google-cloud-dialogflow'

##--- gems for debugging and error reporting ---##
# static analysis
gem 'brakeman'
gem 'ddtrace'
gem 'scout_apm'
gem 'sentry-rails', '>= 4.6.5'
gem 'sentry-ruby'
gem 'sentry-sidekiq'

##-- background job processing --##
gem 'sidekiq'
# We want cron jobs
gem 'sidekiq-cron'

##-- Push notification service --##
gem 'fcm'
gem 'webpush'

##-- geocoding / parse location from ip --##
# http://www.rubygeocoder.com/
gem 'geocoder'
# to parse maxmind db
gem 'maxminddb'

# to create db triggers
gem 'hairtrigger', '>= 0.2.25'

gem 'procore-sift', '>= 1.0.0'

group :development do
  gem 'annotate', '>= 3.2.0'
  gem 'bullet', '>= 6.1.5'
  gem 'letter_opener'
  gem 'web-console', '>= 4.2.0'

  # used in swagger build
  gem 'json_refs'

  # When we want to squash migrations
  gem 'squasher'
end

group :test do
  # Cypress in rails.
  gem 'cypress-on-rails', '~> 1.0'
  # fast cleaning of database
  gem 'database_cleaner', '>= 2.0.2'
end

group :development, :test do
  gem 'active_record_query_trace'
  gem 'bundle-audit', require: false
  gem 'byebug', platform: :mri
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'listen'
  gem 'mock_redis'
  gem 'pry-rails'
  gem 'rspec-rails', '~> 5.0.2'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', '>= 2.12.0', require: false
  gem 'rubocop-rspec', require: false
  gem 'seed_dump'
  gem 'shoulda-matchers', '>= 5.1.0'
  gem 'simplecov', '0.17.1', require: false
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'webmock'
end
