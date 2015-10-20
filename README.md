# vagrant-rpm
A basic CentOS 5 Vagrant development environment for building RPMs

## Usage
First install [VirtualBox](https://www.virtualbox.org/) and
[Vagrant](https://www.vagrantup.com/downloads.html) and then run the following
commands:

````bash
# Install required oscar plugin:
vagrant plugin install oscar

# Install recommended plugins:
vagrant plugin install vagrant-cachier vagrant-hostmanager
 
# Clone repo:
git clone https://github.com/liger1978/vagrant-rpm.git

# Start and provision the Vagrant environment:
cd vagrant-rpm
vagrant up

exit
````