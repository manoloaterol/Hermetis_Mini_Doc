# Inicio Rápido

Para la configuración de Hermetis necesitarás: 

* 2 baterías AAA (LR03, las pequeñas 😉 ). No incluidas.
* Adaptador de corriente 5V (no incluido)
* Cable USB tipo B (incluido)
* Destornillador de estrella pequeño (punta Philips)
* En caso de querer motarlo en la pared, 2 tornillos + tacos acordes al soporte incluido.
* PC, smartphone o tablet para la configuración via WiFi.

## Instalación de las baterías

1. Desatornilla la tapa de la parte trasera para acceder al compartimento de las baterías. 
2. Instala las dos baterías AAA siguiendo la polaridad indicada en el soporte. *Hermetis* dispone de protección contra polaridad inversa, por lo que no hay peligro de dañarlo si se instalan de forma incorrecta por accidente.

La pantalla se refrescará mostrando información sobre las versiones del sistema y la frecuencia del chip LoRa instalado. Espera 90 segundos hasta que se muestre la primera pantalla de información.

[IMAGEN]


## Alimentación por cable

*Hermetis* dispone de un sistema de doble alimentación que permite funcionar con baterías y a la vez estar conectado mediante cable USB. En este caso, se prioriza la corriente suministrada por USB y no se consumen las baterías.

Si desconectamos el cable USB se pasa automáticamente a la alimentación mediante batería sin que se produzca ningún conrte en la alimentación y sin que se resetee el dispositivo.

Es recomendable conectar el dispositivo por cable USB durante las porcesos de configuración, sobre todo durante las configuraciones inciales, para evitar el consumo de las baterías.

[IMAGEN ADAPTADOR+CABLE] [IMAGEN CONECTOR LATERAL]

## Navegación rápida

Tras 90 segundos de haber alimentado *Hermetis*, se mostrará la primera pantalla con información obtenida mediante los sensores. A continuación se detallan la funcionalidad de cada uno de los botones.

[IMAGEN CON FLECHAS ]

* Botón 1
* Botón 2
* Botón 3

## Configuración rápida

Para configurar el dispositivo sigue los siguientes pasos:

* Pulsa el botón lateral para activar el punto de acceso Wifi. El LED inferior se iluimna en azulpara indicar que el WiFi está activo.
* Desde un ordenador o dispositivo móvil, conéctate a la nueva red WiFi habilitada por defecto con el nombre **HERMETIS_X-Y-Z**, siendo X, Y y Z valores numéricos de 1 a 255.
!!! note "Nota" 
    El nombre de la WiFi es el mismo que el nombre asignado al dispostivo, por lo que cambiará acorde a nuestra configuración.
!!! info "Info"
    Si no se detecta conexión tras 30 segundos, la WiFi se desactiva de forma automática para ahorrar batería. Pulsa de nuevo el botón lateral para activarla.
* El led lateral se iluminará en azul indicando la conexión.
* Desde el navegador, accede a la URL [http://192.168.20.20](http://192.168.20.20) para cargar la página de configuración. Según el navegador, también puedes acceder a la URL [http://hermetis.local](http://hermetis.local).
* Selecciona el idioma a mostrar en el selector de la parte superior izquierda. Navega por los diferentes apartados y realiza los cambios que consideres oportunos.
!!! note "Nota"
    Ten en cuenta que cada pestaña tiene su propio botón para guardar los datos. Úsalo en todas las pestañas que realices cambios.

Puedes encontrar más información en el apartado de [Configuración](configuration.md)
