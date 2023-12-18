## Herramienta de Anotación de Imágenes
### Objetivo

Desarrollar una aplicación web para anotar imágenes, similar a una herramienta de etiquetado de imágenes. La aplicación debe permitir a los usuarios iniciar sesión, seleccionar y anotar imágenes, y guardar estas anotaciones en una base de datos. Las imágenes deben almacenarse en un servicio S3.

### Requisitos Técnicos
1. Framework y Lenguaje
Lenguaje de Programación: Python.
Framework Web: FastAPI, Django, o cualquier otro framework web de su elección.
2. Autenticación de Usuarios
La aplicación debe manejar usuarios y contraseñas.
Los detalles de los usuarios deben almacenarse en una base de datos segura.
3. Almacenamiento de Imágenes
Las imágenes deben almacenarse en un servicio S3.
La aplicación debe permitir cargar y recuperar imágenes desde S3.
4. Galería de Imágenes y Herramienta de Anotación
Implementar una galería de imágenes donde los usuarios puedan seleccionar imágenes para anotar.
La herramienta de anotación debe incluir un selector tipo canvas para capturar coordenadas X e Y con un clic.
Incluir un cuadro de texto para que los usuarios indiquen la acción o etiqueta relacionada con la anotación.
5. Base de Datos
Almacenar la información de las coordenadas y texto de las anotaciones en una base de datos.
La estructura de la base de datos debe ser diseñada para optimizar la recuperación y el almacenamiento de datos de anotaciones.
6. Interfaz de Usuario
La interfaz debe incluir botones para "Guardar" y "Rechazar" anotaciones.
Incluir una sección de instrucciones para guiar a los usuarios en el proceso de anotación.
7. Funcionalidades Adicionales
Implementar medidas de seguridad para proteger la información de los usuarios y las imágenes.
La aplicación debe ser responsiva y fácil de usar en diferentes dispositivos.

### Criterios de Evaluación


* Funcionalidad: La aplicación debe cumplir con todos los requisitos mencionados.
Diseño de la Base de Datos: Eficacia en el manejo de datos de usuarios e imágenes.
* Usabilidad: Facilidad de uso de la interfaz de usuario.
Calidad del Código: Claridad, mantenibilidad y uso de buenas prácticas de programación.
* Seguridad: Implementación de medidas de seguridad para proteger datos sensibles.

### Entrega

El código fuente debe ser entregado en un repositorio diferente (compartir link)
Incluir un README detallado con instrucciones para configurar y ejecutar la aplicación.
Documentar el diseño de la base de datos y cualquier decisión importante de arquitectura.
