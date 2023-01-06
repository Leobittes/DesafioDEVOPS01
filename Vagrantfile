Vagrant.configure("2") do |config|
    config.vm.provider "virtualbox" do |vb|
    vb.name = "Desafio01"
    
end
 
    config.vm.box = "ubuntu/focal64"
    config.vm.network "forwarded_port", guest: 80, host: 8090

end
