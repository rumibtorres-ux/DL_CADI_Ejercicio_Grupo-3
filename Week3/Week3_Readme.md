# Week 3 – Actividad 2: Implementación de Backpropagation y Funciones de Activación en Redes Neuronales en Google Colab

En esta actividad, las y los creadores de oportunidades implementarán y validarán el proceso de aprendizaje de una red neuronal mediante backpropagation y el uso de funciones de activación, en un entorno de práctica guiada (Google Colab). El propósito es evidenciar cómo una red ajusta sus parámetros (pesos y sesgos) para reducir el error durante el entrenamiento, y cómo las funciones de activación influyen en el comportamiento del modelo y su capacidad de aprendizaje.

La actividad se orienta a consolidar criterios básicos de entrenamiento: cálculo de salida, pérdida (loss), actualización de parámetros y seguimiento del desempeño mediante métricas. La evidencia debe mostrar resultados verificables y conclusiones breves sustentadas en la observación.

1) Producto a entregar
Un notebook ejecutable (.ipynb) desarrollado en Google Colab, con evidencia organizada en GitHub.

2) Características mínimas del notebook (obligatorias)
El notebook debe:

Incluir una red neuronal básica entrenable (no solo inferencia), donde sea visible el proceso de ajuste de parámetros (backpropagation).

Incluir funciones de activación y evidencia comparativa de al menos dos activaciones (por ejemplo: sigmoid y ReLU), manteniendo constantes los demás elementos para que la comparación sea válida.

Mostrar el comportamiento del entrenamiento a lo largo de iteraciones/épocas (por ejemplo: evolución del loss y/o una métrica de desempeño).

Reportar al menos una métrica de evaluación y evidencia verificable de resultados (impresiones, tabla o gráfico).

Incluir análisis escrito (Markdown) con conclusiones breves sobre:
(i) qué cambió al variar la activación,
(ii) cómo se comportó el loss/métrica,
(iii) principales dificultades o hallazgos.

3) Evidencia en GitHub (obligatoria)
Carpeta de la semana: week3/

Archivo principal: notebook .ipynb

Archivo de soporte: README.md breve con: objetivo, qué se implementó, qué activaciones se compararon, resultados principales (1–2 líneas) y cómo ejecutar el notebook.

4) Condiciones de calidad (criterio de aceptación)
El notebook ejecuta de principio a fin sin errores.

Los resultados son reproducibles y verificables (no solo capturas).

La comparación de activaciones es coherente (mismo dataset y configuración base; solo cambia la activación).

El repositorio permite identificar con claridad la evidencia de Semana 3 (estructura y nombres).

5) Forma de entrega
Entregar el enlace directo a la carpeta week3/ del repositorio de GitHub.

____________________________________________________________________________________________________________________

# Objetivo de la actividad
mplementar y validar una red neuronal básica entrenable en Google Colab para comprender de forma práctica el proceso de aprendizaje mediante backpropagation, analizando el impacto de distintas funciones de activación en el comportamiento del entrenamiento.
El objetivo es evidenciar cómo la red ajusta sus pesos y sesgos para reducir el error y cómo la activación influye en la convergencia del loss y la métrica de desempeño.


# ¿Qué se implementó?
Se desarrolló un notebook ejecutable que implementa:

Una red neuronal tipo perceptrón multicapa con 1 capa y 4 neuronas  y 1 capa de salida con activación sigmoidal.
Entrenamiento supervisado utilizando backpropagation y optimizador Adam.
Uso del dataset lógico OR para un problema de clasificación binaria.
Comparación controlada de dos funciones de activación en la capa oculta: Sigmoid y ReLU
Registro del proceso de entrenamiento a lo largo de 100 épocas, mostrando: Evolución del loss y Evolución de la accuracy

# ¿Qué pruebas se realizaron? (en términos generales)
Se realizaron las siguientes pruebas de validación:


Prueba de entrenamiento:  Ejecución del entrenamiento completo para cada activación (Sigmoid y ReLU). Verificación de que el loss disminuye o se estabiliza con las épocas.

Prueba de métricas: Evaluación del modelo entrenado sobre el mismo dataset de entrada. Comparación del loss final y la accuracy final entre ambas activaciones.

Prueba de predicciones:  Generación de predicciones para las entradas del problema OR. Validación de que la red aprendió el patrón lógico esperado.

Prueba de reproducibilidad: Ejecución completa del notebook de principio a fin sin errores. Resultados visibles y verificables mediante tablas y gráficos.

# ¿Cómo ejecutar el notebook?
Acceder a la carpeta week3/
Abrir el archivo Week3_Act2_RumiTorres.ipynb en Google Colab.
Ejecutar todas las celdas en orden (Entorno de ejecución → Ejecutar todo).

