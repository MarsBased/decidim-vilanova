source 'https://rubygems.org'

ruby '2.4.0'

gem 'decidim', git: 'https://github.com/AjuntamentdeBarcelona/decidim.git'

gem 'puma', '~> 3.0'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'decidim-dev', git: 'https://github.com/AjuntamentdeBarcelona/decidim.git'
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console'
  gem 'listen', '~> 3.1.0'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'faker', '~> 1.7.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]