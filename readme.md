# Start CentOs7 in vagrant using docker

In Apple M1 chip virtualbox cannot be installed. But docker can be used with vagrant to manage virtual machines. Using this repo one can run centos 7 in docker virtual machine using vagrant.

```sh
vagrant up --provider=docker
vagrant ssh
```