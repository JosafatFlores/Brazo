# Brazo controlado a través de arduino version 1.0 24/05/18
Realizar un brazo en arduino para la materia de Sistemas Programables. 

Este proyecto fue realizado con fines educativos. 

Autores: 
Cristian Josafat Flores Ramírez __ No.Control 14240146
Carlos Omar Ramírez Rangel __ No.Control 14240265
Isabel Guadalupe Rocha Ramírez __ No.Control 14240260

#Introducción 
El objetivo de está práctica es realizar un brazo que sea controlado con arduino y un lenguaje de programación, este caso el lenguaje de programación que se estableció el lenguaje de Java. El brazo recibirá una serie de instrucciones, el brazo realizará la secuencia.

#Requisitos
Se necesita una máquina con 2GB en RAM. 
Tenemos que tener instalado el siguiente software NeatBeans, Java y Arduino IDE. 
Tenemos que tener instalada la librería (nombre de la librería) en NeatBeans. 

#Instalación 
El brazo robotico tenía 4 servomotores que controlan cada articulación del mismo. Cada brazo será conectado al arduino de acuerdo al código realizado en arduino. 
Para utilizar en la protoboard necesitamos lo siguiente: 
  ✿Protoboard
  ✿Cables macho-macho 
  ✿Push Button 
  ✿Leds 
En la instalacion en la protoboard colocamos el cable de datos del servomotor en algún punto de la protoboard y desde la proto al pin arduino correspondiente, repetimos este paso con los demás servomotores. 
El boton lo conectamos al pin (número de pin), después conectamos a 5V y GND, respectivamente. 
Conectaremos los 4 leds a la protoboard y conectamos la una parte del led a GND y otra a 5V, repetimos con los demás leds. 
Los leds irán conectados a los pines (7,6,5,4). Esto será  de ayuda para saber cuuál es el servo que se está ejecutando.

#Analisis de pruebas:
Mientras el desarrollo de este software nos encontramos con el problema de mover algún servomotor, la conexión de Java a Arduino. 
Utilizamos la memoria EEPROM y fue un conflicto utilizarla. 

#Licencia:
Este proyecto cuenta con licencia GNU General Public License (GNU GPL)

#Expresiones de gratitud 
Queremos agradecer al profesor Ing. Carlos Rafael Levy Roja
