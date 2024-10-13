install virtualbox
```bash
sudo apt update
sudo apt install -y virtualbox
```

install vagrant
```bash
   sudo apt install -y software-properties-common
   sudo add-apt-repository -y ppa:hashicorp/vagrant
   sudo apt update
   sudo apt install -y vagrant

   vagrant --version
```

create Vagrantfile
```bash
   mkdir my_project
   cd my_project
   vagrant init
```

### vagrant commands

create or start virtual machine
```bash
vagrant up
```

connect to virtual machine
```bash
vagrant ssh
```

stop
```bash
vagrant halt
```

reload
```bash
vagrant reload
```

destroy
```bash
vagrant destroy
```

get vagrant images
```bash
vagrant box list
```