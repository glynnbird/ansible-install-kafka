ansible-install-kafka
=====================

Apache Kafka is difficult to install. You need Java, sbt, Zookeeper, Scala and then Kafka itself. From a blank Ubuntu server machine, this is a not inconsiderable task.

This repository contains an Ansible playbook which will do just that.

Run it like this:

```
ansible-playbook install-kafka-playbook.yml --sudo -K
```

which will install everything on all the servers in your Ansible hosts file.
