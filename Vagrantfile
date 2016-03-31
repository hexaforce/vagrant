# -*- mode: ruby -*-
# vi: set ft=ruby :
Vagrant.configure(2) do |config|
  config.vm.box = "alpine-3.3.3-x86_64"
  config.ssh.shell = "/bin/ash"
  config.vm.network "private_network", ip: "192.168.33.10", auto_config: false
  config.vm.synced_folder ".", "/vagrant", disabled: true
end
