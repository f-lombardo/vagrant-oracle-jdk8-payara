# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty32"
  config.vm.provision :shell, path: "bootstrap/run.sh"
  config.vm.network :forwarded_port, guest:4848, host:14848
  config.vm.network :forwarded_port, guest:8080, host:18080
end
