source :rubygems
gem "bundler"

gem "rails", "~> 3.0.0"
gem "rake", "0.8.7"
gem "gem_plugin"
gem "mime-types"
gem "fastthread"
gem "nokogiri"
gem "httpauth"
gem "acts_as_taggable_on_steroids"
gem "ruby-openid"
gem "ruby-openid-apps-discovery"
gem "delayed_job"
gem "dynamic_form"
gem "aws-sdk"
gem 'delayed_job_active_record'
gem "daemons"
gem 'jquery-rails', '>= 1.0.12'
gem 'pivotal_git_scripts'
gem 'httpi'

group :postgres do
  gem "pg"
end

group :mysql do
  gem 'mysql2', '< 0.3'
end

group :thin do
  gem "thin"
end


group :development do
  gem "heroku"
  gem "sqlite3-ruby", "1.3.1"
  gem "capistrano"
  gem "capistrano-ext"
  gem "soloist"
  gem "rvm"
  gem "fog"
end

group :test do
  gem "jasmine", "1.0.1.1"
  gem "headless", "0.1.0"
  gem "timecop"
end

group :test, :development do
  gem "rspec-rails", "~> 2.9.0"
  gem "webrat"
end
