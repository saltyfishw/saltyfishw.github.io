source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll" #, "~> 4.3.4"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima" #, "~> 2.5"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
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


# fix: csv was loaded from the standard library, but will no longer be part of the default gems starting from Ruby 3.4.0.
# You can add csv to your Gemfile or gemspec to silence this warning.
gem 'csv'

# install theme
gem 'jekyll-include-cache'
gem "minimal-mistakes-jekyll", group: :jekyll_plugins
gem "github-pages", group: :jekyll_plugins

# fix: /opt/homebrew/lib/ruby/gems/3.3.0/gems/safe_yaml-1.0.5/lib/safe_yaml/load.rb:22: warning: base64 was loaded from the standard library, 
# but will no longer be part of the default gems starting from Ruby 3.4.0.
# You can add base64 to your Gemfile or gemspec to silence this warning.
gem "base64"


# fix: Configuration file: /Users/wangke3/Code/GitHub/saltyfishw.github.io/_config.yml
# To use retry middleware with Faraday v2.0+, install `faraday-retry` gem
gem "faraday-retry"
