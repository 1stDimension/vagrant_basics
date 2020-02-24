Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.box_version = "1905.1"

  config.vm.define "listener" do |l|
    l.hostname = "listener"
  end

  config.vm.define "pinger" do |p|
    p.hostname = "pinger"
  end

end