source 'https://gems.ruby-china.com/'

gem "jekyll", "~> 4.3.2"

group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-archives"
  gem 'jekyll-loading-lazy'
  gem "rouge"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem 'wdm', '>= 0.1.0' if Gem.win_platform?

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "logger"