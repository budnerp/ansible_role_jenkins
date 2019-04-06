# Ansible role for Jenkins 2
Ansible role for Jenkins 2.164.1 for CentOS 7

## What's inside?
1. Jenkins 2.164.1 under [192.168.33.11:8080](http://192.168.33.11:8080)

## Installation steps
1. Set a domain in your hosts file (add a line in C:\Windows\System32\drivers\etc\hosts). Refer to Vagrantfile's web.vm.hostname configuration. Example:
    ```
    192.168.33.11 jenkins.local
    ```
2. Navigate to [jenkins.local:8080](http://jenkins.local:8080)
3. Initial admin passwrod is available in `/var/lib/jenkins/secrets/initialAdminPassword` file
    ```
    vagrant ssh jenkins
    sudo less /var/lib/jenkins/secrets/initialAdminPassword
    ```
4. Follow the installer 

## Interesting folders
```
/var/log/jenkins 
/var/lib/jenkins 
/var/cache/jenkins
/etc/sysconfig/jenkins # captures configuration parameters for the launch.
```

## Tested on
- Virtual Box 6.0.4, Vagrant 2.2.3, Ansible 2.7.6, ContOS 7 build 1812.01

## Installation

## Other links
- Jenkins User Documentation [https://jenkins.io/doc/](https://jenkins.io/doc/)

## TO DO
-[ ] add dependencies 

## License
Copyright (c) We Are Interactive under the MIT license.