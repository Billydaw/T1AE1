
Vagrant.configure("2") do |config|

  config.vm.box = "hashicorp/precise32"
  config.vm.hostname = "web-dev"
  config.vm.box_url = "?-minimal"
  config.vm.provision "shell", path: "aprovisionamiento.sh"
end
