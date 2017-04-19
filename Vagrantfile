# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntance version.
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "hubot-dev"
  config.vm.provision "shell", path: "provision.sh"
end