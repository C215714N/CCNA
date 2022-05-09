## Tabla de Contenidos
1. [Fundamentos de Redes](#fundamentos-de-redes-ccna)
1. [Tipos y Clasificacion](#tipos-y-clasificacion)

# Fundamentos de Redes (CCNA)

Se conoce como **Red informatica** a la *interconexion de 2 o mas dispositivos entre si* con la finalidad de **compartir recursos**. Estos pueden ser *fisicos*, *logicos* o alguna *prestacion*, como por ejemplo:

> * **Hardware:** Una Impresora de Red
> * **Software:** Una Carpeta Compartida
> * **Servicio:** El Acceso a Internet

Como en todo proceso de **comunicacion**, en redes se necesita de un *emisor*, un *mensaje*, un *medio* y un *receptor*. Entre los elementos que intervienen en este proceso podemos encontrar los siguientes:

> * **Dispositivos Finales:** Aquellos utilizados por el Usuario final y que inician el proceso de comunicacion.
> * **Dispositivos Intermedios:** Son los encargados de administrar la comunicacion entre los dispositivos.
> * **Conexiones y Medios** Canales o elementos utilizados para llevar a cabo el proceso de comunicacion.

## Tipos y Clasificacion

Existen diferentes criterios a la hora de diferenciar las redes, estos pueden ser por su disposicion fisica en el espacio, el funcionamiento de los dispositivos dentro de la misma, razonamiento logico y matematico aplicado en su implementacion, entre otros. A continuacion se mencionan los diferentes formas de clasificarlas.

### Area Geografica

Especificacion utilizada para determinar el alcance de las redes, independientemente de la forma en la que se encuentren interconectados los dispositivos.

* *PAN:* Personal Area Network *(Cercania Pocos Metros)*
* **LAN:** Local Area Network *(Red de localizacion Privada)*
* *CAN:* Campus Area Network *(Facultad / Base Militar / Hospital)*
* *MAN:* Metropolitan Area Network *(Interconexion Publica)*
* **WAN:** Wide Area Network *(Satelitales / Interoceánicas / Internet)*
* *SAN:* Storage Area Network *(Servidores / Matrices de Discos)*
* *VLAN:* Virtual LAN *(Division Logica de la Red)*

### Jerarquia

Clasificacion que determina la funcion que cumplen los dispositivos dentro de la red y su implementacion segun los requisitos de seguridad, para la distribucion de las tareas.

* **Client/Server:** Modelo que basa su funcionamiento en proveedores de recursos o servicios y equipos que demandan el acceso o uso de los mismo.
* **Peer To Peer:** Modelo que implementa el uso de dispositivos sin roles definidos dentro de la topologia, una red entre pares es mas facil de configurar debido a su simplicidad.

### Medios Utilizados

Diferenciacion de la forma en la que se encuentran interconectados los dispositivos de la red y a la vez se subdividen segun las diferentes tecnologias implementadas.

* **Guiados** (Cableado estructurado)
  * Cable Coaxial
  * Cable UTP
  * Fibra Optica
* **No Guiados** (Tecnologias Inalambricas)
  * Infrarrojo
  * Ondas de Radio
  * Microondas

### Topologia

Mapa que describe la forma en la que se intercambian datos entre los dispositivos de red, se divide segun su representacion en el espacio y su representacion matematica a nivel logico.

* **Fisica:** Representa la forma en la que se encuentran conectados los dispositivos de la red y la disposicion de los mismos dentro de las instalaciones.
* **Logica:** Representacion de la forma en la que produce el intercambio de datos segun los niveles de funcionamiento de cada dispositivo.

En ambos casos se aplica la misma clasificacion de la topologia segun la forma generada en el mapa grafico, dependiendo del area abarcada por la red.

* **LAN** Para los dispositivos dentro de la red empresarial / hogareña
  * **Bus:** Todos Los dispositivos comparten un mismo canal de datos
  * **Token Ring:** Los dispositivos se organizan para compartir datos
  * **Star:** Los dispositivos se intercomunican a traves de uno central
* **WAN** Para los enrutadores que conectan las redes privadas / publicas
  * **Point to Point:** Los dispositivos de red se comunican ignorando el medio
  * **Hub and Spoke:** Los dispositivos de red se intercomunican con un nodo central
  * **Full Mesh**: Los dispositivos de red se intercomunican entre todos
