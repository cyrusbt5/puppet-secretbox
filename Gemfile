source 'https://rubygems.org'

gem 'rake', '< 11.0'
gem 'puppet-lint'
gem 'rspec-puppet'
gem 'rspec-system-puppet'
gem 'puppetlabs_spec_helper'
gem 'travis'
gem 'travis-lint'
gem 'puppet-syntax'
gem 'puppet', ENV['PUPPET_VERSION'] || '~> 3.3.0'
gem 'vagrant-wrapper'
gem 'puppet-blacksmith', :platforms => [:ruby_19, :ruby_20]
gem 'rubocop', '0.41.2', :require => false if Gem::Version.new(RUBY_VERSION.dup) < Gem::Version.new('2.0.0')
gem 'rubocop', :require => false if Gem::Version.new(RUBY_VERSION.dup) >= Gem::Version.new('2.0.0')
gem 'json', '1.8.3', :require => false if Gem::Version.new(RUBY_VERSION.dup) < Gem::Version.new('2.0.0')
gem 'json', :require => false if Gem::Version.new(RUBY_VERSION.dup) >= Gem::Version.new('2.0.0')

