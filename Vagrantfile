# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provider "virtualbox" do |vb|
     vb.memory = "2048"
  end

  config.vm.provision :shell, path: "provision/install_packets.sh"
  config.vm.provision :shell, privileged: false, path: "provision/build_osv_erlang.sh"

end
