# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "generic/ubuntu1804"
  config.vm.network "forwarded_port", guest: 4000, host: 4000, host_ip: "127.0.0.1"
  config.vm.synced_folder ".", "/web"

  config.vm.provision "shell", inline: <<-SHELL
    sudo apt-get update
    sudo apt install -y build-essential ruby-dev libghc-zlib-dev ruby-execjs imagemagick
    sudo gem install rubygems-update
    sudo gem install jekyll
    sudo gem install bundler -v '1.17.3'
    cd /web/
    bundle
    echo "Pro start lokalniho webserveru:"
    echo "vagrant ssh"
    echo "cd /web/; bundle exec jekyll serve --baseurl ''"
  SHELL
end
