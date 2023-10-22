# Parcial-domiciliario-Sistemas-de-Procesamiento-de-Datos-Publico

## Integrantes
- Bautista Santos Tapia

---
## Parcial: Parte 1: Contador de 0 a 99 con Display 7 Segmentos y Multiplexación.

## Descripción
La multiplexacion hace que los dos display de 7 segmentos puedan estar recibiendo datos por el mismo puerto del arduino, permitiendo mandar la senal del display 1 y del display 2 por el mismo medio sin que interfieran entre ellos. Esto se logra por el TDM (Time Division Multiplexing) que hace que cuando uno este funcionando el otro no lo este y alternardolos entre si. En el codigo hacemos esto dandole un intervalo de 10 milisegundo entre cada alternacion para que haga el efecto visual de que estan todo el tiempo los dos prendidos.

## Función principal
En este proyecto estoy diseñando un contador de 0 a 99 utilizando dos displays de 7 segmentos y tres botones los cuales sirven para sumar de a uno, restar de a uno y el tercero para resetear el contador a 0.

## :robot: Link al proyecto
- https://www.tinkercad.com/things/dpvWJ6Y5xPa-bautista-santos-tapia-parcial-parte-1/editel?sharecode=bpoRQbbyKpBeLroWs2UxTb1eWhs99DoOGsAYqRPB3hg

---
### Fuentes
- Me base en este video para armar la base del codigo https://youtu.be/_Ry7mtURGDE?si=JapqSVm8sZe9f_YF
---


## Parcial: Parte 2: Modificación con Interruptor Deslizante y Números Primos.

## Descripción
Motor de Corriente Continua

El motor de corriente continua, es una máquina que convierte energía eléctrica en energía mecánica, provocando un movimiento rotatorio, gracias a la acción de un campo magnético.

Piezas de un motor de corriente continua:
- Estator: Es la pieza encargada de crear el campo magnético fijo o la excitación. En su interior se encuentran los polos inductores y las bobinas, que forman el devanado inductor. De esta forma, es posible generar el campo inductor de la máquina suministrando las polaridades norte y sur.
- Rotor: Es el corazón de este tipo de motor. Es la parte que consta de movilidad y permite desplazar la carga.
- Colector de delgas: Se trata de un conjunto de láminas de cobre, aisladas las unas de las otras. Estas láminas se encuentran, a su vez, soldadas a las bobinas.
- Escobillas de grafito: Se sitúan sobre un portaescobillas y están permanentemente en contacto con el colector de delgas. Esto les provoca un fuerte desgaste.
- Entrehierro: Se conoce como el espacio existente entre el estátor y rotor. A través de este espacio es por donde circula el flujo magnético. En algunos modelos de este tipo de motores, es posible encontrar incorporados unos polos de conmutación. Utilizados, principalmente, para evitar posibles cortocircuitos en el interior del mecanismo.

  
Cómo funciona un motor CC:

El principio de funcionamiento básico de un motor de CC se explica a partir del caso de una espira de material conductor inmersa en un campo magnético, a la cual se le aplica una diferencia de potencial (o voltaje) entre sus extremos, de forma que a través de la misma circula una corriente I. Para este caso, la espira constituye el rotor del motor y los imanes que producen el campo magnético constituyen el estator.

Entonces, dado que cuando un conductor, por el que pasa una corriente eléctrica, se encuentra inmerso en un campo magnético, este experimenta una fuerza según la Ley de Lorentz. Dicha fuerza, denominada Fuerza de Lorentz, es perpendicular al plano formado por el campo magnético y la corriente, y su magnitud esta dada por: 

F=B⋅L⋅I⋅sen(Φ)

F: Fuerza en newtons

I: Intensidad que recorre el conductor en amperios

L: Longitud del conductor en metros

B: Densidad de campo magnético o densidad de flujo tesla

Φ: Ángulo que forma I con B

En resumen, consiste en aprovechar la fuerza producida por un campo magnético sobre una intensidad de corriente eléctrica en un conductor, siguiendo la fórmula F=B•L•I.


Tipos de motores de corriente continua:
1. Serie: es el modelo en el que el campo magnético principal se conecta en serie con la armadura.
2. Paralelo: en este caso, el devanado del estátor y rotor se consigue mediante una conexión en paralelo.
3. Compound: este tipo de motor combina las opciones de motores en serie y en paralelo, descritas anteriormente.
Los tipos de motores CC se distinguen por su forma de conexión.

Ventajas y desventajas de los motores CC:

