Ejercicios VLSM
1. Con una red 172.16.0.0/16 desarrolle un esquema de direccionamiento que satisfaga los
siguientes requerimientos:
• 80 host para la Subred_1
• 100 host para la Subred_2
• 10 host para la Subred_3
• 8 host para la Subred_4
Determina para cada subred: La máscara de subred y la primera y última IP válida.
|SUBRED|IP|RED| BROADCAST| PRIMER HOST DISPONIBLE | ULTIMO HOST DISPONIBLE | MASCARA| HOSTS
|1 |172.16.0.0 /25| 172.16.0.127| 172.16.0.1| 172.16.0.126| 255.255.255.128| 126|
2 172.16.0.128 /25 172.16.0.255 172.16.0.129 172.16.0.254 255.255.255.128 126
3 172.16.1.0 /28 172.16.1.15 172.16.1.1 172.16.1.14 255.255.255.240 14
4 172.16.1.16 /28 172.16.1.31 172.16.1.17 172.16.1.30 255.255.255.240 14
2. Dada la red 192.168.0.0/24, desarrolle un esquema de direccionamiento que cumpla con los
