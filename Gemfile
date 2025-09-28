source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run. When you
#  want to use a different version, change it below, save the file, then run:
#
#     bundle install
#
#     bundle exec jekyll serve
#
# If running plain vanilla GitHub Pages, you have to check here for versions:
#   https://pages.github.com/versions.json
#
# ... and unremark the following: 
# gem "github-pages", "~> 232", group: :jekyll_plugins
#
# This is the default theme for new Jekyll sites. You may change this to anything you like.
#gem "minima", "~> 2.5"
#
# We had it running with a custom theme:
# gem "jekyll-theme-pl2029_theme", git: "https://github.com/ProjectLiberty2029/PL2029_theme.git"
# 
# But we're going to run with asciidoc and argdown, so here are the gems we need. 
gem 'jekyll', '~> 4.3.0'
gem 'coderay', '~> 1.1.0'
gem 'rake-jekyll', '~> 1.1.0'
gem 'csv'
gem 'base64'
gem 'bigdecimal'

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-remote-theme" 
  gem "jekyll-asciidoc", "~> 3.0.0"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
