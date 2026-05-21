# Tarea 7 - Clasificación y Reconocimiento de Imágenes

Este proyecto contiene dos ejercicios prácticos basados en p5.js y ml5.js para clasificación y reconocimiento de imágenes.

## Ejercicio 01: Clasificador con Cámara y Gráfico de Barras (ejer01.html)

Clasifica objetos en tiempo real a través de la cámara web utilizando un modelo entrenado personalizado.

- **Componentes:** Carga el modelo desde `./model/model.json` y utiliza Chart.js para mostrar un gráfico de barras horizontales con la confianza para cinco objetos (Celular, ConsolaRetro, Billetera, USB, Audífonos).
- **Funcionamiento:** Captura video de la webcam, lo procesa con ml5.js en tiempo real y actualiza dinámicamente las barras y etiquetas de texto con la probabilidad del objeto detectado.

## Ejercicio 02: Reconocimiento de Imágenes (ejer02.html)

Identifica objetos en imágenes estáticas predefinidas usando el modelo estándar MobileNet.

- **Componentes:** Selector desplegable con 5 imágenes de prueba (cocodrilo, gato, león, perro, ratón) y lienzo de p5.js para renderizar la imagen seleccionada.
- **Funcionamiento:** Al seleccionar una imagen de la lista, esta se dibuja en el lienzo, es clasificada por MobileNet y se muestran los resultados (etiqueta y porcentaje de confianza) en la pantalla.

## Ejecución

Se recomienda usar Live Server o un servidor local de Python para servir los archivos.
