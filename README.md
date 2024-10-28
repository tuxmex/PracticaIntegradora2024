# PracticaIntegradora2024

### **Ejercicios Combinados para la ESP32**

#### **1. Sistema de Alarma Ambiental**
- **Componentes**: DHT11, buzzer, LED RGB, OLED
- **Descripción**: Si la temperatura o la humedad superan ciertos niveles, el LED RGB cambia de color y el buzzer emite una alerta. La pantalla OLED muestra los valores actuales de temperatura y humedad.

#### **2. Control de Ventana Automática**
- **Componentes**: Servo motor, DHT11, OLED, botón
- **Descripción**: El servo controla la apertura de una "ventana". Si la humedad supera un valor, la "ventana" se abre. Un botón permite resetear el sistema y la OLED muestra el estado.

#### **3. Sistema de Distancia con Alerta de Color**
- **Componentes**: HC-SR04, LED RGB, buzzer, OLED
- **Descripción**: Mide la distancia de un objeto; si está demasiado cerca, el LED RGB se enciende en rojo y el buzzer emite una alerta. La distancia se despliega en la OLED.

#### **4. Indicador de Nivel de Agua**
- **Componentes**: Potenciómetro, LED RGB, OLED, buzzer
- **Descripción**: Simula un nivel de agua controlado con un potenciómetro. Dependiendo del nivel, el LED RGB cambia de color, y si se sobrepasa un límite, el buzzer emite un sonido.

#### **5. Panel de Control de Velocidad y Dirección de Motor DC**
- **Componentes**: Motor DC, joystick, LED RGB, OLED
- **Descripción**: Controla la velocidad de un motor DC con el joystick y muestra la dirección de giro en el LED RGB. La velocidad actual se despliega en la OLED.

#### **6. Semáforo de Tráfico con Sensor de Distancia**
- **Componentes**: LED RGB, HC-SR04, botón, buzzer
- **Descripción**: Crea un semáforo que detecta si un objeto está cerca para cambiar de rojo a verde. Un botón reinicia el semáforo y el buzzer emite una señal de alerta si el objeto pasa la distancia límite.

#### **7. Termostato de Calor con Buzzer y LED RGB**
- **Componentes**: DHT11, buzzer, LED RGB, OLED
- **Descripción**: Si la temperatura supera un límite, el LED RGB cambia a rojo y el buzzer emite una alerta. La pantalla OLED muestra la temperatura en tiempo real.

#### **8. Juego de Reflejos con Botón y LED**
- **Componentes**: Botón, LED RGB, buzzer, OLED
- **Descripción**: Crea un juego donde el LED RGB cambia de color y el jugador debe presionar el botón al ver cierto color. La OLED muestra el tiempo de reacción y el buzzer emite un sonido para el ganador.

#### **9. Detector de Proximidad para Control de Servomotor**
- **Componentes**: HC-SR04, servo motor, LED RGB, buzzer
- **Descripción**: Si el sensor detecta un objeto cercano, el servo se activa para mover una "puerta" y el LED RGB cambia de color. El buzzer alerta si el objeto está demasiado cerca.

#### **10. Control de Luces con Potenciómetro y Sensor de Distancia**
- **Componentes**: Potenciómetro, LED RGB, HC-SR04, OLED
- **Descripción**: Controla la intensidad de un LED RGB con el potenciómetro. La distancia de un objeto se muestra en la OLED y, si está muy cerca, el LED cambia de color.

#### **11. Alarma de Seguridad para Zona Restringida**
- **Componentes**: HC-SR04, buzzer, LED RGB, OLED
- **Descripción**: Si alguien cruza la zona restringida, el buzzer emite una alarma, el LED RGB parpadea en rojo, y la distancia del intruso se muestra en la OLED.

#### **12. Medidor de Intensidad de Luz Ambiental**
- **Componentes**: LDR, LED RGB, buzzer, OLED
- **Descripción**: La LDR mide la luz ambiental. El LED RGB cambia de color según la intensidad, y el buzzer suena si es muy baja. La OLED muestra el nivel en tiempo real.

