Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.hostname = "centos7"

  config.vm.provider("virtualbox") do |vbox|
    vbox.gui = true
    vbox.cpus = 2
    vbox.memory = 2048
  end

  config.vm.provision("ansible") do |ansible|
    ansible.playbook = "playbook.yaml"
    # ansible.verbose = "v"
  end
end
