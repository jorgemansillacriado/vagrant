Vagrant.configure(2) do |config|
  config.vm.define "webserver" do |webserver|
    webserver.vm.box = "ubuntu/trusty64"
    webserver.vm.network "private_network", ip: "192.168.0.2"
    webserver.vm.hostname = "webserver"
  end
config.vm.provider "virtualbox" do |v|
  v.memory = 1024
  v.cpus = 2
end
end