-Las principales ventajas son la sencillez que tienen para poder controlar la velocidad y su gran capacidad de sobrecarga. Tambien se puede tener en cuenta su pequeño tamaño y su nulo  daño a el medio ambiente. 

-El principal inconveniente que tienen es su mantenimiento costoso y laborioso.

Usos de los motores:

Son extremadamente útiles en infinidad de máquinas en las que se necesita una gran potencia para su correcto funcionamiento y tambien son útiles gracias a su bajo par motor y su gran velocidad. Como ejemplos podemos reseñar los trenes, tranvías, ascensores, cadenas de producción y aeromodelismo, entre otros. Su uso es tan versátil y funcional que se puede precisar de uno de estos motores en cualquier campo de aplicación.


Se podria integrar al proyecto haciendo que cuando el switch este en podicion 1 este activado y cuando este en posicion 0 se apague.


## Función principal
El proyecto consta se un switch que va a ser el factor principal ya que con el prodras cambiar entre que los displays sean un contador de 0 a 99 como anteriormente, solo que sin el boton de reinicio, o que muestren todos los numeros primos en el rango de 0 a 99. Ademas si el switch esta del lado del contador, ahora tenes unos leds conectados a un sensor de flexion que te avisan, mediante colores, que tan flexionado esta ese sensor.
El componente que agregue es el sensor de flexión y el que investigue es el motor de corriente continua.

## :robot: Link al proyecto
- https://www.tinkercad.com/things/idDMhUQKnhH-bautista-santos-tapia-parcial-parte-2/editel?sharecode=Yolw5YMv8hd4o-WcOCxc1j9FnkOfCn9575wX6b0ofpM

---
### Fuentes
- https://es.wikipedia.org/wiki/Motor_de_corriente_continua
- https://internationalcouplings.es/motores-de-corriente-continua
---




## Parcial: Parte 3: Modificación según el Último Número de Documento.

## Descripción
El Fotodiodo

El fotodiodo es un diodo semiconductor, construido con una unión PN, expuesto a la luz a través de una cobertura cristalina en forma de lente que es especialmente sensible a la incidencia de la luz visible o infrarroja.

Funcionamiento

Para que su funcionamiento sea correcto se polariza inversamente, con lo que cuando sea excitado por la luz se producirá una cierta circulación de corriente eléctrica proporcional a la cantidad de luz que lo ilumina. Esta corriente eléctrica fluye en sentido opuesto a la flecha del diodo y se llama corriente de fuga.
Los fotodiodos se utilizan en instrumentos científicos e industriales para medir la intensidad de la luz, ya sea por sí misma o como medida de alguna otra propiedad (densidad del humo, por ejemplo). 

Composición

Los fotodiodos suelen estar compuestos de silicio, sensible a la luz visible, germanio para luz infrarroja, arseniuro de indio y galio y sulfuro de plomo.

Uso

Los fotodiodos P-n pueden utilizarse como receptor de datos codificados en un haz de infrarrojos, para generar una salida que depende de la iluminación, o para cambiar el estado de los circuitos.
Los fotodiodos se utilizan en dispositivos de electrónica de consumo como reproductores de discos compactos, detectores de humo, dispositivos médicos, encendido del alumbrado y los receptores para dispositivos de control remoto por infrarrojos utilizados para controlar equipos desde televisores hasta aparatos de aire acondicionado. 
Una célula solar utilizada para generar energía eléctrica es un fotodiodo de gran superficie.



## Función principal

En este proyecto ademas de lo anteriormente dicho agregue un fotodiodo el cual detecta el porcentaje de luz que hay. Lo que hace es que si su medidor de luz le indica que hay menos de 45% de luz va a encender un primer led que da un poco de luz para ayudar a iluminar, en caso de que el indicador de luz siga bajanda y llegue a esta por debajo del 25%, se encendera un segundo led (rgb) para compenzar esa falta de luz, y, en caso de que el nivel de luz sea de menos de 10% se encendara una lampara, que es la que mas luz da de los tres. En caso de que el nivel de luz este por encima de los dichos no se encendera ninguna luz.

## :robot: Link al proyecto
- https://www.tinkercad.com/things/35Nm4dXnC0z-bautista-santos-tapia-parcial-parte-3/editel?sharecode=yQAz2Wxwt42bFXyGiT3PWYvEZEtdFHmRW_XrukUp0F8

---
### Fuentes
- https://es.wikipedia.org/wiki/Fotodiodo
- https://web.archive.org/web/20060430230802/http://www.unicrom.com/Tut_fotodiodo.asp
- https://robots-argentina.com.ar/Sensores_fotodiodos.htm
---
