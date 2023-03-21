# **Taller de Análisis automático de textos en Humanidades**
## Javier Vera Zúñiga, jveraz@pucp.edu.pe

# ## Link importante para elementos básicos de Python
# 
# [Curso de Python](https://developers.google.com/edu/python/introduction)

# ## Primeros elementos de Python
# 
# En este primer acercamiento a **Python**, veremos los siguientes conceptos:
# 
# - ¿Qué es Python?
# - ¿Dónde programar?
# - Tipos de celdas en Jupyter
# - Nociones básicas de variables
# - Lectura de archivos

# ## ¿Qué es Python?
# 
# - un **lenguaje de programación** es un lenguaje artificial que se usa para dar instrucciones que controlan una máquina.
# - tal como en las lenguas naturales, es posible definir elementos que se combinan (una sintaxis) y que portan un significado (una semántica).
# - es relevante pensar, entonces, en qué unidades o estructuras nos ofrece **Python** y cómo se combinan. Con esto, podremos dar instrucciones precisas al computador. 
# - **Python** es un lenguaje de programación de sintaxis amigable, que privilegia que los códigos o programas sean legibles.
# - **Python** necesita de un espacio donde escribir los códigos, para que luego sean transformados en instrucciones para el computador. 

# ## ¿Dónde programar?
# 
# - [Sagemaker StudioLab](https://studiolab.sagemaker.aws): gratis + 24 horas
# - [Sagemaker](https://portal.aws.amazon.com/billing/signup#/start/email): gratis + tarjeta de crédito/débito
# - [Anaconda](https://www.anaconda.com/products/distribution)
# - [Try jupyter](https://jupyter.org/try-jupyter/lab/): solo para probar

# ## Tipos de celdas
# 
# Dos tipos esenciales:
# 
# - **Código** (code)
# - **Texto** (markdown)
# 
# Probemos! ¿Cuál debemos usar?

# ## Python en términos de Python
# 
# En términos un poco más prácticos, en **Python** siempre vamos a estar interesados en manipular información de diversas formas. La idea es manipular **variables**, que van a ir actualizando sus valores. Un **código de Python** es esencialmente una **secuencia de pasos** que **modifican el valor** de **ciertas variables &#x1F638;.** 

# ## Variables en Python
# 
# ¿Qué es una **variable**?
# 
# Una **variable** es, al mismo tiempo,
# 
# - un espacio de memoria (físicamente asignado en el propio computador) que permite manejar información; y
# - una etiqueta que permite manejar esa información en nuestros códigos. 
# 
# Supongamos por ejemplo que nuestra información proviene de un texto en formato **txt.** Como programadores/programadoras &#x1F916; debemos pensar en 
# 
# - ¿Cuál es el **objetivo** de nuestro **código**?
# - ¿Qué **variables** vamos a usar?
# - ¿Qué **procedimientos** vamos a usar para **cambiar el valor de variables**?

# ### Asuntos básicos de variables
# En la expresión
# ```python
# palabra = 'Lima'
# ```
# el contenido _Lima_ se asigna a una etiqueta, la **variable** "palabra" &#x1F638;. La asignación es de derecha a izquierda! El signo "=" **NO** indica igualdad, **sino** el hecho de que se está asignando lo que está a la derecha en la variable de la izquierda &#x1F640; 
