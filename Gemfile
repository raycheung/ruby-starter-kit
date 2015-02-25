source 'https://rubygems.org'

ruby '2.1.6'

# server layer
gem 'puma'

# data layer
gem "mongoid", "~> 4.0.0"
gem 'bson_ext'

# dev libs
gem 'activesupport'

# service integrations
gem 'raygun4ruby'
gem 'slack-notifier'

group :development, :test do
  gem 'pry-byebug'

  gem 'pronto'
  gem 'pronto-rubocop'
  gem 'pronto-brakeman'
  gem 'pronto-flay'
  gem 'pronto-reek'
end

group :test do
  gem 'database_cleaner'
  gem 'rspec', '~> 3.2'
end
