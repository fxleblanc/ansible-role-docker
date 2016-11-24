Vagrant.configure(2) do |config|
    config.vm.box = "centos/7"
    config.vm.provision "shell", inline: "sudo mkdir -p /etc/ansible/roles/docker && sudo rsync -rv /vagrant/ /etc/ansible/roles/docker/ "
    config.vm.provision "ansible_local" do |ansible|
      ansible.playbook = "test.yml"
    end
end
