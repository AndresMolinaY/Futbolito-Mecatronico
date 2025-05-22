## Mini Futbolito Mecatrónico  

Este proyecto fue desarrollado como parte de la materia **Implementación de Sistemas Mecatrónicos**. Consiste en un futbolito mecatrónico basado en el video [Automated Foosball Table](https://www.youtube.com/watch?v=JqSubWfrhvw), adaptado con componentes accesibles y un diseño personalizado.  

Descripción  

El mini futbolito mecatrónico permite el control automático de los jugadores mediante un sistema de motores y sensores. Se diseñó para ofrecer una experiencia interactiva utilizando principios de automatización y control mecatrónico.  

Componentes principales  

- **Microcontrolador:** Arduino Uno  
- **Motores:** Motor paso a paso NEMA  
- **Sensores:** Sensor lineal para contabilizar goles  
- **Solenoide:** 5V para golpear el balón  
- **Estructura:** PLA impreso en 3D, diseñada por el equipo  
- **Fuente de alimentación:** Diseñada a medida con salida de 12V, incluyendo un step-down a 5V  
- **Balón:** Pelota de ping-pong  
- **Control:** El usuario puede mover los jugadores mediante un control físico  

Funcionamiento  

1. **Control de movimiento:** Los jugadores se desplazan mediante un motor NEMA controlado por el Arduino Uno.  
2. **Golpeo del balón:** Se activa un solenoide de 5V para impactar la pelota.  
3. **Contabilización de goles:** Un sensor lineal detecta cuando la pelota entra en la portería.  

Objetivos del proyecto  

- Aplicar conceptos de automatización y control en un sistema físico.  
- Implementar una solución funcional con materiales asequibles.  
- Desarrollar habilidades en integración de hardware y software.  

Posibles mejoras  

- Implementar visión por computadora para mejorar la detección de la pelota.  
- Agregar conectividad para control remoto vía Bluetooth o WiFi.  
- Mejorar la precisión del control con algoritmos más avanzados.  

Proceso de desarrollo  

1. **Diseño del futbolito:** Modelado de la estructura en software CAD e impresión en 3D.
   - Diseño y Calculos de Engranes basado en (https://www.youtube.com/watch?v=GZQxDMYksXk)
  ![image](https://github.com/user-attachments/assets/49659164-70ce-4076-adfd-2063709259fd)
   
   -Modelado de Piezas de Soporte para el perfil y base para engranes.
   ![image](https://github.com/user-attachments/assets/d4be3da8-b068-48a1-a3fe-61fd5cbda7a1)

   -Diseño Piezas para golpeador y carrito deslizante.
   ![image](https://github.com/user-attachments/assets/c1cb8876-4b7e-40a2-b061-63647b6cfa87)

  -Ensamble Final.
  ![image](https://github.com/user-attachments/assets/4afe912f-b366-4900-ba06-91d9f3196eb7)

 
3. **Implementación del sistema mecánico**
   - Integración del motor NEMA para el movimiento de los jugadores.  
   - Instalación del solenoide de 5V para golpear el balón.
   ![image](https://github.com/user-attachments/assets/e113d3f0-80d0-462d-8792-2839366076ac)


5. **Programación y control**  
   - Configuración del Arduino Uno para controlar los motores y solenoide.
   ![WhatsApp Image 2025-03-04 at 12 18 24_78e29c11](https://github.com/user-attachments/assets/5168cf78-6b7d-4ab4-b45e-799cd3ae2ec4)

   - Implementación del sistema de conteo de goles con el sensor lineal.
   ![WhatsApp Image 2025-03-04 at 12 18 23_e6e65ad9](https://github.com/user-attachments/assets/7fc85142-0300-4296-9617-1db708e560df)


6.**Integración de Fuente de Poder**
   - Calulos y Compra de Componentes
   - Ensamble y Pruebas
![WhatsApp Image 2025-03-04 at 12 18 24_b856c940](https://github.com/user-attachments/assets/3318b5b0-7f39-44da-98cf-7c89bb62be4e)


7.  **Pruebas y ajustes**  
   - Evaluación del movimiento y respuesta del sistema.  
   - Corrección de fallos y optimización del código.

8. **Producto Final**

![WhatsApp Image 2025-03-04 at 12 18 23_abc44396](https://github.com/user-attachments/assets/f31c429f-9389-4937-ada8-e6d1840fcf45)
![WhatsApp Image 2025-03-04 at 12 18 23_23466cbb](https://github.com/user-attachments/assets/fb5d772f-ffec-4816-8174-0b01a50684da)

Créditos  

Proyecto desarrollado por Kleber Molina para la materia **Implementación de Sistemas Mecatrónicos**. Basado en la referencia de [Automated Foosball Table](https://www.youtube.com/watch?v=JqSubWfrhvw). 
