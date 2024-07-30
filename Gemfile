source "https://rubygems.org"

# Use GitHub Pages gem
gem "github-pages", ">= 228", group: :jekyll_plugins
gem "jekyll-github-metadata"

# Add necessary plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jemoji"
end

# Add webrick to support running Jekyll server
gem "webrick", "~> 1.7"

# Add csv and base64 to handle warnings
gem "csv"
gem "base64"

# Platform-specific gems
platforms :jruby do
  gem "http_parser.rb", "~> 0.6.0"
end

gem "tzinfo", ">= 1", "< 3"
gem "tzinfo-data"
