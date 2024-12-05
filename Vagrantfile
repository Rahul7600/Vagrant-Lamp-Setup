Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.network "private_network", type: "dhcp"
  
  # Increase memory and CPUs if necessary
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "2048"  # Set the memory to 2GB
    vb.cpus = 2         # Set the number of CPUs
  end

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "provision/playbook.yml"
  end
end

