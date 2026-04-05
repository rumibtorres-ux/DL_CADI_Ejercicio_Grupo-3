
# Week  4 – Actividad 4: Aplicación de Métodos de Regularización en una Red Neuronal

En esta actividad, las y los creadores de oportunidades aplicarán métodos de regularización a una red neuronal en Google Colab, con el propósito de reducir el sobreajuste (overfitting) y mejorar la capacidad de generalización del modelo. La regularización se evidencia comparando el desempeño del modelo con y sin técnicas de regularización, observando el comportamiento del loss y/o métricas en entrenamiento y evaluación.

La actividad fortalece criterio técnico sobre generalización, control del error y prácticas recomendadas de entrenamiento, manteniendo trazabilidad y evidencia reproducible en un notebook.

) Producto a entregar

Un notebook ejecutable (.ipynb) desarrollado en Google Colab, con evidencia organizada en GitHub.

2) Características mínimas del notebook (obligatorias)

El notebook debe:

Incluir una red neuronal entrenable (modelo base) y un proceso de entrenamiento por épocas/iteraciones.

Evidenciar la aplicación de métodos de regularización mediante comparación de al menos dos configuraciones:
(i) modelo base sin regularización y
(ii) modelo con regularización (por ejemplo: L2 y/o Dropout u otra técnica equivalente).

Registrar el comportamiento del entrenamiento y evaluación (loss y/o métrica) para cada configuración, con evidencia visible (impresiones, tabla o gráfico).

Incluir al menos una métrica de evaluación y una interpretación breve sobre el efecto de la regularización (mejoró generalización, cambió estabilidad, impacto en desempeño).

Incluir análisis escrito (Markdown) con conclusiones breves sobre:
(i) evidencia de overfitting/underfitting,
(ii) efecto de la regularización,
(iii) hallazgos o dificultades.

3) Evidencia en GitHub (obligatoria)

Carpeta de la semana: week4/ (puede incluir subcarpeta o notebook con nombre que indique “regularización”).

Archivo principal: notebook .ipynb.

Archivo de soporte: README.md breve con: objetivo, método(s) aplicado(s), comparación realizada (en una frase), resultado principal (1–2 líneas) y cómo ejecutar el notebook.

4) Condiciones de calidad (criterio de aceptación)

El notebook ejecuta de principio a fin sin errores.

Resultados reproducibles y verificables (no solo capturas).

Comparación coherente: mismo dataset y misma arquitectura base; se modifica únicamente el componente de regularización.

El repositorio permite identificar con claridad la evidencia de Semana 4 (estructura y nombres).

5) Forma de entrega

Entregar el enlace directo a la carpeta week4/ del repositorio de GitHub.


________________________________________________________________________________________________________

# Objetivo de la actividad
Aplicar técnicas de regularización en una red neuronal para reducir el sobreajuste (overfitting) y mejorar la capacidad de generalización del modelo, mediante la comparación entre un modelo base y un modelo regularizado, usando un escenario simulado de contact center.

# ¿Qué se implementó?
Se implementó una red neuronal entrenable para clasificar casos de un contact center (FCR vs escalamiento), entrenada en dos configuraciones: un modelo base sin regularización y un modelo con regularización L2 y Dropout, manteniendo constante la arquitectura y el dataset.

# ¿Qué pruebas se realizaron? (en términos generales)
Se entrenaron ambos modelos por múltiples épocas y se comparó su desempeño mediante curvas de loss y accuracy en entrenamiento y validación, así como métricas finales sobre un conjunto de prueba, con el fin de evidenciar el efecto de la regularización sobre el overfitting y la estabilidad del aprendizaje.

# ¿Cómo ejecutar el notebook?
Acceder a la carpeta week3/ 
Abrir el archivo Week4_Act3_RumiTorres.ipynb en Google Colab. 
Ejecutar todas las celdas en orden (Entorno de ejecución → Ejecutar todo).
