source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in jekyll-academicons-svg.gemspec
gemspec

gem 'liquid'

if ENV["GH_PAGES"]
  gem "github-pages"
elsif ENV["JEKYLL_VERSION"]
  gem "jekyll", "~> #{ENV["JEKYLL_VERSION"]}"
end