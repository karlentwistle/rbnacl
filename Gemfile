# frozen_string_literal: true

source "https://rubygems.org"

gemspec

group :development do
  gem "guard-rspec"
end

group :test do
  gem "coveralls", require: false
  gem "rbnacl-libsodium", ENV["LIBSODIUM_VERSION"]
  gem "rspec"
  gem "rubocop", "0.51.0"
end

group :development, :test do
  gem "rake"
end
