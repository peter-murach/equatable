source "https://rubygems.org"

gemspec

gem "json", "2.4.1" if RUBY_VERSION == "2.0.0"

group :development do
  if Gem::Version.new(RUBY_VERSION) >= Gem::Version.new("2.5.0")
    gem "coveralls_reborn", "~> 0.20.0"
    gem "simplecov", "~> 0.21.0"
  end
  gem "yardstick", "~> 0.9.9"
end
