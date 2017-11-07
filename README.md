# Vagrant Magento 2 Development Environment
Vagrantfile & Vagrant.config.yml

- PHP 7.0
- Apache 2.4
- MySQL database
- Magento 2
   -setup grunt
   -theme



Create a directory for magento2 files, synced_folder
```
mkdir ~Documents/www/magento2.8-v
```     
Change directory to folder containing Vagrantfile & Vagrant.config.yml
```
cd ~Documents/www/magento2.8
vagrant up
vagrant ssh
```

Vagrantfile.config.yml contains the ip (current settings)
Enter into your browser
```
http://192.168.10.10/magento2
```



```
vagrant destroy
```
