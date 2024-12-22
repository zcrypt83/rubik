# Documentación del Juego Rubik

## Introducción

El juego Rubik es una aplicación interactiva que permite a los usuarios resolver un cubo Rubik virtual. La aplicación está compuesta por tres archivos principales: `rubyk.html`, `rubyk.css` y `main.js`. A continuación, se detalla el uso del juego y las opciones de personalización disponibles para los jugadores.

## Estructura de Archivos

1. **rubyk.html**: Contiene la estructura HTML del juego y referencias a los archivos CSS y JavaScript.
2. **rubyk.css**: Define el estilo visual del juego, incluyendo fuentes, colores y disposición de los elementos.
3. **main.js**: Contiene la lógica del juego, incluyendo la animación del cubo Rubik, controles y gestión de eventos.

## Uso del Juego

### Interfaz de Usuario

La interfaz del juego está dividida en varias secciones:

- **Fondo del juego**: Área donde se visualiza el cubo Rubik.
- **Texto**: Muestra información sobre el juego, incluyendo el título, el temporizador y mensajes de finalización.
- **Preferencias**: Permite al usuario ajustar configuraciones como el tamaño del cubo, el tipo de giro, la longitud del desorden y el ángulo de la cámara.
- **Temas**: Permite personalizar los colores del cubo.
- **Estadísticas**: Muestra información sobre el rendimiento del jugador, incluyendo el mejor tiempo y el total de resoluciones.
- **Botones de acción**: Proporciona acceso a funciones como estadísticas, preferencias y reiniciar el juego.

### Cómo Jugar

1. **Iniciar el juego**: Doble toque en la pantalla para comenzar.
2. **Resolver el cubo**: Interactuar con el cubo utilizando gestos de arrastre para girar las capas.
3. **Finalizar el juego**: Al completar el cubo, se mostrará un mensaje de "¡Completo!".

## Personalización del Juego

### Preferencias del Jugador

Los jugadores pueden personalizar su experiencia a través de varias opciones configurables:

1. **Tamaño del Cubo**:
 - Opciones: 2x2, 3x3, 4x4, 5x5.
 - Ajusta la dificultad del juego.

2. **Tipo de Giro**:
 - Opciones: Rápido, Suave, Rebote.
 - Cambia la forma en que las capas del cubo giran.

3. **Longitud del Desorden**:
 - Opciones: 20, 25, 30 movimientos.
 - Define cuán desordenado estará el cubo al inicio del juego.

4. **Ángulo de la Cámara**:
 - Opciones: Ortográfico, Perspectiva.
 - Permite cambiar la vista del cubo.

5. **Esquema de Colores**:
 - Opciones: Cube, Erno, Dust, Camo, Rain.
 - Cambia los colores del cubo y su fondo.

### Temas de Color

Los jugadores pueden ajustar los colores del cubo mediante un editor de HSL (Hue, Saturation, Lightness):

- **Tono (Hue)**: Ajusta el color base del cubo.
- **Saturación**: Controla la intensidad del color.
- **Luminosidad (Lightness)**: Ajusta el brillo del color.

## Estadísticas del Jugador

La sección de estadísticas permite a los jugadores ver su rendimiento:

- **Cubo**: Muestra el tamaño actual del cubo.
- **Total de Resoluciones**: Cuántas veces se ha completado el cubo.
- **Mejor Tiempo**: El tiempo más rápido registrado para resolver el cubo.
- **Peor Tiempo**: El tiempo más largo registrado.
- **Promedio de 5, 12 y 25**: Promedios de los mejores tiempos en diferentes cantidades de resoluciones.

## Conclusión

El juego Rubik ofrece una experiencia interactiva y personalizable para los amantes del cubo Rubik. Los jugadores pueden ajustar la dificultad y la apariencia del juego a su gusto, lo que les permite disfrutar de un desafío único cada vez que juegan.