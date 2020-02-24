Vagrant.configure("2") do |config|
  # If you have multiple provider on one machine you should pick one
  # Vagrant will try to use other present providers if default fails 
  # config.vm.provider "hyperv"
  # config.vm.provider "virtualbox"
  config.vm.box = "centos/7"
  config.vm.box_version = "1905.1"

  config.vm.define "listener", primary: true do |l|
  end

  config.vm.define "pinger" do |p|
  end

end