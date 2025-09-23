# Lab-6
Este laboratorio consiste en que el estudiante, mediante el uso del entorno
PlarformIO, el framework de Arduino y el microcontrolador ESP32, practique el
uso de la comunicación serial utilizando el protocolo UART.
El objetivo de este laboratorio es realizar un sistema que pueda modificar la
intensidad de cada uno de los colores de un LED RGB. En donde los colores Rojo
y Verde serán manipulados por 2 potenciómetros y el color azul será modificado
mediante el envío de comandos por medio de la terminal serial. Finalmente se
deben generar las 3 señales PWM para modificar el brillo de cada color y
despliegue en una pantalla LCD 16x2 los valores correspondientes.
Parte A: Envío de Datos mediante UART (25pts) Entrega en Clase
Implemente una rutina para obtener la lectura de 2 potenciómetros. Ajuste los
valores de lectura a un rango de 8bits. Finalmente envíe ambas lecturas a la
terminal serial e identifíquelas debidamente, para que el usuario sepa que valor
corresponde al valor de intensidad de los colores Rojo y Verde del LED RGB.
Parte B: Lectura de Datos mediante UART (25pts) Entrega en Clase
Implemente una ruta para recibir datos enviados desde la terminal serial. Al recibir
los caracteres “+” y “-“, el valor de un contador de 8 bits deberá aumentar o
decrementar, respectivamente. Este contador debe tener topes. Este valor debe
luego ser desplegado en la terminal serial identificado como la intensidad del color
Azul del LED RGB.
Parte C: Despliegue de Información en Pantalla LCD (25pts) Entrega en Clase
Configura la pantalla LCD Hitachi 16x2 para utilizarla en 8 bits. Luego implemente
una rutina para desplegar los 3 valores como se muestra en el diagrama.
Parte D: Generación de señales PWM para LED RGB (25pts)
Genere 3 señales PWM en donde cada una varíe su ciclo de trabajo de forma
independiente según el valor del contador correspondiente a la intensidad de cada
color.
