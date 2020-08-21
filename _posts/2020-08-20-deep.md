---
title: Deep Learning
search: true
tags:
  - Deep Learning
toc: true
toc_label: 'My Table of Contents'
toc_icon: 'cog'
classes: wide
---

Deep Learning

### ¿Qué es el Deep Learning?
El Deep Learning apareció recientemente en los titulares de los medios de comunicación cuando el programa AlphaGo de Google venció al campeón mundial de Go (juego mucho más difícil de jugar por parte de una máquina que el ajedrez, ya que tiene muchas más combinaciones posibles), Lee Sedol.

> Además, el Deep Learning supone la base tecnológica de distintas funcionalidades de varios productos de Google, y de otras grandes empresas tecnológicas. Pero, ¿qué es el 

### Deep Learning y en qué puede aplicarse? Forbes lo explica en un interesante artículo.
### Diferencias entre Inteligencia Artificial, Machine Learning y Deep Learning

### La Inteligencia Artificial (IA) 
Es un subcampo de la informática que se creó en la década de 1960, y que trata de solucionar tareas que son sencillas para los seres humanos, pero difíciles para las computadoras. Se trata de un concepto bastante genérico e incluye todo tipo de tareas tales como la planificación, el reconocimiento de objetos y sonidos, hablar, traducir, realizar actividades creativas (como por ejemplo crear obras de arte, o la poesía), etc.

El Machine Learning o aprendizaje automático se ocupa de un aspecto de la IA 
Dado un problema de IA que se puede describir en términos discretos (por ejemplo, dado un conjunto de posibles acciones para un determinado objetivo, cuál es la correcta), y disponiéndose de una gran cantidad de información sobre el mundo, se determina cual es la acción "correcta", sin que el mecanismo de elección se encuentre previamente programado. Es decir, el sistema aprende de forma autónoma a tomar las decisiones. De forma práctica esto se traduce en una función en la que a partir de una entrada se obtiene una salida, con lo que el problema radica en construir un modelo de esta función matemática de forma automática. Por lo tanto, la principal diferencia radica en que un programa muy inteligente que tiene un comportamiento similar al humano puede ser IA, pero a menos que sus parámetros se aprendan automáticamente a partir de los datos, no es Machine Learning.

### Machine Learning
>Aunque los términos se utilizan a veces como sinónimos, el Deep Learning y el Machine Learning no son lo mismo, siendo el primero un tipo particular del segundo, es decir, el Deep Learning es Machine Learning, pero existen técnicas de Machine Learning que no son Deep Learning.

El Machine Learning, como se ha visto, se describe a menudo como un tipo de técnicas de Inteligencia Artificial  donde las computadoras aprenden a hacer algo sin ser programadas para ello. Por poner un ejemplo sencillo, se podría programar un ordenador para identificar a un animal como un gato escribiendo un código que indique al programa que elija "gato" cuando se ve una imagen concreta de un gato. Esto funcionaría si el único gato con el que tratase el programa es el de esa imagen, pero no lo haría si el programa tuviera que ver un montón de imágenes de diferentes animales, incluyendo una gran cantidad de gatos, y tuviera que identificar cuáles de ellas representan a un gato.

Los programas de Machine Learning actuarían en ese segundo caso, para lo cual pueden entrenarse de diferentes maneras. En una de ellas al programa se le muestra una gran cantidad de imágenes de diferentes animales (etiquetadas con el nombre del animal correspondiente). El programa aprenderá que los animales que se parecen a los gatos se llaman "gato" sin haber sido programado para llamar "gato" a una imagen concreta de un gato. Para ello el programa debe aprender combinaciones de características visuales que tienden a aparecer juntas (por ejemplo, la forma de los cuerpos y de las caras), haciendo a los gatos visualmente diferentes de otros animales. El programa aprende a asociar esta combinación de características distintivas con la palabra "gato", proceso de aprendizaje conocido como “construcción de un modelo de un gato”.

