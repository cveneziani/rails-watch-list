source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.3.5"

# default
gem "rails", "~> 8.1.1"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 6.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis", "~> 4.0"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

gem "bootstrap", "~> 5.2"
gem "autoprefixer-rails"
gem "font-awesome-sass", "~> 6.1"
gem "simple_form", github: "heartcombo/simple_form"
gem "cloudinary"
gem "sassc-rails"

# own gems
gem "devise"

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "dotenv-rails"
end

group :development do
  gem "web-console"
end

gem 'rspec-rails', group: [ :test ]
gem 'rails-controller-testing', group: [ :test ]

gem "bundle", "~> 0.0.1"
gem "add", "~> 0.3.2"
gem "ostruct", "~> 0.6.0"
gem "logger", "~> 1.6"
gem "base64", "~> 0.2.0"
gem "bigdecimal", "~> 3.1"
gem "mutex_m", "~> 0.2.0"
