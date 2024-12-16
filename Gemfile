source "https://rubygems.org"

# GitHub Pages-specific configuration
gem "github-pages", group: :jekyll_plugins

# Optional: Add other plugins supported by GitHub Pages, if needed
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows and JRuby-specific configuration
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]