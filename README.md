Proyecto: Interfaz Inteligente de Soporte a Decisiones de Marketing en E-commerce mediante Aprendizaje Automático 
¿Qué hace el proyecto?
Este proyecto tiene como propósito principal desarrollar una Interfaz Web intuitiva y robusta para el soporte a la toma de decisiones estratégicas en el área de Marketing de empresas de Comercio Electrónico. Aborda la problemática de los grandes volúmenes de datos dispersos y poco estructurados que generan las plataformas e-Commerce , los cuales dificultan el análisis estratégico y la toma de decisiones oportunas.



Características principales:

Visualización de información clave: Permite visualizar datos importantes por producto, categoría, precio, descuentos, rating y opinión del cliente.
Procesamiento con modelos de analítica de datos: Genera predicciones, segmentaciones y recomendaciones sobre la venta de productos utilizando Machine Learning (ML).

Soporte a la toma de decisiones en tiempo real: Apoya a los equipos de marketing a anticipar comportamientos del mercado, personalizar estrategias comerciales y optimizar recursos.

Interfaz predictiva: Diseñada en Python utilizando Gradio, permite seleccionar el modelo deseado e ingresar valores para realizar predicciones en tiempo real para clasificación y regresión.
¿Para quién está dirigido?
Este proyecto está dirigido a equipos de marketing y negocios en empresas de e-commerce que buscan transformar datos en conocimiento útil para la toma de decisiones y mejorar su eficiencia operativa.

¿Cómo puedo usarlo o instalarlo?
Requisitos previos
Se utilizó Python para el desarrollo de este proyecto, incluyendo librerías para Machine Learning y Gradio para la interfaz. Asegúrate de tener un entorno Python configurado.

Instalación
El proyecto se basa en un notebook de Colab.

Uso
El proyecto incluye una interfaz desarrollada con Gradio que permite interactuar con los modelos de regresión y clasificación.

Ejemplos de Uso:

Predicción de precio real (Regresión): Permite estimar el precio real de un producto basándose en el precio con descuento, calificación, grupo de precio y si incluye video. Por ejemplo, con un precio con descuento de 100, calificación de 3.5, grupo de precio 1, y sin video, se estimó un precio real de 113.17 euros.

Clasificación de producto exitoso/no exitoso: Permite predecir si un producto será exitoso (rating >= 4) o no exitoso (rating < 4). Se usan variables como puntaje de emoción, rating, título de emoción y si es un producto para el hogar. Por ejemplo, con puntaje de emoción 2, rating 3.5, título de emoción 1 y siendo un producto para el hogar (1), el resultado fue “Producto no exitoso”.



¿Cómo puedo contribuir?
Aunque el documento no detalla un proceso específico de contribución, al ser un proyecto de GitHub, las contribuciones pueden seguir las prácticas estándar:

Reportar errores o sugerir mejoras: Abre un "Issue" en el repositorio de GitHub.
Enviar Pull Requests: Si deseas contribuir con código, bifurca el repositorio, realiza tus cambios y envía un Pull Request.
¿Qué tecnologías o herramientas se utilizaron?
Lenguajes de Programación: Python.
Librerías y Frameworks (Machine Learning): Se utilizaron diversos modelos de Machine Learning para regresión (LinearRegression, Ridge, Lasso, K-Nearest Neighbors, Random Forest Regressor, Gradient Boosting Regressor)  y clasificación (Regresión Logística, K-Nearest Neighbors, Árbol de Decisión, Soporte Vectorial, Random Forest Classifier, Gradient Boosting Classifier).

Interfaz de Usuario: Gradio.
Herramientas de Diseño de Mockups/Wireframes: Figma o Balsamiq.

¿Quién es el autor o equipo?
Este proyecto fue desarrollado por estudiantes de la Universidad Nacional Mayor de San Marcos , de la carrera de Ingeniería de Sistemas de Software , bajo la supervisión del docente Víctor Manuel Cabrejos Yalán.

Equipo numero 03

¿Qué licencia tiene el proyecto?
El documento proporcionado no especifica una licencia. Se recomienda añadir una licencia al repositorio para indicar cómo otros pueden usar, modificar y distribuir tu código.

¿Dónde puedo obtener soporte o más información?
Issues de GitHub: Puedes usar la sección de "Issues" del repositorio para hacer preguntas o reportar problemas.
Documentación adicional: El informe completo del proyecto proporciona detalles sobre el procesamiento de datos, modelado y evaluación.
Estado del Proyecto y Próximos Pasos
El proyecto se encuentra en una fase de desarrollo avanzada, con modelos entrenados y una interfaz funcional para demostración. El informe detalla un "Flujograma del Proceso a Mejorar" (AS IS y TO BE)  y mockups del producto final, lo que indica una visión clara para futuras iteraciones.
