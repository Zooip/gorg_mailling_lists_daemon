source 'https://rubygems.org'

ruby File.read(".ruby-version").strip

gem 'gorg_service', '~> 6.0'

gem 'gram_v2_client', git: "https://github.com/gadzorg/gram2_api_client_ruby"

gem 'google-api-client'
gem 'googleauth'

gem 'redis'

group :test do
  gem "simplecov"
  gem "codeclimate-test-reporter", "~> 1.0.0"
end

group :development, :test do
  gem 'webmock'

  gem 'rspec'
  gem 'rspec-collection_matchers'
  gem 'bogus'
  gem 'faker'
end
