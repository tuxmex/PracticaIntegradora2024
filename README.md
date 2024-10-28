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
Aquí tienes los ejercicios del 26 al 50 que incluyen al menos cuatro componentes, incluyendo la fotorresistencia (LDR) y el motor a pasos. Estos ejercicios buscan desafiar a los estudiantes con escenarios creativos y útiles.

#### **26. Control de Brillo con Potenciómetro y LDR**
- **Componentes**: LDR, potenciómetro, LED RGB, OLED
- **Descripción**: La intensidad del LED RGB se ajusta según la luz ambiental detectada por la LDR y el nivel del potenciómetro. La pantalla OLED muestra el nivel de brillo en tiempo real.

#### **27. Control de Ventana de Invernadero con Motor a Pasos**
- **Componentes**: DHT11, motor a pasos, LED RGB, OLED
- **Descripción**: Controla la apertura de una "ventana" en función de la humedad, usando el motor a pasos para ajustar posiciones. El LED RGB cambia de color según el nivel de humedad, y la OLED muestra los valores actuales.

#### **28. Sistema de Alarma para Cambio de Luz**
- **Componentes**: LDR, buzzer, LED RGB, OLED
- **Descripción**: La LDR detecta cambios drásticos en la luz. Si detecta un cambio brusco, el buzzer emite una alarma y el LED RGB se ilumina en rojo, mostrando los niveles de luz en la OLED.

#### **29. Control de Giro de Motor a Pasos con Joystick**
- **Componentes**: Joystick, motor a pasos, LED RGB, OLED
- **Descripción**: Usa el joystick para controlar la dirección y el número de pasos del motor. El LED RGB cambia de color para indicar la dirección de giro, y la OLED muestra la posición del motor.

#### **30. Semáforo Inteligente para Cruce Peatonal**
- **Componentes**: LED RGB, LDR, botón, buzzer
- **Descripción**: Simula un semáforo controlado por un botón que se activa solo si la luz ambiental es baja. Un buzzer emite una alerta si el peatón no cruza en el tiempo asignado.

#### **31. Indicador de Nivel de Agua con Motor a Pasos y Sensor de Distancia**
- **Componentes**: HC-SR04, motor a pasos, LED RGB, OLED
- **Descripción**: Usa el sensor de distancia para medir el nivel de "agua" en un tanque, y ajusta un "indicador" con el motor a pasos. La OLED muestra el nivel en tiempo real y el LED RGB indica si el nivel está seguro.

#### **32. Juego de Luz y Reflejos con LDR y Buzzer**
- **Componentes**: LDR, buzzer, LED RGB, botón
- **Descripción**: El juego inicia con el LED RGB parpadeando. El usuario debe cubrir la LDR al ver cierto color. El buzzer emite una alarma si falla y el juego se reinicia.

#### **33. Control de Puerta con LDR y Motor a Pasos**
- **Componentes**: LDR, motor a pasos, LED RGB, OLED
- **Descripción**: La puerta se abre o cierra según la intensidad de luz detectada por la LDR. La OLED muestra el estado de la puerta y el LED RGB indica si está abierta o cerrada.

#### **34. Sistema de Iluminación de Emergencia**
- **Componentes**: LDR, LED RGB, buzzer, OLED
- **Descripción**: Si la luz ambiente baja demasiado, el LED RGB se activa en blanco como iluminación de emergencia, y el buzzer emite un sonido de advertencia. La OLED muestra la intensidad de luz actual.

#### **35. Sistema de Enfriamiento en Motor a Pasos**
- **Componentes**: DHT11, motor a pasos, LED RGB, OLED
- **Descripción**: Controla el "ventilador" usando el motor a pasos si la temperatura supera un umbral. La OLED muestra la temperatura y el LED RGB cambia de color según la intensidad de enfriamiento.

#### **36. Indicador de Posición del Sol**
- **Componentes**: LDR, motor a pasos, OLED, LED RGB
- **Descripción**: La LDR detecta la intensidad de luz solar y el motor ajusta su posición simulando un panel solar. La OLED muestra el ángulo y el LED RGB indica el estado de captación solar.

