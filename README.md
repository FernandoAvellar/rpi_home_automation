# rpi_home_automation
Base para projetos de automação residencial com o Raspberry Pi
# Hadware
Raspeberry Pi</br>
Relay Module
# Fluxo de Comunicação
App Android --> Servidor Web (Apache) --> PHP --> Python --> GPIO Raspberry
# App Android
Desenvolvido no MIT APP Inventor 2 - http://appinventor.mit.edu/</br>
Source: automacao.aia </br>
APP: automacao.apk
# GPIO
Foi utilizado o Pino 17. para conexão com o relay molude(scripts python)</br>
# Instruções
1. Copiar o diretório <b>GPIO</b> para <b>/home/pi</b></br>
2. Copiar o arquivo <b>php/automacao.php</b> para <b>/var/www/html</b> (diretório home do servidor web)
