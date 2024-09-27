# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby File.read(File.expand_path("../.ruby-version", __FILE__)).chomp
gem "rails", "~> 6.0"

gem "autoprefixer-rails", "~> 10.0", ">= 10.2.5"

gem "barnes"
gem "bootsnap", "~> 1.12", require: false

gem "connection_pool", "~> 2.2"

gem "dalli", "~> 3.2"


gem "failbot_rails", "~> 0.7.0"

gem "faraday", "~> 1.0"
gem "faraday-http-cache", "~> 2.2"
gem "faraday_middleware", "~> 1.2"
gem "flipper", "~> 1.1.0"
gem "flipper-redis", "~> 1.1.0"
gem "flipper-ui", "~> 1.1.0"

gem "geo_pattern", "~> 1.4"
gem "google-api-client", "~> 0.53"
gem "googleauth", "~> 1.1"

gem "jquery-datetimepicker-rails", "~> 2.4", ">= 2.4.1.0"
gem "jquery-turbolinks",           "~> 2.1"

gem "active_model_serializers", "~> 0.10.12"
gem "api-pagination", "~> 4.8"
gem "kaminari", "~> 1.2"

gem "ims-lti", "~> 2.3.4"
gem "local_time", "~> 2.1"

gem "oauth",           "~> 1.0"
gem "octicons_helper", "~> 18.0"
gem "octokit", github: "octokit/octokit.rb"
gem "octopoller",      "~> 0.2"
gem "omniauth", "~> 2.1"
gem "omniauth-github", "~> 2.0"

gem "peek",                 "~> 1.1"
gem "peek-dalli",           "1.2.0"
gem "peek-gc",              "~> 0.0.2"
gem "peek-git",             "~> 1.0", ">= 1.0.2"
gem "peek-performance_bar", "1.3.1"
gem "peek-pg",              "~> 1.3"
gem "peek-sidekiq",         "1.0.4"
gem "pg",                   "~> 1.4"
gem "pg_search",            "~> 2.3"
gem "pry-byebug",           "~> 3.9"
gem "pry-rails",            "~> 0.3.9"
gem "puma",                 "~> 5.6"

gem "rack-canonical-host", "~> 0.2.3"
gem "rack-rewrite",        "~> 1.5.0"
gem "rack-timeout",        "~> 0.6", require: false
gem "rails-i18n",          "~> 7.0"
gem "redis-namespace",     "~> 1.8"
gem "ruby-progressbar",    "~> 1.11", require: false

gem "kramdown",            "~> 2.3.2"

gem "sass-rails", "~> 6.0"
gem "sidekiq",    "~> 6.5"
gem "sprockets",  "~> 4.1"

gem "turbolinks", "~> 5.2"
gem "typhoeus",   "~> 1.4"

gem "uglifier",      "~> 4.2"
gem "unicode-emoji", "~> 2.1"

group :development do
  gem "web-console", "~> 4.2"
end

group :development, :test do
  gem "awesome_print",            "~> 1.9", require: "ap"
  gem "bullet",                   "~> 7.0"
  gem "dotenv-rails",             "~> 2.8"
  gem "fuubar",                   "~> 2.5"
  gem "guard-rspec",              "~> 4.7", require: false
  gem "knapsack",                 "~> 1.21"
  gem "rails-controller-testing", "~> 1.0"
  gem "rspec-rails",              "~> 5.1"
  gem "rubocop",                  "~> 1.25", require: false
  gem "scss_lint",                "~> 0.59", require: false
  gem "spring",                   "~> 1.2"
  gem "spring-watcher-listen",    "~> 2.0"
  gem "terminal-notifier-guard",  "~> 1.6.2"
  gem "timecop",                  "~> 0.9.4"
end

group :production do
  gem "dogstatsd-ruby",     "~> 5.0.0"
  gem "lograge",            "~> 0.12"
  gem "newrelic_rpm",       "~> 8.7"
  gem "pinglish",           "~> 0.2.1"
  gem "puma_worker_killer", "~> 0.2"
  gem "rack-tracker",       "~> 1.13.0"
end

group :test do
  gem "action-cable-testing", "~> 0.6.0"
  gem "database_cleaner",     "~> 2.0"
  gem "factory_bot_rails",    "~> 6.0"
  gem "faker",                "~> 2.2"
  gem "shoulda-matchers",     "~> 5.0"
  gem "simplecov",            "~> 0.21"
  gem "vcr",                  "~> 6.1"
  gem "webmock",              "~> 3.14"
end
