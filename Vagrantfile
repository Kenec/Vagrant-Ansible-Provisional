Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"

  config.vm.box_check_update = false

  # config.vm.network "forwarded_port", guest: 80, host: 8080

  config.vm.network "private_network", ip: "192.168.33.10"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "provisional/playbook.yml"
    ansible.ask_vault_pass = true
    ansible.verbose = false
  end
end
