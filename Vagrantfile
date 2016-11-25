Vagrant.configure(2) do |config|
    # Default box
    config.vm.box = "centos/7"
    # Start the test playbook from the host
    config.vm.provision "ansible" do |ansible|
      ansible.playbook = "test.yml"
      ansible.verbose = 'vv'
    end
end
