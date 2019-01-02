# My personal machine provisioning using Ansible

This repository contains my latest machine configuration setup, that install some OS packages, configurations, etc.

I choose to use Ansible mostly to learn more about it after seeing https://github.com/flaudisio/ansible-workstation.

## The real beginning

For the first time, run:

```sh
wget -nv https://github.com/geovanisouza92/machine/archive/master.tar.gz -O - | tar -xzf -
cd machine-master
./machine bootstrap
```

The starting point it the [`machine`](./machine) script, that has two commands:

## `./machine bootstrap`

Install some dependencies including Ansible.

## `./machine run`

Start provisioning the machine by installing some OS dependencies and configurations.
