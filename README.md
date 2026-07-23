# LARA KAREN - TRABAJO DE TITULACION
Este repositorio contiene el sistema desarrollado como parte del trabajo de titulación "Desarrollo de un módulo de detección de zonas de acceso terrestre en entornos de desastres naturales mediante segmentación de imágenes aéreas".


# Estructura del proyecto

### 01 Preprocesamiento_Final.ipynb

Contiene el proceso de preparación del conjunto de datos, incluyendo el redimensionamiento de imágenes, normalización, aumento de datos y generación de los archivos NumPy utilizados durante el entrenamiento.

### 02 Modelo_U-Net_final.ipynb

Implementación y entrenamiento del modelo U-Net.

### 03 Modelo_LinkNet_final.ipynb

Implementación y entrenamiento del modelo LinkNet.

### 04 Modelo_DeeplabV3.ipynb

Implementación y entrenamiento del modelo DeepLabV3+. 

### 05 Modelos

Contiene los modelos entrenados:

* Modelo_LinkNet_final.ipynb
* Modelo_U-Net_final.ipynb
* deeplabV3plus.keras
  
### 06 EvaluacionFinal_Modelos.ipynb

Comparación del desempeño de las tres arquitecturas implementadas.
### 07 Módulo_Final_Deteccion.ipynb

Implementa el sistema final de detección. Permite cargar una imagen aérea, realizar automáticamente el preprocesamiento requerido, ejecutar la predicción mediante DeepLabV3+ y visualizar la máscara segmentada obtenida.

# Funcionamiento

El sistema realiza las siguientes etapas:

* Carga de una imagen aérea.
* Preprocesamiento automático.
* Carga del modelo DeepLabV3+ entrenado.
* Segmentación de la imagen.
* Visualización de la máscara obtenida y de la superposición sobre la imagen original.
* Resultado esperado

Como salida del sistema se obtiene:

* Imagen original.
* Máscara binaria segmentada.
* Imagen con la segmentación superpuesta (Overlay).
# Autor

Karen Doménica Lara Félix

Universidad de las Fuerzas Armadas ESPE

Trabajo de Titulación
