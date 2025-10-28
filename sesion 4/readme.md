# Cómo Medir Corriente en Proteus

https://udistritaleduco-my.sharepoint.com/:v:/g/personal/jsmorenoq_udistrital_edu_co/EfrxZWHbs1ZAnvcpn800p84BBfwtayezQMg9K1PDIItu0Q?e=pE2oAQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


¡Hola! esta sesion 4 te guía paso a paso para medir la corriente en un circuito usando Proteus Design Suite. Es ideal para estudiantes de primer semestre que están aprendiendo sobre circuitos eléctricos. La corriente es el flujo de electrones a través de un circuito, medida en amperios (A).

## Requisitos Previos
- Proteus instalado en tu computadora.
- Un proyecto abierto con un circuito básico (por ejemplo, con una batería y resistencias).

## Pasos para Medir la Corriente

### 1. Crea o Abre tu Circuito
- Abre Proteus y carga un proyecto existente o crea uno nuevo.
- Agrega una fuente de voltaje (como una batería) y componentes como resistencias (consulta los README de sesiones anteriores si necesitas ayuda para agregar elementos).
- Conecta los elementos para formar un circuito simple.

### 2. Agrega un Amperímetro
- En la **Library Browser**, busca "AMMETER" o "MULTIMETER".
- Arrástralo al área de diseño.
- Configúralo como amperímetro: haz doble clic y selecciona la opción de corriente (A).

### 3. Conecta el Amperímetro
- Conecta el amperímetro en serie con la parte del circuito donde quieres medir la corriente.
- Esto significa que la corriente debe pasar a través del amperímetro, así que insértalo en el camino de la corriente (no en paralelo como el voltímetro).
- Por ejemplo, entre la batería y una resistencia.

### 4. Simula el Circuito
- Haz clic en el botón "Play" (▶️) para iniciar la simulación.
- El amperímetro mostrará el valor de la corriente en amperios (A).

### 5. Interpreta los Resultados
- Usa la ley de Ohm para verificar: I = V / R (corriente = voltaje / resistencia).
- Si hay ramas en paralelo, la corriente total se divide.

### 6. Guarda tu Trabajo
- Ve a **File > Save** para guardar el proyecto.
- Anota los valores en tu cuaderno o en este README.

## Consejos para Principiantes
- **Circuito básico**: Usa una batería de 5V y una resistencia de 1kΩ para medir la corriente (debería ser 5mA).
- **Modo correcto**: El amperímetro debe estar en modo DC si usas baterías.
- **Errores comunes**: No conectes el amperímetro en paralelo; debe estar en serie. Si el valor es cero, revisa que el circuito esté cerrado.
- **Ayuda en Proteus**: Usa **Help > Tutorials** para ver ejemplos visuales.
- Practica cambiando resistencias y observa cómo cambia la corriente.

## Ejemplo Rápido
- Agrega una batería de 10V y una resistencia de 2kΩ en serie.
- Conecta el amperímetro en serie con la resistencia.
- Simula: deberías ver 5mA en el amperímetro.

¡Experimenta y aprende! Si tienes dudas, revisa tutoriales en línea o pregunta a tu profesor.

---

Este README es para estudiantes de primer semestre. Si necesitas más detalles, edítalo aquí.