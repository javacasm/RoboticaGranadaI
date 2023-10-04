# Robot [edison](https://meetedison.com/)

![](./images/edison.jpg)

Hay 2 versiones: v1.0 y v2.0, mucho mejor comprar la 2.0

* Precio: uno 50€
* Es compatible con piezas lego para hacer montajes más complejos
* Incluye en la documentación muchos ejemplos y montajes

![](./images/Meet-Edison-Robot-Programable.jpg)

### Sensores

* Deteccion de obstáculos derecho e izquierdo
* 1 Seguilínecesitamos
* Receptor de IR (38Khz)
* Siguelíneas (1 solo sensor)
* 2 fototransistores
* Sensor de sonido (piezoeléctrico)

Procesador de 8bits Freescale  8kb

### Programación:

Se programa con un cable específico (EdComm) que se conecta a la salida de audio (del tablet, móvil Android, Raspberry, PC, ...) y que se coloca encima del sensor siguelíneas

![](./images/edison-programacion.jpeg)

#### Programación con código de barras

Podemos grabar un programa sencillo sin más que leer un código, lo que activa un programa:

* Esquivaobstáculos
* Siguelíneas
* Sigueluz
* control por sonido
* Rebota en los bordes
* Sumo wrestle

![](./images/Edison-qr.jpg)

Podemos usar código de barras para  hacer que responda con ciertos movimiento a ciertas teclas del mando a distancia
(programamos un movimiento para un botón (código) del mando)

Para leer un código, lo colocamos a la derecha (suele haber una flecha) y pulsamos 3 veces el botón de grabación. El robot se mueve sobre el código y lo lee

#### Manejo con mandos a distancia

Se pueden usar diversos modelos de mandos a distancia. Los Sony y los Sansung funcionan perfectamente. Algunos otros como Philips no son compatibles

## Precauciones

Cómo es necesario con todos los robots móviles, conviene disponer de bastante espacio libre sobre la mesa (50cm).

Se mueve bastante rápido, con lo que hay que estár atento!!

## [Descargas](https://meetedison.com/download/)

[Descargas de software](https://meetedison.com/robot-programming-software/)

Hay aplicaciones (open https://github.com/Bdanilko/Edware) para Windows, Linux, MacOS, Android, iOS, web ([web bloques](http://edwareapp.com/?_ga=1.150026806.1695549331.1454041273#) [Web python](http://www.edpyapp.com/))

Se puede programar con bloques, python y código de bárras


![bloques](./images/edison-robot-programming-software-edware.jpg)

[Edware online (bloques)](http://edwareapp.com/?_ga=1.150026806.1695549331.1454041273#)

[Edpy online](http://www.edpyapp.com/#checkcode)


## Libros

[10 Robotics lesson  plans](https://meetedison.com/wp-content/uploads/2015/04/Your-EdVenture-into-Robotics-10-Lesson-Plans.pdf?x20535)

[Libro de actividades](https://meetedison.com/robot-activities/)


[Edison robot activities: controller](https://meetedison.com/wp-content/uploads/2015/04/EdBook1-Your-EdVenture-into-Robotics-You-re-a-Controller.pdf?x20535)

[Edison robot activities: programmer](https://meetedison.com/wp-content/uploads/2015/04/EdBook2-Your-EdVenture-into-Robotics-You-re-a-Programmer.pdf?x20535)


[Edison FAQ](https://meetedison.com/edison-robot-support/edison-robot-faq/)

[Documentación en micro-log](https://edison.micro-log.com/)


### Montaje de varios

Podemos colocar varios conectados (físicamente con los pines de lego) consiguiendo más motores (se comunican entre ellos)

Ejemplo [Impresora/plotter](https://meetedison.com/robot-activities/robot-builder/printer/)

![Impresra](./images/edison-Lego-robot-printer.jpg)

<iframe width="560" height="315" src="https://www.youtube.com/embed/yZILrtHUCxQ" frameborder="0" allowfullscreen></iframe>

## Instalación en Linux


Para ejecutar el software EdWare necesitamos instalar algunas dependencias. Para facilitar la instalación usaremos pyp. Lo instalamos con:

    sudo apt install pyp

Ahora instalamos los paquetes necesarios con:

    sudo pip install jsonpickle
    sudo pip install pygame


Ya podemos ejecutarlo con


  python edware.py
