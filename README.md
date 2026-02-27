## 💻 Cómo ejecutar el proyecto

Dado que es un archivo estático, la ejecución es inmediata:

1. Descarga o clona este repositorio/archivo.

2. Asegúrate de tener conexión a internet (para cargar las librerías CDN de Tailwind y Chart.js).

3. Haz doble clic en el archivo `canvas_dss_interactivo.html` para abrirlo en tu navegador web moderno preferido (Chrome, Firefox, Edge, Safari).

4. *¡Listo!* Puedes comenzar a interactuar con los sliders en la sección "Matriz MCDA".

## 🗂️ Estructura del Código

El archivo HTML único está dividido en las siguientes secciones lógicas:

* `<nav>`: Barra de navegación superior fija.

* `<header id="hero">`: Introducción y gancho visual de la presentación.

* `<section id="contendientes">`: Tarjetas informativas de las 3 herramientas.

* `<section id="matriz">`: Interfaz principal del modelo MCDA con los sliders de entrada y el gráfico de barras dinámico.

* `<section id="analisis">`: Gráfico de radar y análisis cualitativo profundo (Alteryx vs. Palisade).

* `<script>`: Contiene los arrays de datos, la configuración de *Chart.js* y la función `updateCalculations()` que recalcula los puntajes en base a eventos de tipo `input`.

*Desarrollado como un caso de estudio para la Selección de Sistemas de Soporte a la Decisión (DSS).*