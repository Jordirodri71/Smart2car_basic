# Smart2car_basic

Autor: Jordi Rodríguez  
  
Práctica de programación básica en Arduino   
Crearemos un vehículo de 2 ruedas con el material especificado  
Para la programación usaremos la plataforma Arduino IDE:  

https://www.arduino.cc/en/software  
  
Se han incluido las siguientes librerías:  

- NewPing  
https://bitbucket.org/teckel12/arduino-new-ping/src/master/  

- LiquidCrystal I2C  
https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library  
  
    
Este código realiza las siguientes funciones simples:  
- Lectura de sensores de línea  
- Medición de distancia de obstáculo  
- Medición de luminosidad ambiente  
- Actúa sobre motores y luces según los datos recibidos  
  
![Imagen Smart2car acabado](Smart2car_final.jpeg)  


## Material utilizado

- Arduino UNO  
- Arduino Shield Sensor v.5.0
- HC-SR04 = Sensor ultrasonido de distancia
- TCRT5000 = Sensor infrarrojo de proximidad (2x)
- LM393 = Sensor fotolumínico
- LCD I2C = Pantalla lcd
- Led blanco + R100Ω (2x)
- Led rojo + R220Ω (2x)
- Buzzer activo + R100Ω  
- L298N = Controlador de motores
- Motores Arduino (2x)
  

## Pines de conexion

A0 = Sensor ultrasonido-Echo (HC-SR04)  
A1 = Sensor ultrasonido-Trigger (HC-SR04)  
A2 = Sensor línea izquierda (TCRT5000)  
A3 = Fotosensor (LM393)  
A4 = I2C LCD (SDA)  
A5 = I2C LCD (SCL)  

D0 = (RX)  
D1 = (TX)  
D2 = Led blanco derecho  
D3-= Led rojo derecho  
D4 = Sensor línea derecha   
D5-= ENB motor izquierdo  
D6-= ENA motor derecho  
D7 = IN1 motor derecho  
D8 = IN2 motor derecho  
D9-= IN3 motor izquierdo  
D10-= IN4 motor izquierdo  
D11-= Buzzer  
D12 = Led rojo izquierdo   
D13 = Led blanco izquierdo  
