source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem 'github-pages', group: :jekyll_plugins if !Gem.win_platform?

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?
gem 'jekyll', "< 3.9.2" # This line was added in order to pin jekyll to a stable version (it is broken >= 3.9.2).
gem "jekyll-paginate"
gem "jekyll-gist"
gem "jekyll-redirect-from"
gem "kramdown-parser-gfm"
gem "webrick"
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]
gem 'liquid', '4.0.4', platforms: [:mingw, :mswin, :x64_mingw]
# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins'
end
