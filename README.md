# Tarea-4_VLSI
En este proyecto, se desarrollará un contador arriba-abajo de 8 bits con carga paralela y reset asincrónico. El diseño estará optimizado para operar a una frecuencia mínima de 100 MHz, garantizando así un rendimiento eficiente y fiable. El contador permitirá tanto el incremento como el decremento de su valor en función de las señales de control, y podrá cargar valores específicos de manera paralela, lo que facilita su configuración en diversas aplicaciones digitales. Este proyecto combinará conceptos avanzados de diseño digital y técnicas de optimización para cumplir con los requisitos de velocidad y funcionalidad establecidos.

## Parte a
Se utilizarán las celdas DFRRHDLLX0 para los flip-flops y FAHDLLX0 para el sumador. Se medirán el retardo y el consumo de potencia del sumador a nivel esquemático, y se identificará la señal crítica de entrada del mismo. Además, se medirá la potencia dinámica de un registro sencillo (1 bit) y de un registro completo (8 bits) con la señal de reloj conmutando a la máxima frecuencia.

## Parte b
Se diseñó y trazó un sumador sencillo de un bit utilizando la celda FAHDLLX0 y un registro sencillo de un bit con la celda DFRRHDLLX0, incluyendo las compuertas lógicas necesarias y asegurando el cumplimiento de DRC y LVS. Se midieron los retardos y el consumo de potencia de estas unidades sencillas de la misma manera que se describió anteriormente.

## Parte c 
Se implementó el circuito y el trazado del contador completo.
### i
