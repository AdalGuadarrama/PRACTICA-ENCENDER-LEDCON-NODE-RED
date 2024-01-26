# PRACTICA-ENCENDER-LEDCON-NODE-RED
El objetivo es ver la  manera de programar una ESP32 con una luz LED para que sea encendida y apagada a través del programa Node-RED con la ayuda de una conexión a internet.
## INTRODUCCION 
En este repositorio te mostraremos paso a paso cómo encender un LED utilizando la plataforma Wokwi y conectarlo a una red de internet con nuestro programa Node-rede. Aprenderemos a programar el código necesario y lograr que tu LED brille con su propio resplandor. 
### MATERIAL
Para realizar el proyecto se necesita:
* Tarjeta ESP 32
* Resistor
* WOKWI
* Programa Node-RED
* Resistor
* LED
#### INSTRUCCIONES 
1. Abrimos nuestro programa Wokwi y colocamos el siguiente codigo:
2. Colocamos la libreria de PubSubClient como se muestra en la siguente imagen.
3. Despues  insertamos el LED y el Resistor con la ESP32 y procedemos a ser la conexión.
4. Abrimos el programa de Node-RED y colocamos el bloque de mqtt out.
5. Configuramos el bloque con el puerto mqtt out con el ip 18.193.219.109 y el nombre de tu eleccion.
6. A continuacion colocamos el bloque de switch.
7. Despues configuramos el bloque con el puerto switch en el grupo de interruptor.
8. Por ultimo en la pestaña de de Layout crearemos otro tabulador con el nombre de tu eleccion y dentro de el añadiremos un grupo llamado interruptor.
9. Para finalizar iniciamos el simulador en Node-RED dando click izquierdo en el botón Deploy y abrimos la tarjeta eps32 dando click izquierdo en el boton de exportar.
#### RESULTADOS 
Visualizamos  la interfaz y accionar el switch, observamos que el simulador haya funcionado. Veremos la luz del LED encendida y los valores dentro del monitor serial, con respecto a la interfaz.
#### CREDITOS
ing. Guadarrama Lome Adalberto 
