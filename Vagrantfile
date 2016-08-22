# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos7.1"
  config.vm.network :public_network, bridge: 'en0: Wi-Fi (AirPort)'

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
  end
end
