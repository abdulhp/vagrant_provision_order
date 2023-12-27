# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"

  config.vm.provision "first_step", type: 'shell' do |s|
    s.inline = 'echo "first_step"'
  end

  config.vm.provision "first_step", type: 'shell' do |s|
    s.inline = 'echo "overriden first_step"'
  end
end
