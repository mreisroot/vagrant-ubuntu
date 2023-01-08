# Instância do Ubuntu no Vagrant

Este projeto apresenta um exemplo simples de criação de máquina virtual pelo Vagrant.

O SO utilizado neste exemplo é o Ubuntu na versão 20.04 (Focal LTS).

Para utilizar este projeto, instale o Vagrant em sua máquina física:

[Instalação do Vagrant](https://developer.hashicorp.com/vagrant/downloads)

Após a instalação, execute o comando abaixo dentro da pasta do projeto:

`vagrant up`

Este comando irá procurar pelo arquivo Vagrantfile, que contém as especificações da máquina virtual, e criará a máquina virtual.

Para acessar a máquina virtual criada, execute:

`vagrant ssh`

Com este comando, haverá o acesso da máquina virtual via protocolo SSH (Secure Shell).
