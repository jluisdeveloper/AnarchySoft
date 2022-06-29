source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.3"
gem "sprockets-rails"
gem "pg", "~> 1.4"
gem "puma", "~> 5.6"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis", "~> 4.7"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

gem "bootsnap", require: false
gem "brakeman"
gem "bundler-audit"
gem "rubocop-rails"

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "rspec-rails"
  gem "rubocop-rspec"
end

group :development do
  gem "web-console"
  gem "rack-mini-profiler"

end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
