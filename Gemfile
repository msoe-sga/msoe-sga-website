source 'https://rubygems.org'

gem 'jekyll'
gem 'rouge'
gem 'rubocop-jekyll', '~> 0.4.0'

group :jekyll_plugins do
  gem 'github-pages'
  gem 'jekyll-feed'
  gem 'jekyll-paginate'
  gem 'jekyll-sitemap'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem 'tzinfo'
  gem 'tzinfo-data'
end

# Performance-booster for watching directories on Windows
gem 'wdm', '~> 0.1.1', :install_if => Gem.win_platform?
