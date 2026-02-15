source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "github-pages", group: :jekyll_plugins

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
# 仅保留 GitHub Pages 支持的插件，否则 Actions 会报 "can't satisfy your Gemfile's dependencies"
group :jekyll_plugins do
  # gem "jekyll-archives"
  # jekyll-feed、jekyll-sitemap 已包含在 github-pages 中，无需重复
  # gem 'hawkins'  # 非 GitHub Pages 支持，会导致 build 失败
end
