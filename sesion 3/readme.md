# Cómo Medir Voltaje en Proteus

![Proteus Logo](banner.png)

https://udistritaleduco-my.sharepoint.com/:v:/g/personal/jsmorenoq_udistrital_edu_co/EWhE8uFQLXJDmSjGr--3XHsBV8XaI7z9Qa5vA-RxdCluAw?e=R9ZycG&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

¡Hola! esta sesion 3 te explica de manera sencilla cómo medir el voltaje en un circuito usando Proteus Design Suite. Es perfecto para estudiantes de primer semestre que están empezando con la simulación de circuitos eléctricos. El voltaje es la diferencia de potencial eléctrico entre dos puntos.

## Requisitos Previos
- Proteus instalado en tu computadora.
- Un proyecto abierto con un circuito básico (por ejemplo, con una batería y resistencias).

## Pasos para Medir el Voltaje

### 1. Crea o Abre tu Circuito
- Abre Proteus y carga un proyecto existente o crea uno nuevo.
- Agrega una fuente de voltaje (como una batería) y componentes como resistencias (consulta los README de sesiones anteriores si necesitas ayuda para agregar elementos).
- Conecta los elementos para formar un circuito simple.

### 2. Agrega un Voltímetro
- En la **Library Browser**, busca "VOLTMETER" o "MULTIMETER".
- Arrástralo al área de diseño.
- Configúralo como voltímetro: haz doble clic y selecciona la opción de voltaje (V).

### 3. Conecta el Voltímetro
- Conecta las puntas del voltímetro a los dos puntos del circuito donde quieres medir la diferencia de voltaje.
- Por ejemplo, entre la batería y una resistencia, o entre dos nodos del circuito.
- Asegúrate de que esté en paralelo con la parte del circuito que quieres medir (no en serie, ya que eso cambiaría el circuito).

### 4. Simula el Circuito
- Haz clic en el botón "Play" (▶️) para iniciar la simulación.
- El voltímetro mostrará el valor del voltaje en voltios (V).

### 5. Interpreta los Resultados
- Compara el valor medido con tus cálculos teóricos (usando la ley de Ohm: V = I * R).
- Si el circuito tiene divisiones, verifica el voltaje en cada parte.

### 6. Guarda tu Trabajo
- Ve a **File > Save** para guardar el proyecto.
- Documenta los valores en tu cuaderno o en este README.

## Consejos para Principiantes
- **Circuito básico**: Empieza con una batería de 5V y una resistencia de 1kΩ para medir el voltaje a través de la resistencia.
- **Modo correcto**: El voltímetro debe estar en modo DC (corriente continua) si usas baterías.
- **Errores comunes**: No conectes el voltímetro en serie; debe estar en paralelo. Si el valor es cero, revisa las conexiones.
- **Ayuda en Proteus**: Usa **Help > Tutorials** para ver ejemplos visuales.
- Practica cambiando valores de componentes y observa cómo cambia el voltaje.

## Ejemplo Rápido
- Agrega una batería de 10V y una resistencia de 2kΩ en serie.
- Conecta el voltímetro en paralelo con la resistencia.
- Simula: deberías ver aproximadamente 10V en el voltímetro (si no hay otras caídas).

¡Experimenta y diviértete aprendiendo! Si tienes dudas, revisa tutoriales en línea o pregunta a tu profesor.

---

Este README es para estudiantes de primer semestre. Si necesitas más detalles, edítalo aquí.