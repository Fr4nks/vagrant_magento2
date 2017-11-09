# Vagrant Magento 2 Development Environment
Vagrantfile & Vagrant.config.yml

- Ubuntu 16.4
- PHP 7.0
- Apache 2.4
- MySQL database
- Magento 2 -setup grunt -upload theme

Clone Repository
```
git clone https://github.com/Fr4nks/vagrant_magento2.git .
```
Place the Vagrantfile.config.yml one folder up. Or change line 5 of Vagrant.config.yml
```
vagrantConfig = YAML.load_file '../Vagrantfile.config.yml'
```
Start vagrant
```
vagrant up
vagrant ssh
```
Vagrantfile.config.yml contains the ip (current settings)
Enter into your browser
```
http://192.168.10.10/magento2
```

# Manage
Destroy the virtual machine 
```
vagrant destroy
```
# Git commands
How to change this file?
```
git pull
```
Make changes
```
git add .
git commit -m "my heading"
git push
```
