Vagrant.configure("2") do |config|

  # Definindo nome, cpu e memória da máquina virtual
  config.vm.provider "virtualbox" do |v|
    v.name = "exemplo-ubuntu"
    v.cpus = 1
    v.memory = "1024"
  end

  # Definindo o SO e configuração de rede da máquina
  
  # Ubuntu versão 20.04
  config.vm.box = "ubuntu/focal64"

  # Rede pública no modo bridge; altere a placa de rede conforme
  # as interfaces da sua máquina física
  config.vm.network "public_network", bridge: [
    "wlan0",
    "eth0",
  ]

end
