Exo sur le network


Au programme ce soir, un peu de maths 😱

Pour les adresses IP et masques de sous-réseau suivants, calculez :

l’adresse de réseau
l’adresse de broadcast
le nombre d’adresses utilisables par des machines
la plage d’adresses disponibles
Certains masques utilisent la notation « classique », d’autres la notation CIDR :

192.168.13.67/24
172.16.0.1 – 255.255.255.0
172.16.27.32/23
10.7.5.1 – 255.255.128.0
10.42.0.82/12



192.168.13.67/24
255.255.255.0
256-0= 256
0, 256, 512, ...
R= 192.168.13.0
255.255.255.0 = 11111111.11111111.11111111.00000000 = 8
B= 192.168.13.255
P= 2 puissance 8 = 254

172.16.0.1
255.255.255.0
256 - 0 = 256
0, 256, 512, ...
R= 172.16.0.0
B= 172.16.0.255
p= 2 puissance 8 = 254
