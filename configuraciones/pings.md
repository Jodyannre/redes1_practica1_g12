# Pings

Antes de realizar ping en gns3 con las demás maquinas, se verifican las conexiones entre VPN desde CMD. Cada usuario tiene asignada una dirección VPN, como se listan a continuación:

| USUARIO         | VPN      | IP GNS3        |
| --------------- | -------- | -------------- |
| JAVIER ALFARO   | 10.8.0.3 | 192.168.112.20 |
| EDIN MONTENEGRO | 10.8.0.4 | 192.168.112.10 |
| JOEL SANTOS     | 10.8.0.5 | 192.168.112.30 |
| WILSON PEREZ    | 10.8.0.6 | 192.168.112.40 |

Como primer paso para asegurar la conectividad se debe de bajar el escudo de Windows o mas conocido como firewall. Este apartado se encuentra en el panel de control de Windows y luego en seguridad se procede a desactivar el firewall, como se observa a continuación:



![Imagen de firewall Windows](https://github.com/Jodyannre/redes1_practica1_g12/blob/feature/edin/configuraciones/images/firewall.png)

Luego que se desactivó el firewall, se procede a hacer pings entre cada VPN:

![Imagen de pings vpn](https://github.com/Jodyannre/redes1_practica1_g12/blob/feature/edin/configuraciones/images/pingvpn.png)

Sí todo fue bien, se procede a realizar ya lo que compete a esta practica en GNS3 para validar la conexión entre cada maquina, para ello se utiliza el comando ping en la consola de VPCS, estos pings se realizan desde la terminal de la VPCS del coordinador, con dirección IP: 192.168.112.10:

![pings entre vpcs](https://github.com/Jodyannre/redes1_practica1_g12/blob/feature/edin/configuraciones/images/pingsvpcs.png)