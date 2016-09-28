Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/trusty64"
  config.vm.network :forwarded_port, guest: 6379, host: 6379

  # Set virtual machine memory size to 2Gb for now
  config.vm.provider :virtualbox do |vb|
    vb.memory = 2048 # should be enough for now.
  end

  config.vm.provision :shell, :path => "init.sh"
end
