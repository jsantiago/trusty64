# -*- mode: ruby -*-
# # vi: set ft=ruby :

Vagrant.configure("2") do |config|

    config.vm.box = "ubuntu/trusty64"

    config.vm.provider "virtualbox" do |v|
        v.destroy_unused_network_interfaces = true
        v.memory = 2048
        v.cpus = 4
    end

    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "playbook.yml"
        ansible.verbose = 'vv'
    end

end
