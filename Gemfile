source 'https://rubygems.org'

gem 'rails', '4.0.0.beta1'

gem 'activesupport', '4.0.0.beta1'

group :production do
     gem 'mysql'
end
group :development, :test do
    gem 'sqlite3-ruby', :require => 'sqlite3'
end

group :assets do
  gem 'sass-rails',   '~> 4.0.0.beta1'
  gem 'coffee-rails', '~> 4.0.0.beta1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', platforms: :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.0.1'


gem 'activeresource', git: 'git://github.com/rails/activeresource', require: 'active_resource'

gem 'multi_json'

group :development do
	gem 'pry'
	gem 'pry-doc'
	gem 'pry-rails'
end
