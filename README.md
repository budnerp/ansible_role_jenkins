# Ansible role for Jenkins 2
Ansible role for Jenkins 2.164.1 for CentOS 7

## What's inside?
1. Jenkins 2.164.1 under [192.168.33.11:8080](http://192.168.33.11:8080)

## Installation steps
1. After successful machine provisioning navigate to [192.168.33.11:8080](http://192.168.33.11:8080). Initial admin passwrod is needed.
2. SSH into `vagrant_ansible_jenkins` machine
    ```
    vagrant ssh jenkins
    ```
3. Get admin password from `/var/lib/jenkins/secrets/initialAdminPassword`
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