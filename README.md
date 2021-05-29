# ComandosLinuxAndGit

COMANDOS UTEIS DO MUNDO LINUX


Farça a instalação de pacotes e suas dependencias
sudo apt-get -f install
sudo apt -f install

**************************************************
Comando para remover
sudo apt-get -f remove

sudo dpkg --configure -a

***********************************************************************************
Remover o PHP
Comandos para remover/desinstalar todos os pacotes relacionados à sua versão do PHP.

sudo apt-get remove --purge php7*
sudo apt-get autoremove

******************************************************************
Comando para remover/desinstalar todas as versões do PHP no Ubuntu.

sudo apt-get remove --purge php*
sudo apt-get autoremove
Remover o Apache

**********************************************************************
Comandos para desinstalação/remover do Apache no Ubuntu.

sudo apt-get remove --purge apache*
sudo apt-get autoremove.

*****************************************************************************************************
Comando para remover/desisnstalar o MySQL
A desinstalação do MySQL no Ubuntu dá um pouco mais de trabalho, pois comando apt-get não resolve tudo. 

sudo apt-get remove --purge mysql*
sudo apt-get autoremove
sudo rm -rf /var/lib/mysql
sudo rm -rf /etc/mysql

****************************************************************************
Comanso para remover/desistalar o PHPMyAdmin

sudo apt-get remove --purge phpmyadmin*
sudo apt-get autoremove
sudo apt-get autoclean

******************************************************************************
Para realizar o commit das alterações do projeto

git status

git add.

git status

git commit -m 'seu comentário'

git push origin master 

