source "https://rubygems.org"

gem "jekyll", "~> 4.3.0"
gem "jekyll-email-protect"

group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "jekyll-paginate"
  gem "jekyll-github-metadata"
  gem "jekyll-coffeescript"
  gem "jekyll-commonmark-ghpages"
  gem "jekyll-gist"
  gem "jekyll-relative-links"
  gem "jekyll-optional-front-matter"
  gem "jekyll-readme-index"
  gem "jekyll-default-layout"
  gem "jekyll-titles-from-headings"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1.0.0"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows.
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions are not supported on JRuby.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]