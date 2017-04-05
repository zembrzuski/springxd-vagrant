That is my way to get started to development of spring-xd applications.

- It provisions a machine with jdk8, spring-xd, and rabbit-mq

You need to install
 - vagrant
 - virtual box
 - ansible

Then, you can do the following steps:
$ vagrant up --provider virtualbox
$ vagrant provision # the machine is provisioned by default for the first time
$ vagrant ssh
