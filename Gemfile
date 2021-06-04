source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "jekyll", "~> 3.8.7"

gem "github-pages", group: :jekyll_plugins



group :jekyll_plugins do
    gem "jekyll-menus", "~> 0.6.0"
    gem 'jekyll-paginate-v2', github: 'sverrirs/jekyll-paginate-v2'
    gem "jekyll-paginate", "~> 1.1"
	 gem "jekyll-feed", "~> 0.12"
end



# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
