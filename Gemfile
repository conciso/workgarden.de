source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "github-pages", "~> 207"

group :noupdate do
  gem "ffi", "= 1.12.1"
  gem "nokogiri", "1.13.2"
end

gem 'jekyll', '>=3.9', '<4'

group :jekyll_plugins do
  gem "jekyll-sitemap", "~> 1.2"
  gem "jekyll-seo-tag", "~> 2.5"
  gem "jekyll-analytics"
  gem "jekyll_picture_tag", "< 1.10.3"
end
