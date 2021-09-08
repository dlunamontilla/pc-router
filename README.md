# PC Router

Es posible que deba cambiarse su nombre en el futuro.

> **Importante:**
>
> Esta documentación se va a ir actualizando en la medida en el que vaya avanzando el desarrollo de esta aplicación.

---

## ¿Qué hacer antes de utilizar?

Debe instalar primero primero los servicios DHCP y DNS. Para instalarlo, proceda a escribir en la terminal la siguiente línea:

```shell
sudo apt install isc-dhcp-server bind9
```

Luego, como la aplicación está escrita en parte en PHP debe escribir la siguiente línea para instalar el intérprete:

```shell
sudo apt install php
```

## ¿Qué permitirá hacer?

Le permitirá _configurar su equipo Linux como si fuese un router_. Además, le permitirá configurar su DNS y servidor DHCP para entregar direcciones IP dentro de su red y asignarle un nombre de dominio.

Pero, su función principal es permitir darle acceso a Internet a las personas que quiera desde una PC con Linux preparada como un servidor.

Puede controlar el tiempo de conexión de la persona, asignar una dirección IP fija, además, de bloquear ciertos sitios Web.
