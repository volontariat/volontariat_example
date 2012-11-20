source "http://gems.github.com"
source 'https://rubygems.org'

gem 'rails', '3.2.8'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'voluntary'
gem 'voluntary_text_creation'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

gem "rack-cors", "~> 0.2.4", :require => "rack/cors"
gem "thin", "~> 1.3.1", :require => false
gem "settingslogic", :git => "https://github.com/binarylogic/settingslogic.git"
gem "acts-as-taggable-on", :git => "https://github.com/mbleigh/acts-as-taggable-on.git"
gem "acts_as_markup", :git => "git://github.com/vigetlabs/acts_as_markup.git"
gem "auto_html", :git => "git://github.com/Applicat/auto_html"
gem "recaptcha", :require => "recaptcha/rails"
gem "sinatra", :require => false
gem "addressable", "~> 2.2", :require => "addressable/uri"
gem "jasmine", :git => "https://github.com/pivotal/jasmine-gem.git"
group :development do
  gem "linecache", "0.46", :platforms => :mri_18
  gem "capistrano", :require => false
  gem "capistrano_colors", :require => false
  gem "capistrano-ext", :require => false
  gem "yard", :require => false
end

group :test do
  gem "cucumber-rails", "1.3.0", :require => false
  gem "rspec-instafail", ">= 0.1.7", :require => false
  gem "webmock", "~> 1.7", :require => false
  gem "simplecov", :require => false
end

group :development, :test do
  gem "debugger", :platforms => :mri_19
  gem "ruby-debug", :platforms => :mri_18
end

group :assets do
  gem "therubyracer", :platforms => :ruby
  gem "asset_sync", :require => nil
end

group :production do
  gem "fastercsv", "1.5.5", :require => false
  gem "rack-ssl", :require => "rack/ssl"
  gem "rack-rewrite", "~> 1.2.1", :require => false
  gem "rack-google-analytics", :require => "rack/google-analytics"
  gem "rack-piwik", :require => false
end
