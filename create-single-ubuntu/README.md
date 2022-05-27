# Vagrant create single Ubuntu server

- Create a folder on your local machine

```sh
mkdir -p /home/vagrant
cd /home/vagrant
```

- Create `Vagrantfile` and copy content from this repository

```sh
nano Vagrantfile
```

- Run vm

```sh
vagrant up
```

- SSH to vm

```sh
vagrant ssh
```

- Stop vm

```sh
vagrant halt
```

- Destroy vm

```sh
vagrant destroy
```