# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

# Màquina virtual creada amb vagrant
  config.vm.define :maquina1 do |maquina1|
	maquina1.vm.box = "ubuntu/focal64"
	maquina1.vm.hostname = "maquina1_FH"

  config.vm.provider "virtualbox" do |vb|
	vb.gui = true
  end
end
