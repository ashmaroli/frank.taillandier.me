# frozen_string_literal: true

source "https://rubygems.org"

# gem "gsl" not supported by Netlify
gem "jekyll", :git => "https://github.com/ashmaroli/jekyll.git", :branch => "optima/benchmark"
gem "rouge", :git => "https://github.com/ashmaroli/rouge.git", :branch => "frozen-strings"
gem "memory_profiler"
gem "stackprof" unless Gem.win_platform?

group :jekyll_plugins do
  # gem "jekyll-paginate-v2"
  # gem "classifier-reborn"
  gem "jekyll-cloudinary"
  gem "jekyll-compose"
  gem "jekyll-feed"
  gem "jekyll-github-metadata"
  gem "jekyll-include-cache"
  gem "jekyll-last-modified-at"
  # gem "jekyll-mentions"
  gem "jekyll-microtypo"
  gem "jekyll-pwa-plugin"
  gem "jekyll-redirect-from"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-tidy"
  gem "jekyll-typogrify"
  gem "jekyll_reading_time", :git => "https://github.com/RouteMap/jekyll_reading_time.git", :branch => "master"
  gem "jekyll-mentioji", :git => "https://github.com/ashmaroli/jekyll-mentioji.git", :branch => "master"
  # gem "jemoji"
end

group :development do
  gem "launchy"
  gem "rake"
end

group :test do
  gem "html-proofer"
end
