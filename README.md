# Ventilador
## Potencia
Está constituido por el control del motor Brushless (compresor) y las electroválvulas, es necesario especificar driver de potencia (ESC, puente H) y las conexiones al Arduino.
## Alimentación
Esta constituido por el módulo de carga de 3 celdas 10 A https://www.mactronica.com.co/cargador-bateria-lipo-celdas-10a-162210011xJM, para las baterías del motor compresor, modulo de carga de baterias 1 celda 1A https://www.mactronica.com.co/cargador-bateria-litio-tp4056-micro-usb-96483598xJM para las baterías de la electrónica, el diseño o implementación de los slots de baterías, y el regulador de voltaje step up 3.7 a 5 V de las baterias de Arduino.
## Sensórica
Está constituido por los sensores de flujo, presión, y CO2, realizar la conexión de la alimentación y la comunicación de cada módulo al Arduino. 
Nota: revisar el consumo de cada módulo y la máxima corriente que puede entregar el Arduino en sus pines de alimentación, si lo supera, planear o notificar para pensar en una solución.
## Alarmas
Está constituido por un buzzer o un Neopixel, revisar si es necesario usar algún drive e implementarlo en las conexiones.
