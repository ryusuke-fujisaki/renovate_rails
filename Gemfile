source 'https://rubygems.org'
git_source(:github) { |repo| 'https://github.com/#{repo}.git' }
ruby '3.3.8'

gem 'active_decorator'
gem 'active_flag'
gem 'active_hash', '~> 3.1.1'
gem 'active_model_serializers'
gem 'activerecord-import'
gem 'ahoy_email', '~> 1.1.1' # open(開封のtrack)メソッドを使いたい場合はversion up不可
gem 'ahoy_matey', '~> 3.0.5'
gem 'api-pagination'
gem 'asset_sync'
gem 'aws-sdk-cloudwatch', require: false
gem 'aws-sdk-elasticloadbalancingv2', require: false
gem 'aws-sdk-lambda', require: false
gem 'aws-sdk-s3', require: false
gem 'aws-sdk-ses', require: false
gem 'aws-sdk-ssm', require: false
gem 'bcrypt', '~> 3.1.7'
gem 'bcrypt_pbkdf', '>= 1.0', '< 2.0'
gem 'bootsnap', '>= 1.1.0'
gem 'bootstrap', '~> 4.3.1'
gem 'breadcrumbs_on_rails'
gem 'browser'
gem 'cancancan'
gem 'carrierwave'
gem 'caxlsx'
gem 'caxlsx_rails'
gem 'chunky_png'
gem 'combine_pdf'
gem 'counter_culture'
gem 'cssbundling-rails'
gem 'devise'
gem 'devise_invitable'
gem 'devise-security'
gem 'devise-two-factor', '~> 4.1.0'
gem 'discard'
gem 'ed25519', '>= 1.2', '< 2.0'
gem 'era_ja'
gem 'exception_notification'
gem 'faraday'
gem 'faraday_middleware'
gem 'fog-aws'
gem 'font_awesome5_rails'
gem 'hashid-rails', '~> 1.0'
gem 'hexapdf'
gem 'imgkit'
gem 'intercom-rails'
gem 'jsbundling-rails'
gem 'json-schema'
gem 'kaminari'
gem 'mysql2', '>= 0.4.4', '< 0.6.0'
gem 'omniauth-oauth2'
gem 'omniauth-rails_csrf_protection'
gem 'paranoia'
gem 'pdfkit'
gem 'pdf-reader'
gem 'pwned'
gem 'rack-proxy', '~> 0.7.7'
gem 'rails', '~> 7.2.2'
gem 'rails_autolink'
gem 'rails-i18n'
gem 'ransack'
gem 'recaptcha'
gem 'redis', '~> 4.8.1'
gem 'redis-namespace'
gem 'redis-rails'
gem 'rqrcode-rails3'
gem 'rubyXL'
gem 'rubyzip'
gem 'sassc-rails', '~> 2.1'
gem 'seed-fu', '~> 2.3'
# バージョン固定中
# これをあげるとrackupが1.0.1にあがり、specが大量に落ちるようになった
gem 'sentry-rails', '5.19.0'
gem 'settingslogic'
gem 'sidekiq', '~> 6.5.12'
gem 'sidekiq-cron'
gem 'simple_form'
gem 'simple_token_authentication'
gem 'slack-notifier'
gem 'state_machines'
gem 'state_machines-activerecord'
gem 'stripe'
gem 'summernote-rails', '~> 0.8.12.0'
gem 'typhoeus'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'utf8-cleaner'
gem 'validates_email_format_of', '~> 1.7.2'
gem 'virtus'
gem 'wareki'
gem 'wicked'
gem 'wicked_pdf'
gem 'wkhtmltoimage-binary', '0.12.4'
gem 'wkhtmltopdf-binary'
gem 'zip_kit'
# 最新の1.8.3を使うと、csvのgemがインストールされ不具合が起きるため1.8.2で固定する
# https://github.com/alexreisner/geocoder/blob/master/CHANGELOG.md
gem 'geocoder', '<= 1.8.2'

group :development, :test, :staging, :mufg_staging do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'brakeman', require: false
  gem 'bundler-audit'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'pry'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'reek'
  gem 'rubocop-airbnb'
  gem 'rubocop-checkstyle_formatter', require: false
end

group :development, :test do
  gem 'awesome_print'
  gem 'bullet'
  gem 'figaro'
  gem 'knapsack_pro'
  gem 'puma'
end

group :development do
  gem 'erb_lint'
  gem 'listen', '~> 3.5.1'
  gem 'ruby-jmeter'
  gem 'scss_lint'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem 'web-console', '>= 3.3.0'
end

group :development, :staging, :mufg_staging do
  gem 'capistrano'
  gem 'capistrano-bundler'
  gem 'capistrano-nodenv'
  gem 'capistrano-passenger'
  gem 'capistrano-rails'
  gem 'capistrano-rbenv'
  # 3.0.0にあげるとデプロイ時にsidekiqの処理が実行されないため、2.3.1で固定
  # TODO: 3.0.0以上でも動くように修正する
  gem 'capistrano-sidekiq', '~> 2.3.1'
  gem 'capistrano-yarn'
  gem 'derailed_benchmarks'
  gem 'elbas'
end

group :test do
  gem 'capybara'
  gem 'capybara-playwright-driver'
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'rspec'
  gem 'rspec_junit_formatter'
  gem 'rspec-rails'
  gem 'rspec-retry'
  gem 'selenium-webdriver'
  gem 'shoulda-matchers'
  gem 'simplecov'
  gem 'simplecov-json'
  gem 'simplecov-rcov'
  gem 'stripe-ruby-mock'
  gem 'sucker_punch'
  gem 'test-prof', '~> 1.0'
  gem 'webmock'
end

group :staging, :production, :mufg_staging, :mufg_enhance, :mufg_production do
  gem 'newrelic_rpm'
end
