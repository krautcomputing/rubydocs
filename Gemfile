source 'https://rubygems.org'

ruby '2.2.2'

gem 'rails', '~> 4.0.8'

# Load common gems
%w(
  common-gems/rails/Gemfile
  common-gems/redis/Gemfile
).each do |gemfile|
  instance_eval(File.read(gemfile))
end

gem 'sdoc',                               github: 'krautcomputing/sdoc', branch: 'a_instead_of_h1_fixup'
gem 'git',                                '~> 1.2'
gem 'high_voltage',                       '~> 2.0'
gem 'aws-sdk',                            '~> 1.42'
gem 'friendly_id',                        '~> 5.0'
gem 'rubyzip',                            '~> 1.1'
gem 'net-sftp',                           '~> 2.1'
gem 'render_anywhere',                    '~> 0.0', require: false

# Frontend
gem 'bootstrap-sass',                     '~> 3.0.2'
gem 'rails_bootstrap_navbar',             '~> 2.0'
gem 'font-awesome-rails',                 '~> 4.0'

source 'https://rails-assets.org' do
  gem 'rails-assets-jquery.smooth-scroll', '~> 1.4'
  gem 'rails-assets-jquery-cookie',        '~> 1.4'
end

group :test do
  gem 'rspec-rails',                      '~> 3.0'
  gem 'guard-rspec',                      '~> 4.2'
  gem 'factory_girl_rails',               '~> 4.4'
  gem 'database_rewinder',                '~> 0.2'
end
