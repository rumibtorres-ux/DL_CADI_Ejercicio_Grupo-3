Semana 2 – Actividad 1: Implementación de Redes Neuronales Básicas en Google Colab 

En esta actividad, las y los creadores de oportunidades desarrollarán una práctica guiada orientada a implementar y validar una red neuronal básica en un entorno de cuaderno interactivo (Google Colab), con el propósito de consolidar las bases del aprendizaje profundo desde la lógica de una neurona/perceptrón y la toma de decisiones por umbral.

La actividad busca evidenciar comprensión de los conceptos mínimos de redes neuronales: entradas, pesos, sesgo (bias), cálculo del puntaje z, regla de activación y obtención de una salida de clasificación (0/1). Asimismo, se espera que el/la creador(a) de oportunidades documente resultados y presente conclusiones técnicas breves a partir del comportamiento observado.

1) Producto a entregar
Se debe presentar un notebook ejecutable (.ipynb) desarrollado en Google Colab, acompañado de evidencia organizada en GitHub.

2) Características mínimas del notebook (obligatorias)
El notebook debe:

Implementar una red neuronal básica (neurona/perceptrón) y evidenciar el cálculo del puntaje z y la decisión de salida (clasificación).

Incluir un conjunto de pruebas (casos controlados) que permitan observar el comportamiento de la neurona y registrar resultados.

Mostrar resultados visibles (impresiones o tabla/resumen) que permitan verificar la salida obtenida en cada prueba.

Incluir un análisis escrito (Markdown) con conclusiones breves sobre el efecto de los parámetros (pesos y/o bias) en la decisión final.

3) Evidencia en GitHub (obligatoria)
La entrega debe quedar organizada en el repositorio con:

Carpeta de la semana: week2/

Archivo principal: notebook .ipynb

Archivo de soporte: README.md breve, que describa:

objetivo de la actividad

qué se implementó

qué pruebas se realizaron (en términos generales)

resultados principales (en una frase)

cómo ejecutar el notebook

4) Condiciones de calidad (criterio de aceptación)
La evidencia se considera válida si:

El notebook ejecuta de principio a fin sin errores.

Los resultados son reproducibles y verificables (no solo capturas).

El repositorio permite identificar con claridad la evidencia de Semana 2 (estructura y nombres).

5) Forma de entrega
El/la creador(a) de oportunidades debe entregar el enlace directo a la carpeta week2/ del repositorio de GitHub.



Objetivo de la actividad
Implementar y analizar el comportamiento de una neurona artificial básica (perceptrón) con función de activación por umbral, con el fin de comprender cómo las entradas, los pesos y el sesgo (bias) influyen en la toma de decisiones y en la salida binaria de clasificación (0/1).

¿Qué se implementó?
Se implementó una neurona/perceptrón simple que calcula el puntaje lineal z=w1x1+w2x2+bz = w_1x_1 + w_2x_2 + bz=w1​x1​+w2​x2​+b y aplica una función escalón como regla de activación.
Los pesos se mantuvieron constantes y se realizaron variaciones en el bias para observar su impacto en la salida del modelo.

¿Qué pruebas se realizaron? (en términos generales)
Se evaluó el perceptrón con un conjunto de entradas binarias, modificando el valor del sesgo en distintos escenarios.
Para cada configuración se analizaron:

El valor del puntaje zzz
La activación o no de la neurona
El comportamiento de la salida frente a un problema tipo AND


¿Cómo ejecutar el notebook?

1. Abrir el notebook en Google Colab.
2. Ejecutar programa 
3. Observar en la salida los valores
