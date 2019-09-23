# -*- mode: ruby -*- 
# emacs: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.provider "docker" do |d|
    d.buld_dir = "."
  end
  
  config.vm.network "forwarded_port", guest: 5000, host: 5000
end
