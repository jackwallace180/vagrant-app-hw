
Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", ip: "192.168.10.100"
  config.hostsupdater.aliases = ["eng42.local"]

  config.vm.provision "shell", path: "provision/provision.sh"
end
