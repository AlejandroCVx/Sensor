# Sensor:           Seven Segment Display (4 digits)
# Por: Alejandro Cortes 

![titulo](https://user-images.githubusercontent.com/79546666/191896415-3305c4b0-6f15-4144-84de-de048f99c4d9.png)

El TM1637 es un driver para display de LED de 7 segmentos y teclado, muy popular por ser muy barato y muy sencillo de usar, tanto a nivel electrónico como a nivel de software. Existe en formato de superficie y de inserción y hay gran número de módulos, sobre todo para gestionar display de LED, que lo incluyen; lo que hace que este integrado sea muy usado para pequeños montajes que muestren valores numéricos.

La comunicación con este dispositivo es del tipo serie de dos hilos: una línea para una señal de reloj y otra línea para la información. Aunque el funcionamiento es muy similar al más conocido I2C, el TM1637 utiliza su propio protocolo TWSI.Al disponer de resistencias pull-up en las líneas de reloj y datos, cuando las comunicaciones se encuentran inactivas el nivel de la señal es alto. Para realizar las pruebas no es crítico pero para el funcionamiento normal sí es relevante considerar que debe establecerse el estado de alta impedancia en los pines de comunicaciones del microcontrolador para enviar un valor 1, y no un nivel alto de salida, ya que serán las resistencias las responsables de subir el nivel en la línea de comunicaciones.

![display-7-seg-4-digit](https://user-images.githubusercontent.com/79546666/191896809-ac984ef9-e171-4dac-aaf2-81f790fcf301.jpg)

![TM1637-4-Digit-7-Segment-Display-Module-Pinout](https://user-images.githubusercontent.com/79546666/191896882-9b70b962-07fd-445c-82c0-90b9729c0af6.png)

![subtitulo](https://user-images.githubusercontent.com/79546666/191897090-7d1fe77f-f037-4e15-92c7-ffdfc6d50c6d.png)

