# LINAC_V1.0
LINAC (Nombre clave) es un placa basada en SAMD21 para montaje directo en motores NEMA23, aunque se puede usar en todo tipo de motores a pasos bipolares. Por medio de comandos Seriales muy sencillos, se puede configurar cualquier motor para usarse en modo angular o lineal.

LINAC se puede programar por USB o por puerto serial, basta con conectarlo a una funente de hasta 24v, conectar el USB, abrir el puerto Serie en 9600 baudios, y se comenzará a comunicar con la PC. solamente necesitas teclear info; y LINAC te mostará un menú muy completo de opciones que puedes programar en el.


LINAC - Version 1.0 - 02/12/2019
Modulo de control de motor a pasos bipolar con programación y comandos seriales.
La velocidad por defecto es de 9600 baudios
 
La placa contiene un microcontrolador, basado en un ATSAMD21E18 de 32 bits, 
Integrado en una pequeña tarjeta con la forma perfecta para soldarse directamente
a un motor NEMA23. Para la etapa de control, cuenta con una driver Toshiba TB6560
que permite un suave manejo de corriente del motor, para lograr un torque más
robusto y un consuma más eficiente de corriente. Cuenta además con una entrada
para sensor de límite digital, pudiendo ser mecánico, infrarojo, capacitivo, etc.
Cuenta además con 3 botones para mover el motor un número configurable de mm.

Algunas de las funciones que se pueden controlar a través de los comandos seriales son:

* Micropaso configurable en 1/1, 1/2, 1/8 y 1/16.
* Habilitación y deshabilitación de las bobinas.
* Configuración de la lógica del sensor de límite.
* Configuración del numero de pasos por revolución.
* Comandos de posición en mm.
* Configuración de la velocidad de movimiento en mm/s
* 2 botones para mover el motor en pasos de 0.01, 0.1 y 1mm hacia ambos lados.
* 1 botón de enter (Uso no disponible en esta versión).
* LED RGB (Uso no disponible en esta versión.