Una vez que se ha construido el modelo de “gato”, un programa de Machine Learning prueba dicho modelo al tratar de identificar a los gatos en un conjunto de imágenes que no ha visto antes. El programa mide el éxito obtenido en la identificación de los nuevos gatos y utiliza esta información para ajustar el modelo, de forma que la próxima vez obtendrá mejores resultados. Es decir, el nuevo modelo se prueba, se evalúa su rendimiento, y se realiza otro ajuste. Este proceso iterativo continúa hasta que el programa haya construido un modelo que pueda identificar gatos con un alto nivel de precisión.

Si el entrenamiento es “supervisado”, en cada paso iterativo de prueba y perfeccionamiento del modelo se compara la etiqueta asignada a la foto con la “decisión” tomada por el programa, determinando si ha identificado el tipo de imagen correctamente. El entrenamiento supervisado es relativamente rápido y necesita relativamente pocos recursos computacionales. Sin embargo necesita de la intervención humana para etiquetar las ingentes cantidades de información requeridas para el entrenamiento, lo cual supone un proceso lento y costoso.

### Deep Learning
El Deep Learning lleva a cabo el proceso de Machine Learning usando una red neuronal artificial que se compone de un número de niveles jerárquicos. En el nivel inicial de la jerarquía  la red aprende algo simple y luego envía esta información al siguiente nivel. El siguiente nivel toma esta información sencilla, la combina, compone una información algo un poco más compleja, y se lo pasa al tercer nivel, y así sucesivamente.

Continuando con el ejemplo del gato, el nivel inicial de una red de Deep Learning podría utilizar las diferencias entre las zonas claras y oscuras de una imagen para saber dónde están los bordes de la imagen. El nivel inicial pasa esta información al segundo nivel, que combina los bordes construyendo formas simples, como una línea diagonal o un ángulo recto. El tercer nivel combina las formas simples y obtiene objetos más complejos cómo óvalos o rectángulos. El siguiente nivel podría combinar los óvalos y rectángulos, formando barbas, patas o colas rudimentarias. El proceso continúa hasta que se alcanza el nivel superior en la jerarquía, en el cual la red aprende a identificar gatos.

>¿Por y para qué es útil el Deep Learning?
>El Deep Learning ha llamado mucho la atención por su potencial utilidad en distintos tipos de aplicaciones en el “mundo real” (pueden aplicarse con éxito a grandes volúmenes >de datos para el descubrimiento y aplicación de conocimiento, así como a la realización de predicciones a partir de él), principalmente debido a que obtiene tasas de éxito >elevadas con entrenamiento “no supervisado”. En el caso del ejemplo, las redes de Deep Learning aprenderían a identificar gatos aunque las imágenes no tuvieran la etiqueta >"gato”.

A continuación se muestran algunos de los principales problemas “reales” en los que distintas compañías están aplicando Deep Learning en la actualidad:

Utilización de imágenes en lugar de palabras clave para buscar productos de una empresa, o artículos similares.

Identificar marcas y logotipos de empresas en fotos publicadas en redes sociales.

Monitorización en tiempo real de reacciones en canales online durante el lanzamiento de productos.

Orientación de anuncios y predicción de las preferencias de los clientes.

Identificación y seguimiento de los niveles de confianza de los clientes, sus opiniones y  actitud en diferentes canales online y servicios de soporte automatizado al cliente.

Identificación de clientes potenciales.

Detección de fraudes, recomendaciones a clientes, gestión de relaciones con los clientes, etc.

Mejor comprensión de enfermedades, mutaciones de enfermedades y terapias genéticas.

Análisis de imágenes médicas, como radiografías y resonancias magnéticas, aumentando la precisión diagnóstica, en un menor tiempo y con un menor coste que los métodos tradicionales.

Exploración de la posibilidad de reutilización de fármacos ya conocidos y probados para su uso contra nuevas enfermedades.

Detección, predicción y prevención de amenazas sofisticadas en tiempo real en el campo de la ciberseguridad.

Identificación en textos de sentimientos positivos y negativos, temas y palabras clave.

Localización de caras e identificación de emociones faciales.

Reconocimiento de voz.

Clasificación de vídeos.

Y muchas más.

El descubrimiento y reconocimiento de patrones en el mundo que nos rodea es un factor fundamental en los progresos científicos y tecnológicos actuales. La cuestión ahora es cómo utilizar el Deep Learning para obtener nuevos conocimientos, o para mejorar lo que se está haciendo... en definitiva, para innovar.
