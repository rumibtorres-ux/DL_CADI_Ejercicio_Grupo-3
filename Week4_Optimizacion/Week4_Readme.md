# Semana 4 – Actividad 3: Aplicación de Técnicas de Optimización en una Red Neuronal en Google Colab 

En esta actividad, las y los creadores de oportunidades aplicarán técnicas de optimización al entrenamiento de una red neuronal en Google Colab, con el propósito de comprender cómo cambia el proceso de aprendizaje cuando se ajusta la forma en que se actualizan los parámetros del modelo. La optimización se evidencia en la evolución del entrenamiento (por ejemplo, comportamiento del loss y/o métricas) y en la comparación de configuraciones.

La actividad fortalece criterio técnico sobre hiperparámetros de entrenamiento (como tasa de aprendizaje) y sobre optimizadores (variantes de descenso por gradiente), manteniendo trazabilidad y evidencia reproducible en un notebook.

1) Producto a entregar

Un notebook ejecutable (.ipynb) desarrollado en Google Colab, con evidencia organizada en GitHub.

2) Características mínimas del notebook (obligatorias)

El notebook debe:

Incluir una red neuronal entrenable (modelo base) y un proceso de entrenamiento por épocas/iteraciones.

Evidenciar aplicación de técnicas de optimización mediante comparación de al menos dos configuraciones de entrenamiento (por ejemplo: dos optimizadores o dos tasas de aprendizaje), manteniendo constantes los demás elementos para que la comparación sea válida.

Registrar el comportamiento del entrenamiento (loss y/o métrica) para cada configuración, con evidencia visible (impresiones, tabla o gráfico).

Reportar al menos una métrica de evaluación y una breve interpretación del resultado (qué mejoró, qué empeoró o qué fue más estable).

Incluir análisis escrito (Markdown) con conclusiones breves sobre:
(i) diferencias observadas entre configuraciones,
(ii) estabilidad/velocidad de convergencia,
(iii) principales hallazgos o dificultades.

3) Evidencia en GitHub (obligatoria)

Carpeta de la semana: week4/

Archivo principal: notebook .ipynb

Archivo de soporte: README.md breve con: objetivo, técnica(s) comparada(s), configuración base (en una frase), resultado principal (1–2 líneas) y cómo ejecutar el notebook.

4) Condiciones de calidad (criterio de aceptación)

El notebook ejecuta de principio a fin sin errores.

Resultados reproducibles y verificables (no solo capturas).

Comparación coherente: mismo dataset y misma arquitectura base; se modifica únicamente el componente de optimización (optimizador y/o tasa de aprendizaje).

El repositorio permite identificar con claridad la evidencia de Semana 4 (estructura y nombres).

5) Forma de entrega

Entregar el enlace directo a la carpeta week4/ del repositorio de GitHub.
________________________________________________________________________________________________________

# Objetivo de la actividad
mplementar y validar una red neuronal básica entrenable en Google Colab para comprender de forma práctica el proceso de aprendizaje mediante backpropagation, analizando el impacto de distintas funciones de activación en el comportamiento del entrenamiento. El objetivo es evidenciar cómo la red ajusta sus pesos y sesgos para reducir el error y cómo la activación influye en la convergencia del loss y la métrica de desempeño.

# ¿Qué se implementó?
Se desarrolló un notebook ejecutable que implementa:

Una red neuronal tipo perceptrón multicapa con 1 capa y 4 neuronas y 1 capa de salida con activación sigmoidal. Entrenamiento supervisado utilizando backpropagation y optimizador Adam. Uso del dataset lógico OR para un problema de clasificación binaria. Comparación controlada de dos funciones de activación en la capa oculta: Sigmoid y ReLU Registro del proceso de entrenamiento a lo largo de 100 épocas, mostrando: Evolución del loss y Evolución de la accuracy

# ¿Qué pruebas se realizaron? (en términos generales)
Se realizaron las siguientes pruebas de validación:

Prueba de entrenamiento: Ejecución del entrenamiento completo para cada activación (Sigmoid y ReLU). Verificación de que el loss disminuye o se estabiliza con las épocas.

Prueba de métricas: Evaluación del modelo entrenado sobre el mismo dataset de entrada. Comparación del loss final y la accuracy final entre ambas activaciones.

Prueba de predicciones: Generación de predicciones para las entradas del problema OR. Validación de que la red aprendió el patrón lógico esperado.

Prueba de reproducibilidad: Ejecución completa del notebook de principio a fin sin errores. Resultados visibles y verificables mediante tablas y gráficos.

# ¿Cómo ejecutar el notebook?
Acceder a la carpeta week3/ 
Abrir el archivo Week4_Act3_RumiTorres.ipynb en Google Colab. 
Ejecutar todas las celdas en orden (Entorno de ejecución → Ejecutar todo).
