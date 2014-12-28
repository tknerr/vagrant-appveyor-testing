
Vagrant.configure("2") do |c|
  c.vm.box = "ubuntu/precise32"
  c.vm.box_url = "https://atlas.hashicorp.com/ubuntu/boxes/precise32/versions/12.04.4/providers/virtualbox.box"
  c.vm.synced_folder ".", "/vagrant", disabled: true
  c.vm.provider :virtualbox do |p|
    p.customize ["modifyvm", :id, "--memory", "128"]
  end
end
