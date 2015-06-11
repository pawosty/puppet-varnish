source 'https://rubygems.org'

group :test do
  gem 'rake'
  gem 'puppet-lint'
  gem 'rspec-puppet', '~> 1.0.0'
  gem 'rspec-system-puppet'
  gem 'puppetlabs_spec_helper'
  gem 'puppet-syntax', '~> 1.2.0'
  gem 'facter', '~> 2.0.0'
  gem 'puppet', ENV['PUPPET_VERSION'] || '~> 3.7.0'
end

group :development do
  gem 'travis'
  gem 'travis-lint'
  gem 'vagrant-wrapper'
  gem 'puppet-blacksmith'
end
