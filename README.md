# Scrapy-con-Python
# Scrapy-con-Python
 Se crea Aplicación de web scraping con Scrapy, un framework en Python diseñado para extraer datos de sitios web. Pasos y componentes de la app:

1. Instalación y Configuración Inicial
Instalación de Scrapy: comando para instalar Scrapy en el entorno de desarrollo.
Creación del Proyecto: Inicio nuevo proyecto llamado scrapy01 con scrapy startproject scrapy01.
Estructura del Proyecto: estructura predeterminada que incluye directorios y archivos para configuraciones, middlewares, pipelines y spiders.
2. Generación del Spider
Nombre del Spider: Se genera un spider llamado quotes.
URL Objetivo: Se especifica la URL como el punto de partida para la extracción de datos.
3. Configuración del Spider
Definición de la Lógica de Extracción:editar el archivo quotes.py en el directorio scrapy01/spiders.
Definir cómo se debe extraer las citas y sus autores del sitio web.
Uso de Selectores: Uso selectores CSS para navegar y extraer datos de los elementos HTML relevantes en la página web.
5. Ejecución del Spider
Comando de Ejecución: ejecutar el spider con el comando scrapy crawl quotes -o quotes.json.
Salida de Datos: guarda en un archivo quotes.json en el directorio del proyecto.
6. Resultados y Registro de Actividades
Registro de Eventos: Scrapy genera un registro detallado de eventos que incluye el inicio del bot, las solicitudes y respuestas HTTP, y los datos extraídos.
Datos Extraídos:el archivo quotes.json contiene las citas y sus autores en formato JSON.
Estadísticas del Proceso: El log de ejecución proporciona estadísticas como el número de páginas rastreadas, elementos extraídos, y el tiempo total de ejecución.
7. Configuraciones Predeterminadas
Archivo settings.py: Las config básica de Scrapy, obediencia a robots.txt y la codificación de exportación de feeds, se mantuvieron en su mayoría sin cambios.
Extensiones y Middlewares: Se utilizaron las extensiones y middlewares predeterminados de Scrapy para manejar las solicitudes y la extracción de datos de manera eficiente.
Conclusión
La aplicación desarrollada es un ejemplo eficiente y básico de cómo utilizar Scrapy para realizar web scraping. A través de la instalación, configuración, generación de spiders, y ejecución de comandos, se logra extraer datos de un sitio web específico y almacenarlos en un archivo JSON.
