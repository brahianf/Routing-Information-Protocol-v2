# RIPv2 

### Protocolo de enrutamiento RIPv2
 
	RIP versión 2 (RIPv2) para enrutar direcciones IPv4 en redes pequeñas. RIPv2 es un protocolo de
	routing vector distancia sin clase, según la definición de RFC 1723. Debido a que RIPv2 es un protocolo de routing
	sin clase, las máscaras de subred se incluyen en las actualizaciones de routing. De manera predeterminada,
	RIPv2 resume automáticamente las redes en los límites de redes principales. Cuando se deshabilita la
	sumarización automática, RIPv2 ya no resume las redes a su dirección con clase en routers fronterizos.
	En Documento se configurará la topología de la red con routing RIPv2, deshabilitará la
	sumarización automática, propagará una ruta predeterminada, declará las interfaces pasivas y usará comandos de CLI 
	para configurar,ver y verificar la información de routing RIP.
	
* Vector distancia classles y soporta VLSM

* Incluye la proxima dirección de salto en actualizaciones

* Actualizaciones por multicast

* Autenticación opcional

* Máximo de saltos 15


### Topología de red

![alt text](https://github.com/brahianf/Routing-Information-Protocol-v2/blob/master/TOPOLOGIARED.PNG)

### Tabla de direccionamiento

![alt text](https://github.com/brahianf/Routing-Information-Protocol-v2/blob/master/TABLADIRECCIONAMIENTO.PNG)
	
### Comandos CLI

	Router ACADEMICO
	
	https://github.com/brahianf/Routing-Information-Protocol-v2/blob/master/ACADEMICO.txt

	Router GESTION
	https://github.com/brahianf/Routing-Information-Protocol-v2/blob/master/GESTION.txt

### RIPv2.pkt

	https://github.com/brahianf/Routing-Information-Protocol-v2/blob/master/RIPv_2.pkt



