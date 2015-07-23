source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'jekyll'
gem 'jemoji'

group :jekyll_plugins do
  gem 'jekyll-picture-tag', '~> 0.2.3'
  gem 'jekyll-sitemap'
  gem 'jekyll-mentions'
end
