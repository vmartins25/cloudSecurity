# Cloud Security

### Preparação de ambiente

* Instalação do Docker e Kali: 
https://docs.docker.com/get-docker/
(Depois da instalação do docker seguir os passos de instalação manual do WSL através do link: https://docs.microsoft.com/pt-br/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package)

* Abrir o powershell como administrador e seguir os comandos abaixo:

  1- Habitar Subsistema do Windows para Linux: dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
  2- Verificar os requisitos para executar o WSL 2: selecione a tecla do logotipo do Windows + R, digite winver e selecione OK (para sistem x64 versão deve ser 1903 ou superior e build 18362 ou supeior, para sistema ARM64 a versão deve ser 2004 ou superior e o build 19041 ou superior, caso as configurações sejam inferiores, deve-se atualizar o sistema)
