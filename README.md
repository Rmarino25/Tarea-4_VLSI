# Tarea-4_VLSI
En este proyecto, se desarrollará un contador arriba-abajo de 8 bits con carga paralela y reset asincrónico. El diseño estará optimizado para operar a una frecuencia mínima de 100 MHz, garantizando así un rendimiento eficiente y fiable. El contador permitirá tanto el incremento como el decremento de su valor en función de las señales de control, y podrá cargar valores específicos de manera paralela, lo que facilita su configuración en diversas aplicaciones digitales. Este proyecto combinará conceptos avanzados de diseño digital y técnicas de optimización para cumplir con los requisitos de velocidad y funcionalidad establecidos.

## Parte a
Se utilizarán las celdas DFRRHDLLX0 para los flip-flops y FAHDLLX0 para el sumador. Se medirán el retardo y el consumo de potencia del sumador a nivel esquemático, y se identificará la señal crítica de entrada del mismo. Además, se medirá la potencia dinámica de un registro sencillo (1 bit) y de un registro completo (8 bits) con la señal de reloj conmutando a la máxima frecuencia.

El esquemático queda de la sigueinte manera:
<p align="center">
    <img src="https://github.com/Rmarino25/Tarea-4_VLSI/assets/110353604/39014e33-8ef3-4c8e-8dfb-15c5abbc1565" width="500"/>
</p>

Simulación de prueba:
<p align="center">
    <img src="https://github.com/Rmarino25/Tarea-4_VLSI/assets/110353604/d115e38a-4d4b-4eeb-8ced-79b6270088ef" width="500"/>
</p>

Delay CLK-Q:
<p align="center">
    <img src="https://github.com/Rmarino25/Tarea-4_VLSI/assets/110353604/3759907a-ec1c-4cf2-a3d0-fbca8f511cf6" width="500"/>
</p>

Delay del sumador entrada-salida:
<p align="center">
    <img src="https://github.com/Rmarino25/Tarea-4_VLSI/assets/110353604/bc03ec9c-cd7e-4585-a953-a2399388b4dc" width="500"/>
</p>

Consumo de potencia del sumador:

Potencia dinámica del registro de 1 bit:

Potencia dinámica  del registro completo:


## Parte b
Se diseñó y trazó un sumador sencillo de un bit utilizando la celda FAHDLLX0 y un registro sencillo de un bit con la celda DFRRHDLLX0, incluyendo las compuertas lógicas necesarias y asegurando el cumplimiento de DRC y LVS. Se midieron los retardos y el consumo de potencia de estas unidades sencillas de la misma manera que se describió anteriormente.
<p align="center">
    <img src="https://github.com/Rmarino25/Tarea-4_VLSI/assets/110353604/718459d8-3b17-4e69-8d55-6509ea068b83" width="500"/>
</p>

## Parte c 
Se implementó el circuito y el trazado del contador completo.
### i
