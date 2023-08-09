Vagrant.configure("2") do |config|
  config.vm.box = "debian/buster64"

  config.vm.define "sv1" do |server|
    server.vm.network "private_network", ip: "192.168.33.10"
  end

  config.vm.define "sv2" do |server|
    server.vm.network "private_network", ip: "192.168.33.11"
  end
end
