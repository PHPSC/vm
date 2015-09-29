# vm-minicursos

Máquina virtual criada para os minicursos do PHPSC Conference

## Instalação

1. Instale o [VirtualBox 5.0.4](https://www.virtualbox.org/wiki/Downloads)
1. Instale o [Vagrant 1.7.4](https://www.vagrantup.com/downloads.html)
    1. No windows instale o NFS plugin (```vagrant plugin install vagrant-winnfsd```)
1. Clone o repositório (```git clone git@github.com:PHPSC/vm-minicursos.git```)
1. Entre na pasta baixada (```cd vm-minicursos```)
1. Inicie a máquina virtual (```vagrant up```)

## Recursos

* Ubuntu Trusty 32bit
* PHP 5.6 (mysqlnd, curl, intl, mcrypt, apcu, memcached, xdebug)
* Composer
* Apache 2.4
* Mysql 5.5 (root pass = admin)
* Git
* Memcached
* NodeJS
