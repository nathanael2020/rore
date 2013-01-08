source 'http://rubygems.org'

## Bundle rails:
gem 'rails', '~> 3.2.6'

group :assets do
  #gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier', '>= 1.0.3'
end
  gem 'sass-rails', "  ~> 3.2.3"

gem "activemerchant", '~> 1.17.0'#, :lib => 'active_merchant'
gem 'authlogic', "3.0.3"
gem 'bluecloth',     '~> 2.1.0'
gem 'cancan', '~> 1.6.7'
gem 'compass', '~> 0.12.rc.0'
gem 'compass-rails'
#  gem 'dalli', '~> 1.0.2'

gem 'dynamic_form'
gem "friendly_id", "~> 3.3"
gem 'haml',  ">= 3.0.13"#, ">= 3.0.4"#, "2.2.21"#,
gem "jquery-rails"

gem 'nested_set', '~> 1.7.0'
#gem "nifty-generators", :git => 'git://github.com/drhenner/nifty-generators.git'
gem 'nokogiri', '~> 1.5.0'
gem 'paperclip', '~> 2.8.0'
gem 'prawn', '~> 0.12.0'

gem "rails3-generators", :git => "https://github.com/neocoin/rails3-generators.git"
gem "rails_config"
gem 'rmagick',    :require => 'RMagick'

gem 'rake', '~> 0.9.2'
gem 'state_machine', '~> 1.1.2'
#gem 'sunspot_solr'
#gem 'sunspot_rails', '~> 1.3.0rc'
gem 'will_paginate', '~> 3.0.0'

#gem 'memcache-client', '~> 1.8.5'
#group :production do
  #gem 'mysql2', '~> 0.3.10'
#end

gem 'pg'

group :development do
  #gem 'sqlite3'
  #gem 'awesome_print'
  #gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git'
  gem "autotest-rails-pure"

  gem "rails-erd"
  gem "debugger"

  # YARD AND REDCLOTH are for generating yardocs
  gem 'yard'
  gem 'RedCloth'
end
group :test, :development do
  gem "rspec-rails", "~> 2.8.0"
  gem 'capybara', "~> 1.1"#, :git => 'git://github.com/jnicklas/capybara.git'
  gem 'launchy'
  gem 'database_cleaner'
end

group :test do
  gem 'factory_girl', "~> 3.3.0"
  gem 'factory_girl_rails', "~> 3.3.0"
  gem 'mocha', '~> 0.10.0', :require => false
  gem 'rspec-rails-mocha'
  gem "rspec",        "~> 2.8.0"

  gem "rspec-core",         "~> 2.8.0"
  gem "rspec-expectations", "~> 2.8.0"
  gem "rspec-mocks",        "~> 2.8.0"
  gem 'email_spec'

  gem "faker"
  gem "autotest", '~> 4.4.6'
  gem "autotest-rails-pure"

  if RUBY_PLATFORM =~ /darwin/
    gem "autotest-fsevent", '~> 0.2.5'
  end
  gem "autotest-growl"
  #gem "redgreen"
  gem "ZenTest", '4.6.2'

end
