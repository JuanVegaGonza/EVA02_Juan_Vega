# EVA02_Juan_Vega
Evaluación 2
[CUY6142_EVA02_Juan_Vega.docx](https://github.com/user-attachments/files/23011840/CUY6142_EVA02_Juan_Vega.docx)
Introducción
Este informe documenta el desarrollo de dos soluciones tecnológicas para la Biblioteca Nacional:

Gestión de catálogo de libros mediante una API REST usando Postman y Python.

Software de geolocalización mejorado con Graphhopper Directions API.
Se utilizaron herramientas como Postman, Python, Git/GitHub y la máquina virtual Devasc para cumplir con los requerimientos.

Desarrollo de los Requerimientos
1. Gestión de Biblioteca con Postman y APIs
🔹 Paso 1: Creación de los 3 libros iniciales
Se utilizó Postman para enviar solicitudes POST a la API de la biblioteca.

Cada libro se creó con los siguientes datos:

Libro 1:

ID: 5

Título: "Guía de Estudio Para la Certificación Ccna Security"

Autor: Juan Vega

ISBN: RUT sin puntos ni guion

Libro 2:

ID: 6

Título: "Redes Cisco. CCNA Routing y Switching."

Libro 3:

ID: 7

Título: "Redes Avanzadas 1. DEVNET."

✅ Evidencia: Capturas de pantalla de Postman con código de estado HTTP 200 para cada creación.

🔹 Paso 2: Verificación de libro agregado
Se realizó una consulta GET a la API para verificar la creación del Libro 2.

Respuesta exitosa con datos del libro y código HTTP 200.

🔹 Paso 3: Actualización del Libro 1
Se envió una solicitud PUT o PATCH para actualizar el título del Libro 1 a:
"Guía de Estudio para la Certificación CCNA Security V2.0".

✅ Evidencia: Captura de pantalla con respuesta HTTP 200.

🔹 Paso 4: Consulta ordenada por autor con ISBN
Se realizó una consulta GET con parámetros para ordenar los libros por autor.

La respuesta incluyó el ISBN de cada libro.

🔹 Paso 5: Generación de 50 libros aleatorios con Python
Se escribió un script en Python que genera 50 libros con:

Títulos y autores aleatorios.

ISBNs numéricos únicos.

Se usaron librerías como random y requests para interactuar con la API.

✅ Evidencia: Captura del script y respuesta de la API con HTTP 200.

🔹 Paso 6: Listado total de libros
Se realizó una consulta GET para listar todos los libros creados.

Se verificó que los 50 libros aleatorios y los 3 iniciales estuvieran presentes.

2. Mejora del Software de Geolocalización con Python
🔹 Paso 1: Creación del script mejorado
Se creó un directorio con el nombre Juan_Vega.

Archivo: eva02_vega_graphhopper.py.

Traducción de todos los textos al español.

Formato de números con 2 decimales.

Opción de salida con "s" o "salir".

🔹 Paso 2: Narrativa del viaje en español
Se implementó la funcionalidad para mostrar instrucciones paso a paso en español.

Se mostró la ruta desde casa del estudiante hasta Duoc UC Sede.

✅ Evidencia: Captura de pantalla con la ruta y narrativa en español.

3. Control de Versiones con Git/GitHub
🔹 Paso 1: Creación del repositorio
Repositorio local y remoto: EVA02_JUAN_VEGA.

Subida del archivo eva02_vega_graphhopper.py.

🔹 Paso 2: Documentación
Se creó el archivo README_VEGA.md con:

Descripción del proyecto.

Instrucciones para ejecutar el script.

🔹 Paso 3: Enlace al repositorio
Enlace incluido en el documento de entrega:
https://github.com/[usuario]/EVA02_JUAN_VEGA

Conclusión
✅ Gestión de Biblioteca
Se logró interactuar exitosamente con la API REST usando Postman y Python.

Se crearon, actualizaron y listaron libros, incluyendo 50 libros generados automáticamente.

Todas las operaciones fueron validadas con respuestas HTTP 200.

✅ Planificador de Rutas
Se desarrolló una aplicación de geolocalización funcional y amigable en español.

Se implementaron mejoras como formato de decimales, narrativa de viaje y opción de salida.

Se mostró correctamente la ruta desde la casa del estudiante hasta la sede Duoc UC.

✅ Control de Versiones
Se utilizó Git y GitHub para el versionamiento y documentación del código.

El repositorio está disponible de forma pública y bien documentado.

Evidencias Adjuntas
Capturas de pantalla de Postman con códigos HTTP 200.

Script de Python para generación de libros y geolocalización.

Capturas de la ejecución del script de Graphhopper.

Enlace al repositorio de GitHub.
