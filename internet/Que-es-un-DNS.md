# Direcciones IP y DNS

## ¿Que son las direcciones IP?

Una dirección IP es un identificador que se le otorga a los dispositivos una vez que se conectan a la red para ser identificados por el resto de equipos.

## ¿Que es un DNS? (Domain Name System)

Es un sistema que se encarga de traducir los nombres de dominio en direcciones IP.

Por ejemplo, si nosotros tenemos el dominio patricioalmada.com.ar, ese dominio internamente funciona con una IP a la cual nuestro equipo se va a comunicar.

### Tipos de servidores DNS

- Primarios: Estos almacenan los datos sobre los nombres de dominio en sus propios archivos.
- Secundarios: Obtienen los datos de los servidores primarios a traves de una transferencia de zona.
- Locales o cache: No contienen la base de datos, cuando se les realiza una consulta, estos a su vez consultan a otros servidores DNS y almacenan la respuesta en su base de datos para peticiones futuras.