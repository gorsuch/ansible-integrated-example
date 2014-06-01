# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = '2'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = 'thoughtbot/ubuntu-14-04-server'
  config.vm.hostname = 'ansible-integrated-example'

  config.vm.provision 'ansible' do |ansible|
    ansible.playbook = 'site.yml'
  end
end
