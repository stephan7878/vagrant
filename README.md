# Vagrant

This repo contains Vagrantfile templates and scripts for provisioning virtual environments.

If you are unfamiliar with Vagrant, refer to the [Introduction to Vagrant](https://www.vagrantup.com/intro) to get started.

## Installation

[Download Vagrant](https://www.vagrantup.com/downloads) from the official site.

## Boxes

The easiest way to get started is to use base images that already have the operating system installed and configured. 

You can find publicly shared boxes on [Discover Vagrant Boxes](https://app.vagrantup.com/boxes/search).

## Commands

Here is a few commands to help you get started.

* List your boxes.

```shell
vagrant box list
```

* Start/provision a Vagrantfile.

```shell
vagrant up
```

* Start/provision a Vagrantfile with a spesific provider.

```shell
vagrant up --provider hyperv|virtualbox
```

* Force destroy a Vagrant environment.

```shell
vagrant destroy -f
```

For more information, check out the official [Vagrant Documentation](https://www.vagrantup.com/docs).

# Templates

## centos-ansible-cluster

Vagrantfile for a 3-node CentOS Stream 8 Linux environment. The primary node, `ansible-1`, has both ansible and ansible-navigator installed and SSH access configured to the other 2 nodes.



## ubuntu-desktop

Vagrantfile for an Ubuntu Desktop development environment with Docker, Terraform, Visual Studio Code and the IBM Cloud CLI installed.