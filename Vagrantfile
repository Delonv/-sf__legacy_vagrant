# -*- mode: ruby -*-
# vi: set ft=ruby :
vm_box = ENV['BOX'] ? ENV['BOX'] : 'ubuntu/trusty64'
vm_hostname = 'vagrantskillfactory'

Vagrant.require_version '>= 2.2.0'
VAGRANTFILE_API_VERSION = '2'.freeze

    # Start shell provisioning.
    config.vm.provision "shell", path: "install_pythonandsmth.sh"
    end
end