# Instância do Ubuntu no Vagrant

Este projeto apresenta um exemplo simples de criação de máquina virtual pelo Vagrant.

O SO utilizado neste exemplo é o Ubuntu na versão 22.04 (Jammy LTS).

## Como utilizar este projeto

1. Instale o Vagrant em sua máquina:

[Instalação do Vagrant](https://developer.hashicorp.com/vagrant/downloads)

2. Após a instalação, execute o comando abaixo dentro da pasta do projeto:

`vagrant up`

Este comando irá procurar pelo arquivo [Vagrantfile](./Vagrantfile), que contém as especificações da máquina virtual, e criará a máquina virtual.

3. Para acessar a máquina virtual criada, execute:

`vagrant ssh`

Com este comando, haverá o acesso da máquina virtual via protocolo SSH (Secure Shell).

4. Para desligar a máquina virtual, execute:

`vagrant halt`

5. Para apagar a máquina virtual, execute:

`vagrant destroy`

## License

Licensed under the [ISC License](./LICENSE)
