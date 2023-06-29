# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  # The most common configuration options are documented and commented below.
  # For a complete reference, please see the online documentation at
  # https://docs.vagrantup.com.

  # Every Vagrant development environment requires a box. You can search for
  # boxes at https://vagrantcloud.com/search.

    # config.vm.define "trusty32" do |trusty32|
    #     trusty32.vm.box = "ubuntu/trusty32"
    #     trusty32.vm.synced_folder "/home/ash2k/vagrant/sharefolder/trusty32", "/home/vagrant/hostfolder"
    #     trusty32.vm.provider "virtualbox" do |vb|
    #         vb.name = "trusty32"
    #         vb.memory = "4096"
    #         vb.cpus = 4
    #     end
    # end

    # config.vm.define "trusty64" do |trusty64|
    #     trusty64.vm.box = "ubuntu/trusty64"
    #     trusty64.vm.synced_folder "/home/ash2k/vagrant/sharefolder/trusty64", "/home/vagrant/hostfolder"
    #     trusty64.vm.provider "virtualbox" do |vb|
    #         vb.name = "trusty64"
    #         vb.memory = "4096"
    #         vb.cpus = 4
    #     end
    # end

    # config.vm.define "xenial" do |xenial|
    #     xenial.vm.box = "ubuntu/xenial64"
    #     xenial.vm.synced_folder "/home/ash2k/vagrant/sharefolder/xenial", "/home/vagrant/hostfolder"
    #     xenial.vm.provider "virtualbox" do |vb|
    #         vb.name = "xenial"
    #         vb.memory = "4096"
    #         vb.cpus = 4
    #     end
    # end

    # config.vm.define "bionic" do |bionic|
    #     bionic.vm.box = "ubuntu/bionic64"
    #     bionic.vm.synced_folder "/home/ash2k/vagrant/sharefolder/bionic", "/home/vagrant/hostfolder"
    #     bionic.vm.provider "virtualbox" do |vb|
    #         vb.name = "bionic"
    #         vb.memory = "4096"
    #         vb.cpus = 4
    #     end
    # end

    config.vm.define "focal" do |focal|
        focal.vm.box = "ubuntu/focal64"
        focal.vm.synced_folder "/home/ash2k/vagrant/focal", "/home/vagrant/"
        focal.disksize.size = "300GB"
        # focal.vm.disk :disk, name: "focal_disk", size: "300GB", primary: true
        focal.vm.provider "virtualbox" do |vb|
            vb.name = "focal"
            # vb.memory = "4096"
            # memory 32G
            vb.memory = "32768"
            # vb.cpus = 4
            vb.cpus = 12
        end
    end

    # config.vm.define "jammy" do |jammy|
    #     jammy.vm.box = "ubuntu/jammy64"
    #     jammy.vm

    # config.vm.define "stretch" do |stretch|
    #     stretch.vm.box = "debian/stretch64"
    #     stretch.vm.synced_folder "/home/ash2k/vagrant/sharefolder/stretch", "/home/vagrant/hostfolder"
    #     stretch.vm.provider "virtualbox" do |vb|
    #         vb.name = "stretch"
    #         vb.memory = "4096"
    #         vb.cpus = 4
    #     end
    # end

    # config.vm.define "buster" do |buster|
    #     buster.vm.box = "debian/buster64"
    #     buster.vm.synced_folder "/home/ash2k/vagrant/sharefolder/buster", "/home/vagrant/hostfolder"
    #     buster.vm.provider "virtualbox" do |vb|
    #         vb.name = "buster"
    #         vb.memory = "4096"
    #         vb.cpus = 4
    #     end
    # end
end
