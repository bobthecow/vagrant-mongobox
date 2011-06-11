Vagrant::Config.run do |config|
  config.vm.box     = "base"
  config.vm.box_url = "http://files.vagrantup.com/lucid64.box"

  # config.vm.network "33.33.33.10"
  config.vm.forward_port "mongo", 27017, 27018

  config.vm.provision :puppet do |puppet|
    puppet.manifests_path = "manifests"
    puppet.manifest_file  = "base.pp"
    puppet.module_path    = "modules"
  end
end
