Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-18.04"

  config.vm.network "public_network", ip: "192.168.0.29"
  config.ssh.forward_agent = true
  # config.vm.synced_folder "../data", "/vagrant_data"
   config.vm.provider "virtualbox" do |vb|
     vb.memory = "2048"
     vb.cpus = 2
   end
 # config.vm.provision "ansible_local" do |ansible|
#	  ansible.playbook = "provision/playbook.yml"
#	  ansible.verbose = true
 #   end
end
