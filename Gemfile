source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'
gem 'rails', '~> 5.2.2'
gem 'pg', '~> 1.1', '>= 1.1.3'
gem 'puma', '~> 3.12'

# assets
gem 'webpacker'
gem 'bootsnap', '>= 1.1.0', require: false

# ops
gem 'config', '~> 1.7'
gem 'friendly_id', '~> 5.2', '>= 5.2.4'

# users & auth
gem 'devise', '~> 4.5'

group :development, :test do
  gem 'pry', '~> 0.11.3'
  gem 'rspec-rails', '~> 3.8'
  gem 'awesome_print', '~> 1.8'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'factory_bot', '~> 4.11', '>= 4.11.1'
end
