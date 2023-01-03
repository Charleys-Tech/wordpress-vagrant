# Wordpress made Vagrant

Wordpress made Vagrant is an attempt to deploy a local [WordPress](https://wordpress.org) development environment quickly and efficiently. It uses [Vagrant](https://www.vagrantup.com) and VirtualBox/VMware Fusion/Hyper-V to create a linux server environment([Ubuntu_18.04](https://app.vagrantup.com/hashicorp/boxes/bionic64)) with LEMP Stack (Linux Nginx MySQL PHP) as the environment

## How To Use

To use it, download and install [Vagrant](https://www.vagrantup.com) and [VirtualBox](https://www.virtualbox.org/). Then, clone this repository and run:

```shell
vagrant up
```

When it's done, visit [http://localhost:8080](http://localhost:8080).