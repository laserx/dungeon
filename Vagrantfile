# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

path = "#{File.dirname(__FILE__)}"

require 'yaml'
require path + '/scripts/Dungeonkeeper.rb'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  Dungeonkeeper.configure(config, YAML::load(File.read(path + '/Dungeonkeeper.yaml')))
end