Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.provider "virtualbox" do |vb|
     vb.memory = "4072"
     vb.cpus = 3
 end
  config.vm.provision :shell, path: "bootstrap.sh"
end

