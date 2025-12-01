source "https://rubygems.org"

# Use the GitHub Pages gem to match the build environment on GitHub
gem "github-pages", group: :jekyll_plugins

# Remote theme plugin is included in github-pages already,
# so you usually don't need to add jekyll-remote-theme explicitly.
# (If you really want to, you can, but it's redundant.)

# Optional extra plugins (jekyll-feed is already bundled in github-pages,
# so you can actually remove this block entirely if you want)
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows / JRuby bits (you can keep these as-is)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]