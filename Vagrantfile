Vagrant.configure("2") do |config|

  # Definir fornecedor e alocar recursos
  config.vm.provider "virtualbox" do |v|
    v.name = "exemplo-ubuntu"
    v.cpus = 1
    v.memory = 1024
    v.gui = false
  end

  # Definir SO e configuração de rede
  
  # Ubuntu versão 20.04
  config.vm.box = "ubuntu/jammy64"

  # Rede pública no modo bridge; altere as placas de rede conforme
  # as interfaces da sua máquina física
  config.vm.network "public_network", bridge: [
    "wlan0",
    "eth0",
  ]

end
