
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.network "public_network"
  config.vm.provider "virtualbox" do |vb|
  vb.name = "Desafio 00"
  vb.memory = "1024"
  vb.cpus = "1"
  end


 
 


