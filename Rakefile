# -*- ruby -*-

require 'rubygems'
require 'hoe'

Hoe.plugins.delete :rubyforge
Hoe.plugin :minitest
Hoe.plugin :gemspec # `gem install hoe-gemspec`
Hoe.plugin :git     # `gem install hoe-git`

Hoe.spec 'fibur' do
  developer('Aaron Patterson', 'aaron@tenderlovemaking.com')
  self.version = '1.0.0'
  self.readme_file   = 'README.rdoc'
  self.history_file  = 'CHANGELOG.rdoc'
  self.extra_rdoc_files  = FileList['*.rdoc']
  self.spec_extras = {
    :required_ruby_version => '>= 1.9.2'
  }
end

# vim: syntax=ruby
