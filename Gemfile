source "https://rubygems.org"

# Jekyll
gem "jekyll", "~> 4.0.0"

# Site theme
gem "jekyll-theme-so-simple"

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jemoji'
  gem 'jekyll-paginate'
  gem 'jekyll-compose'
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
