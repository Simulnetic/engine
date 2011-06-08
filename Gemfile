source :rubygems

# add in all the runtime dependencies

gem 'rake', '0.8.7'

gem 'rails', '>= 3.0.8'

gem 'warden'
gem 'devise', '1.3.4'

gem 'mongoid', '~> 2.0.2'
gem 'bson_ext', '~> 1.3.0'
gem 'locomotive_mongoid_acts_as_tree', '0.1.5.7', :require => 'mongoid_acts_as_tree'
gem 'will_paginate'

gem 'haml', '3.1.2'
gem 'sass', '3.1.2'
gem 'locomotive_liquid', '2.2.2', :require => 'liquid'
gem 'formtastic', '~> 1.2.3'
gem 'inherited_resources', '~> 1.1.2'

gem 'rmagick', '2.12.2'
gem 'carrierwave', :git => 'git://github.com/did/carrierwave.git', :branch => 'mongoid'
# gem 'carrierwave', :path => '../gems/carrierwave_did'
# gem 'locomotive_carrierwave', '0.5.0.1.beta3', :require => 'carrierwave'

# gem 'custom_fields', '1.0.0.beta.15'
# gem 'custom_fields', '1.0.0.beta.15', :path => '../gems/custom_fields'
gem 'custom_fields', :git => 'git://github.com/locomotivecms/custom_fields.git'
gem 'fog', '0.8.2'
gem 'mimetype-fu'
gem 'actionmailer-with-request', :require => 'actionmailer_with_request'
gem 'heroku', '1.19.1'
gem 'httparty', '>= 0.6.1'
gem 'RedCloth', '4.2.7'
gem 'delayed_job', '2.1.4'
gem 'delayed_job_mongoid', '1.0.2'
gem 'rubyzip'
gem 'locomotive_jammit-s3', :require => 'jammit-s3'
gem 'SystemTimer', :platforms => :ruby_18

# The rest of the dependencies are for use when in the locomotive dev environment

group :development do
  # Using unicorn_rails instead of webrick (default server)
  gem 'unicorn'
end

group :test, :development do
  gem 'ruby-debug', :platforms => :mri_18
  gem 'ruby-debug19', :platforms => :mri_19

  gem 'bushido_stub', :git => 'git://github.com/did/bushido_stub.git'
  # :path => '../gems/bushido_stub'
  # gem 'bushido'
end

group :production do
  gem 'bushido'
end

group :test do
  gem 'autotest'
  gem 'ZenTest'
  gem 'growl-glue'
  gem 'rspec-rails', '2.3.1'
  gem 'factory_girl_rails'
  gem 'pickle'
  gem 'xpath',            :git => 'https://github.com/wunderbread/xpath.git'
  gem 'capybara'

  gem 'database_cleaner'
  gem 'cucumber', '0.8.5'
  gem 'cucumber-rails'
  gem 'spork'
  gem 'launchy'
  gem 'mocha', :git => 'git://github.com/floehopper/mocha.git'
end
