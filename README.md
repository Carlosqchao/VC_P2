## Autores

- Juan Boissier García
- Carlos Ruano Ramos

## TAREA 1: Análisis de Bordes con Canny y Conteo de Píxeles Blancos

Descripción:  
Se procesó una imagen utilizando el detector de bordes Canny para identificar píxeles con valores de 255 (blancos). Posteriormente, se realizó un conteo de píxeles blancos por fila, identificando la fila con mayor cantidad de bordes y aquellas que superan el 90% del valor máximo. Finalmente, se graficaron los resultados para visualizar la distribución de bordes.

Objetivos de aprendizaje:
- Uso del detector de bordes Canny en OpenCV.
- Aplicación de reducción de matrices con `cv2.reduce` para análisis por filas.
- Normalización y análisis de datos numéricos con NumPy.
- Representación gráfica de resultados con Matplotlib.

## TAREA 2: Análisis de Bordes con Sobel y Detección de Filas y Columnas Destacadas

Descripción:  
Se aplicó el filtro Sobel en direcciones X e Y sobre una imagen en escala de grises para calcular la magnitud del gradiente y detectar bordes. Tras binarizar la imagen, se contaron los píxeles blancos por fila y columna, identificando aquellas que superan el 90% del valor máximo. Finalmente, se resaltaron visualmente las filas y columnas destacadas sobre la imagen original y se graficaron los conteos.

Objetivos de aprendizaje:
- Aplicación del operador Sobel para detección de bordes.
- Cálculo de la magnitud del gradiente y binarización.
- Conteo y análisis de píxeles mediante reducción por filas y columnas.
- Visualización de resultados y gráficas con Matplotlib.
  
## TAREA 3: Demostrador de Modos de Procesamiento en Video con OpenCV

Descripción:  
Se implementó un programa que captura video en tiempo real desde la cámara y permite alternar entre diferentes modos de visualización mediante el teclado. Los modos incluyen la imagen original, escala de grises y detección de bordes con Canny. El cambio de modo se realiza presionando las teclas 0, 1, 2 o 3, y se finaliza con la tecla Esc.

Objetivos de aprendizaje:
- Uso de captura de video en tiempo real con OpenCV.
- Aplicación de conversiones de color y filtros de procesamiento.
- Implementación de interacción con teclado para control dinámico.
- Visualización en tiempo real de imágenes procesadas. 

## TAREA 4: Detección de Rostros y Superposición de Imágenes con OpenCV

Descripción:  
Se desarrolló un programa que captura video en tiempo real y detecta rostros mediante el clasificador Haar Cascade. Sobre cada rostro detectado se superpone una imagen seleccionada entre tres opciones diferentes. El cambio de imagen se controla con las teclas 1, 2 y 3, y el programa finaliza con Esc.

Objetivos de aprendizaje:
- Uso del detector de rostros Haar Cascade en tiempo real.
- Implementación de superposición de imágenes sobre regiones detectadas.
- Manipulación de tamaños y posiciones de imágenes con OpenCV.
- Control dinámico de modos mediante interacción con teclado.
