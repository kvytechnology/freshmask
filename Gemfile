source 'https://rubygems.org'

ruby '2.3.4'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.3'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.5'

gem 'spree', '~> 3.2.0'
gem 'spree_auth_devise', '~> 3.2'
gem 'spree_gateway', '~> 3.2'
gem 'spree_i18n', github: 'spree-contrib/spree_i18n'
gem 'spree_recently_viewed', github: 'spree-contrib/spree_recently_viewed'
gem 'spree_reviews', github: 'spree-contrib/spree_reviews'

group :development do
  gem 'listen'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
