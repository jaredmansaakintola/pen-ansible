# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|

  # VM Image - Ubuntu v14.04
  config.vm.box = "kali/2.0"

  # VM Resources
  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
    v.cpus   = 1
  end

  # Provision with Ansible
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "playbook.yml"
  end

end
