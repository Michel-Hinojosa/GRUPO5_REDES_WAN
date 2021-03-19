# GRUPO5_REDES_WAN
ACCESO REMOTO
SSH
Primero debemos cambiar el hostname y colocar las credenciales para proteger el router
1.	ip domain name espe.com
2.	crypto key generate rsa
3.	How many bits in the modulus [512]: 1024
4.	ip ssh version 2
5.	definiremos un máximo de 2 intentos
6.	ip ssh authentication-retries 2
7.	username koulquiango privilege 15 secret powerz12345
8.	line vty 0 15
9.	definimos el medio de transporte transport input ssh
10.	definimos el tiempo de espera exec-timeout 1
11.	login local
12.	exit
13.	ssh -l koulquiango 10.0.10.1
14.	show ruuning-config
Comando para FTP
https://byspel.com/configurar-servidor-ftp-en-cisco-packet-tracer/
