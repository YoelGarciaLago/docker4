# Tarea 4 SXE

<details>  
<summary>
  1. Utiliza la imagen de Ubuntu , tag 22 y apoyandote en esta guía sigue sus instrucciones para instalar LAMP en dicho contenedor.
</summary>
sudo docker pull ubuntu:22.04
sudo docker run -it --name dam_ubuntu 
<details>
  <summary>
**Dentro del contenedor** 
    </summary>
apt update 
apt upgrade
<details><summary>Instalamos Apache</summary>
apt install -y apache2 apache2-utils
  
  </details>
<summary>Instalamos MariaDB</summary>
<details>apt install -y mariadb-server mariadb-client
  
</details>

<details>
  <summary>_Instalar PHP_</summary>
apt install -y php php-mysql libapache2-mod-php

</details>

  <details>
<summary>_Iniciamos los servicios_</summary>
service mariadb start
service apache2 start
  </details>
</details>




<details>
  <summary>
2. Utiliza esta guía para instalar wordpress en el contenedor.
</summary>

</details>
  
<details>
</summary>
 3. Comprueba que puedes acceder a wordpress. 

</summary>
</details>
