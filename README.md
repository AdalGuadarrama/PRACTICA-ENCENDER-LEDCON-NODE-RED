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
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/l1.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/l2.png)

2. Colocamos la libreria de PubSubClient como se muestra en la siguente imagen.
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/l3.png)

3. Despues  insertamos el LED y el Resistor con la ESP32 y procedemos a ser la conexión.
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/l4.png)

4. Abrimos el programa de Node-RED y colocamos el bloque de mqtt out y switch.
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/s0.0.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/I5.png)
5. Configuramos el bloque con el puerto mqtt out con el ip 18.193.219.109 y el nombre de tu eleccion.
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/I6.png)

6. Despues configuramos el bloque con el puerto switch en el grupo de interruptor.
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/i7.png)

7. Por ultimo en la pestaña de de Layout crearemos otro tabulador con el nombre de tu eleccion y dentro de el añadiremos un grupo llamado interruptor.
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/i8.png)

#### RESULTADOS 
* Para finalizar iniciamos el simulador en Node-RED dando click izquierdo en el botón Deploy y abrimos la tarjeta eps32 dando click izquierdo en el boton de exportar.
* Visualizamos  la interfaz y accionar el switch, observamos que el simulador haya funcionado. Veremos la luz del LED encendida y los valores dentro del monitor serial, con respecto a la interfaz.
![:](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/i10.png)
![.](https://github.com/AdalGuadarrama/PRACTICA-ENCENDER-LEDCON-NODE-RED/blob/main/i9.png)

#### CREDITOS
ing. Guadarrama Lome Adalberto 
