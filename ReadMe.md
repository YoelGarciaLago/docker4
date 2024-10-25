<details>
  
<summary># 1. Utiliza la imagen de Ubuntu , tag 22 y apoyandote en esta guía sigue sus instrucciones para instalar LAMP en dicho contenedor.
</summary>
sudo docker pull ubuntu:22.04
sudo docker run -it --name dam_ubuntu 

**Dentro del contenedor** 
apt update 
apt upgrade
_Instalamos Apache_
apt install -y apache2 apache2-utils
_Instalamos MariaDB_
apt install -y mariadb-server mariadb-client
_Instalar PHP_
apt install -y php php-mysql libapache2-mod-php

_Iniciamos los servicios_
service mariadb start
service apache2 start
</details>
<details><summary>
# 2. Utiliza esta guía para instalar wordpress en el contenedor.
</summary>
  </details>
<details>
</summary>
  # 3. Comprueba que puedes acceder a wordpress. 

</summary>

</details>
