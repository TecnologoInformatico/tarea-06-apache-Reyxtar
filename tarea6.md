TAREA 6

1- mkdir repositorios, git clone https://github.com/TecnologoInformatico/AdmInf-web.git

2- apt update

3- sudo apt install apache2

4- sudo mkdir /var/www/zbautes

5- sudo chown ubuntu zbautes

6- cd /etc/apache2/sites-available, sudo cp 000-default.conf pp.conf, sudo nano pp.conf (se edita el servername por “www.zbautes.tecnologoinformatico.com”)

7- cd /etc, sudo nano hosts (se agrega 127.0.0.1 y www.gvera.tecnologoinformatico.com)

8- sudo service apache2 restart

9- cp -r AdmInf-web /var/www/zbautes

10- Para probarlo entro a la ip 168.138.133.150 desde el navegador

11- "serverName": "zbautes.tecnologoinformatico",
    "ip": "168.138.133.150"
