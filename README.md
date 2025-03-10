# greenhouse-project
In this automated greenhouse project, sensors and actuators maintain optimal conditions. A temperature sensor activates a fan if the temperature exceeds 23°C. A soil moisture sensor activates a water pump when the soil is dry. An ultrasonic sensor monitors the irrigation tank's water level and fills it if low. A photoresistor turns on the lighting.
You will find a version for Arduino and ESP32

MATERIALES:
•	ESP32
•	Sensor DHT22 o DHT11
•	Fotorresistencia
•	LED
•	Sensor Humedad del suelo Yl100 o yl69
•	Sensor de ultrasonido
•	Ventilador
•	2 bombas de agua o servomotores(las bombas pueden tener inconvenientes de corriente)
•	Fuente 12v
•	Regulador de voltaje 7805 
	LM353 → Actúa como amplificador de voltaje para activar los reles
	Fuente 5V 3A
	Fuente  5V 2A
	Fuente 12V
	Resistencias 1.2k,10k,22k,3.3k
Conexión con la Página Web
El ESP32 tiene un servidor web que permite visualizar los datos de los sensores en tiempo real. Al conectarse a la red WiFi, la página muestra:

✅ Temperatura actual.
✅ Nivel de humedad del suelo.
✅ Nivel de agua en el tanque,llenado cuando el tanque se este quedando vacio.
✅ Nivel de luz en el invernadero.
Cada segundo, la página se actualiza automáticamente con los nuevos valores.
IMPORTANCIA Y APLICACIÓN DEL PROYECTO
🌱 Ahorro de agua → El riego solo se activa cuando el suelo está seco.
🌞 Optimización del clima → Se mantiene la temperatura ideal dentro del invernadero.
📡 Monitoreo remoto → Se pueden ver los datos desde cualquier dispositivo conectado a la red.
Este proyecto combina electrónica, programación y automatización, habilidades fundamentales en el desarrollo de tecnologías agrícolas inteligentes.
Funcionamiento Técnico
