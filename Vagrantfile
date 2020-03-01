# vim: set ft=ruby :
# frozen_string_literal: true

VAGRANTFILE_API_VERSION = '2'
VAGRANT_DEFAULT_PROVIDER = 'virtualbox'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = 'ubuntu/bionic64'
  config.vm.box_check_update = true
  config.vm.hostname = 'my-vagrant-box'

  config.vm.provider 'virtualbox' do |vb|
    vb.gui = false
  end
end