#### **13. Indicador de Consumo de Energía**
- **Componentes**: Potenciómetro, OLED, LED RGB, buzzer
- **Descripción**: El potenciómetro simula el consumo de energía. Según el nivel, el LED RGB cambia de color. Si el consumo es muy alto, el buzzer suena y el valor se muestra en la OLED.

#### **14. Control de Volumen de Buzzer con Joystick**
- **Componentes**: Joystick, buzzer, OLED, LED RGB
- **Descripción**: Controla el volumen de un buzzer usando el joystick y muestra el nivel en la OLED. El LED RGB cambia de color según el nivel de volumen.

#### **15. Sistema de Alerta de Temperatura y Humedad en Invernadero**
- **Componentes**: DHT11, servo motor, buzzer, OLED
- **Descripción**: Si la temperatura o la humedad alcanzan un nivel crítico, se activa un servo para abrir ventilación y el buzzer suena. La OLED muestra los valores.

#### **16. Juego de Memoria de Colores**
- **Componentes**: LED RGB, botón, OLED, buzzer
- **Descripción**: Muestra una secuencia de colores en el LED RGB que el usuario debe recordar. Si falla, el buzzer suena y la secuencia se reinicia. La OLED muestra el puntaje.

#### **17. Sensor de Proximidad con Control de Alarma y Luz**
- **Componentes**: HC-SR04, buzzer, LED RGB, OLED
- **Descripción**: Detecta la distancia de un objeto; si está muy cerca, el buzzer y el LED RGB se activan en alerta, y la distancia se muestra en la OLED.

#### **18. Control de Ventilación en Plantas con Servo y DHT**
- **Componentes**: DHT11, servo motor, LED RGB, OLED
- **Descripción**: Según la humedad, el servo controla una "ventilación" en un invernadero. La OLED muestra los valores, y el LED RGB indica si está en niveles óptimos.

#### **19. Detector de Movimiento en Pasillo con LED RGB**
- **Componentes**: HC-SR04, LED RGB, buzzer, OLED
- **Descripción**: Detecta movimiento en un pasillo y activa el LED RGB. El buzzer suena para indicar la presencia de alguien y se muestra la distancia en OLED.

#### **20. Simulador de Semáforo de Peatones**
- **Componentes**: LED RGB, botón, buzzer, OLED
- **Descripción**: Usa un botón para cambiar el color de un LED RGB simulando un semáforo para peatones. La OLED muestra el tiempo restante y el buzzer suena en el último segundo.

#### **21. Alarma de Nivel de Agua con LED RGB y Sensor de Distancia**
- **Componentes**: HC-SR04, LED RGB, buzzer, OLED
- **Descripción**: Detecta el nivel de agua en un tanque y cambia el color del LED RGB según el nivel. Si el agua está demasiado alta o baja, suena una alarma y el nivel se muestra en la OLED.

#### **22. Control de Iluminación con Potenciómetro y Buzzer**
- **Componentes**: Potenciómetro, buzzer, LED RGB, OLED
- **Descripción**: Controla el nivel de iluminación de un LED RGB y emite un sonido cuando llega al máximo. La OLED muestra el nivel actual.

#### **23. Control de Robot Simulado con Joystick**
- **Componentes**: Joystick, servo motor, LED RGB, buzzer
- **Descripción**: Usa el joystick para simular el movimiento de un "robot" con un servo motor y muestra la dirección en el LED RGB.

#### **24. Control de Ventana con Servo y Sensor de Luz**
- **Componentes**: LDR, servo motor, LED RGB, OLED
- **Descripción**: Abre o cierra una "ventana" con un servo según la intensidad de luz detectada por la LDR. La OLED muestra el estado y el LED RGB cambia de color.

#### **25. Indicador de Nivel de Humedad en OLED**
- **Componentes**: DHT11, LED RGB, buzzer, OLED
- **Descripción**: Muestra el nivel de humedad en la OLED y cambia el color del LED RGB según el nivel. El buzzer suena si está muy bajo.

