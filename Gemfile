source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.1'
gem 'thor', '0.19.1'

# db
gem 'mysql2', '~> 0.4.5'
gem 'puma', '~> 3.0'

# model
gem 'enumerize'
gem "paranoia", "~> 2.2"
gem "auto_strip_attributes"

# ui
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'kaminari', '~> 0.17.0'
gem 'bootstrap-kaminari-views'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.5.1'
gem 'haml-rails', '~> 0.9.0'
gem 'browser'

# form
gem 'cocoon'

# tools
gem 'bcrypt', '~> 3.1.7'
gem 'envyable', '~> 0.2.0'
gem 'seed-fu', '~> 2.3', '>= 2.3.5'
gem 'unobtrusive_flash', '~> 3.1'
gem 'octokit', '~> 4.0'
gem 'redcarpet'

# file upload
gem 'carrierwave', '~> 0.10.0'
gem "mini_magick"
gem 'file_validators', '~> 2.0', '>= 2.0.2'
gem "fog"

# auth
gem 'cancancan', '~> 1.10'
gem 'devise', '~> 4.2'
gem 'devise-bootstrap-views'
gem 'rolify'
gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-google-oauth2'
gem 'omniauth-naver'
gem 'twitter'
gem 'google-api-client'

# notification
gem 'postmark-rails', '~> 0.12.0'
gem 'slack-notifier', '~> 1.4'
gem 'exception_notification', '~> 4.1', '>= 4.1.4'
gem 'premailer-rails', '~> 1.9', '>= 1.9.2'

# scheduler
gem 'sidekiq', '~> 4.1'
gem 'sidekiq-cron', '~> 0.4.5'
gem 'sidekiq-unique-jobs', '~> 4.0', '>= 4.0.16'
gem 'redis', '~> 3.2', '>= 3.2.2'
gem 'redis-namespace', '~> 1.5', '>= 1.5.2'

group :development, :test do
  gem 'letter_opener_web'
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
