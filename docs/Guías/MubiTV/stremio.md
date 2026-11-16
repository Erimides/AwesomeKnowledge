# Stremio, Setup P2P (casi) definitivo

!!! info
    Esta  guía esta basada en la de [Viren070](https://guides.viren070.me/stremio), Solo que separada en dos y traducida al español. Gracias Viren070 por tu grandiosa guía! El material de Debrid se encontrara separado en una guía proxima.
    Perfil de donación a [Viren](https://ko-fi.com/Viren070) (No esta afiliado de ninguna manera con nosotros, en ese caso habríamos copiado y pegado su guía):heart:

### Que es Stremio?

Lo que me gusta de Stremio es que, por si solo no es más que un reproductor y agregador. Puedes poner una cuenta tuya de Netflix y reproducira netflix. Asi de simple. Pero no se queda ahí, lo que lo hace poderoso son las extensiones de la comunidad, y en eso nos metemos.

### Dispositivos compatibles con Stremio

- :desktop_computer: (siguiendo nuestro glosario)
- :mobile_phone: y iPad
- FireTV
- Steamdeck
- AndroidTV
- SamsungTV
- LGTV
- Hisense TV
- PhilipsTV
- Raspberry Pi
- Metaquest
- Apple vision pro
- Más

Ademas puedes usarlos en su version web



### Crearse cuenta de stremio
PRimero necesitamos una cuenta de stremio. Esto hará que mantengamos los progresos de distinto contenido en distintos dispositivos.

Ir a [Stremio](https://www.stremio.com/) y [registrarse](https://www.stremio.com/register) con tu email.

### Descargar stremio

Simplemente descargar el archivo compatible con tu sistema en la [pagina de descarga](https://www.stremio.com/downloads) e instalarlo en el dispositivo una vez descargado.

### Configurar ajustes de stremio

- Aceleracion de hardware -> activar
- Marcar tamaño del cache -> 10GB o infinito
- Perfil de torrent -> Ultra Rapido

## Extensiones
Esto es lo que convertira al "simple" reproductor de video en una herramienta poderosisima

### Proveedores 
Las extensiones que hacen que puedas ver lo que quieras.

En esta guía todas las extensiones recomendadas seran de Torrent, 
!!! warning
    Si vives en un país donde la ley prohiba el trafico por torrent de contenido bajo copyright debería seguir la ley, ya que ademas de ser ilegal sufrirías las consecuencias por que tu IP no esta camuflada.
    Si quieres anonimizar y camuflar tus datos de trafico IP en la red para evitar actores maliciosos sugerimos el uso de una [VPN](/Indice/privsec/#vpn) :wink:

??? Torrentio
    [Instalar](torrentio.strem.fun){ .md-button .md-button--primary style: color:red } 

    - `#!python Providers:` Dejarlos así, todos marcados por defecto
    - `#!python Sorting:` Por calidad, luego por semilleros ("By quality then by size")
    - `#!python Priority Foreign language:` Spanish
    - `#!python Exclude qualities:` Screener, Cam, si su dispositivo no es compatible con 4k entonces agregue 4k
    - `#!python Maximum results by per quality`  Dejar en blanco
    - `#!python Video size limit:` El limite de tamaño del video, opcional dependiendo de velocidad de internet y otros factores. 