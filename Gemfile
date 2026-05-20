source "https://rubygems.org"

gem "github-pages", "~> 232", group: :jekyll_plugins

# Force patched versions of vulnerable transitive dependencies
gem "nokogiri", ">= 1.18.8"
gem "rexml", ">= 3.3.9"
gem "addressable", ">= 2.8.7"
gem "activesupport", ">= 7.0.8.7"
gem "commonmarker", ">= 0.23.11"
gem "faraday", ">= 2.13.4"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end