#### **37. Sistema de Iluminación de Pasillo con Buzzer**
- **Componentes**: HC-SR04, LED RGB, buzzer, OLED
- **Descripción**: Si se detecta a alguien en el pasillo, el LED RGB ilumina y el buzzer emite un sonido. La OLED muestra la distancia del objeto al sensor.

#### **38. Indicador de Clima con LDR y Motor a Pasos**
- **Componentes**: DHT11, LDR, motor a pasos, LED RGB
- **Descripción**: El motor mueve una "persiana" según la luz ambiente y la temperatura. El LED RGB indica si el clima es favorable y la OLED muestra las lecturas.

#### **39. Control de Intensidad de Luz con LDR**
- **Componentes**: LDR, LED RGB, potenciómetro, OLED
- **Descripción**: Ajusta la intensidad del LED RGB según la luz ambiental detectada y el valor del potenciómetro. La OLED muestra el nivel en tiempo real.

#### **40. Indicador de Consumo con Motor a Pasos**
- **Componentes**: Potenciómetro, motor a pasos, LED RGB, OLED
- **Descripción**: El motor se mueve según el "nivel de consumo" ajustado en el potenciómetro. El LED RGB muestra un color de alerta y la OLED muestra el nivel actual.

#### **41. Medidor de Proximidad con Alarma**
- **Componentes**: HC-SR04, buzzer, LED RGB, OLED
- **Descripción**: Si el objeto se acerca a cierta distancia, el LED RGB cambia a rojo y el buzzer emite una alarma. La OLED muestra la distancia actual.

#### **42. Sistema de Temperatura con Indicador en Motor a Pasos**
- **Componentes**: DHT11, motor a pasos, LED RGB, OLED
- **Descripción**: Si la temperatura es alta, el motor gira para mover una "ventilación". La OLED muestra la temperatura, y el LED RGB cambia de color.

#### **43. Indicador de Nivel de Luz en Potenciómetro**
- **Componentes**: LDR, LED RGB, potenciómetro, buzzer
- **Descripción**: Ajusta la intensidad del LED RGB según la luz ambiental y el valor del potenciómetro. Si la luz es muy baja, el buzzer emite una alerta.

#### **44. Control de Apertura con Joystick y Motor a Pasos**
- **Componentes**: Joystick, motor a pasos, LED RGB, buzzer
- **Descripción**: Controla la apertura de una "puerta" con el joystick. El motor la abre o cierra según el movimiento del joystick, y el LED RGB muestra el estado de apertura.

#### **45. Sistema de Iluminación de Seguridad en Oscuridad**
- **Componentes**: LDR, LED RGB, buzzer, OLED
- **Descripción**: Si la luz ambiente baja demasiado, el LED RGB se enciende en blanco y el buzzer emite una alarma de advertencia. La OLED muestra el estado de luz.

#### **46. Panel de Control de Ventilación Automática**
- **Componentes**: DHT11, motor a pasos, LED RGB, OLED
- **Descripción**: Ajusta la posición del motor para abrir una "ventilación" en función de la temperatura. La OLED muestra el estado y el LED RGB indica si está en niveles óptimos.

#### **47. Simulación de Semáforo Peatonal**
- **Componentes**: LED RGB, botón, buzzer, OLED
- **Descripción**: Crea un semáforo con botón para cambiar de verde a rojo. El buzzer suena al finalizar el tiempo, y la OLED muestra el estado del semáforo.

#### **48. Indicador de Nivel de Humedad con LDR y Motor a Pasos**
- **Componentes**: DHT11, motor a pasos, LDR, OLED
- **Descripción**: La "ventilación" se ajusta según la humedad y luz detectadas. La OLED muestra las lecturas y el motor se mueve para cambiar el flujo de aire.

#### **49. Detector de Movimiento en Pasillo**
- **Componentes**: HC-SR04, LED RGB, buzzer, OLED
- **Descripción**: Detecta a alguien en un pasillo y activa el LED RGB en rojo mientras el buzzer emite un sonido. La OLED muestra la distancia del objeto al sensor.

#### **50. Indicador de Luz Solar para Paneles**
- **Componentes**: LDR, motor a pasos, LED RGB, OLED
- **Descripción**: Usa la LDR para detectar la luz solar, ajustando el motor a pasos para simular el movimiento de un panel solar. La OLED muestra el ángulo del panel, y el LED RGB indica si la captación de luz es óptima.
