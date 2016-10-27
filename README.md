# Coding Assignment #

### Create websites in AWS using Ansible ###
Using Ansible roles, orchestrate apache websites that will run on ubuntu images with security group.

```
# configuration
$ aws-website/roles/common/aws-keys.yml      # aws id/keys
$ aws-website/roles/webserver/vars/main.yml  # number of webserver to launch
```

``` shell
$ cd roles
$ ansible-playbook provision.yml
```
