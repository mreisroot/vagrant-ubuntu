Vagrant.configure("2") do |config|

  # Definir provider e alocar recursos
  config.vm.provider "virtualbox" do |vb|
    vb.name = "vagrant-ubuntu"
    vb.cpus = 1
    vb.memory = 1024
    vb.gui = false
  end

  # Definir SO e configuração de rede
  
  # Ubuntu versão 23.04
  config.vm.box = "ubuntu/lunar64"

  # Rede pública no modo bridge; altere as placas de rede conforme
  # as interfaces da sua máquina física
  config.vm.network "public_network", bridge: [
    "wlan0",
    "eth0",
  ]

end
