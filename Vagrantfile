Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.box_version = "1905.1"

  config.vm.define "listener" do |l|
    l.hostname = "listener"
  end
  # If you have multiple provider on one machine you should pick one
  # Vagrant will try to use other present providers if default fails 
  # config.vm.provider "hyperv"
  # config.vm.provider "virtualbox"
end