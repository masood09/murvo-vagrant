VAGRANTFILE_API_VERSION = "2"

path = "#{File.dirname(__FILE__)}"

require 'yaml'
require path + '/scripts/murvo.rb'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  Murvo.configure(config, YAML::load(File.read(path + '/Murvo.yaml')))
end
