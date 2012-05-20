source :rubygems

# Server requirements
platforms :jruby do
  gem 'trinidad'
  gem 'jruby-openssl'
  gem 'jruby-rack'
end

platforms :ruby do
  gem 'thin'
end

# Project requirements
gem 'rake'
gem 'sinatra-flash', :require => 'sinatra/flash'

# Component requirements
# gem "therubyracer", :require => 'v8'
# gem 'rack-less'
# gem 'less'
gem 'haml'
gem 'rdiscount'

# Test requirements

# Padrino Stable Gem
gem 'padrino', '0.10.6'

# Or Padrino Edge
# gem 'padrino', :git => 'git://github.com/padrino/padrino-framework.git'

# Or Individual Gems
# %w(core gen helpers cache mailer admin).each do |g|
#   gem 'padrino-' + g, '0.10.6'
# end

# Require new relic as late as possible
gem 'padrino-rpm'
# gem 'newrelic_rpm'
