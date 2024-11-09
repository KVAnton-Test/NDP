# frozen_string_literal: true
source "https://rubygems.org"

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
gem "minima", "2.4.1"

group :jekyll_plugins do
    gem "jekyll-autoprefixer"
    gem "jekyll-minifier"
    gem "jekyll-figure"
    gem "jekyll-loading-lazy"
    gem "jekyll-youtube"
end
