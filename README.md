Mini Futbolito Mecatrónico  

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

  
 
2. **Implementación del sistema mecánico**  
   - Integración del motor NEMA para el movimiento de los jugadores.  
   - Instalación del solenoide de 5V para golpear el balón.  

3. **Programación y control**  
   - Configuración del Arduino Uno para controlar los motores y solenoide.  
   - Implementación del sistema de conteo de goles con el sensor lineal.  

4. **Pruebas y ajustes**  
   - Evaluación del movimiento y respuesta del sistema.  
   - Corrección de fallos y optimización del código.  

Créditos  

Proyecto desarrollado por Kleber Molina para la materia **Implementación de Sistemas Mecatrónicos**. Basado en la referencia de [Automated Foosball Table](https://www.youtube.com/watch?v=JqSubWfrhvw). 
