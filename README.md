# Overview
These are the configurations used in my different Blogs / Video Tutorials.  Please visit us at

https://www.level7cloud.com

## Software
The software that I am using in everything is the following:

- OS is Mac OS High Sierra
- Vagrant 2.1.5 (Latest at time of article)
- VirtualBox 5.2.18 (Latest at time of article)
- Ansible 2.7 (Latest at time of article).  Installed using pip
- Git 2.14.3

## Instructions
1. Download the repository to your machine
```bash
git clone https://github.com/level7cloud/vagrant-virtualbox-configurations.git
```

2. Configure a local network in your virtual box "Host Network Manager" for the internal network

3. Launch the virtual machines using Vagrant.  In order for the vagrant commands to work, the directory you are in has to have a "Vagrantfile" configuration file.
```bash
cd vagrant-virtualbox-configurations/base-deployment 
vagrant up
```
