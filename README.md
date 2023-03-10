# ingeodata-test-moreno

# Descripción Proyecto

Se debe desarrollar una librería en Python que tenga al menos la implementación de 3
cálculos básicos de la estadística, por ejemplo, la media y al menos 1 gráfica que muestre
los datos (gráficas de tipo: barras, torta, etc)
Esta librería debe ser luego usada en un proyecto en Django que permita:

- Subir un archivo tipo .csv o .xls
- Usar los cálculos de la librería implementada
- Mostrar el dataset y los resultados de los cálculos y la gráfica en una vista web

NOTA: Ya que debe usar un dataset (.csv o .xls) para realizar la implementación le
recomendamos que escoja y use un dataset de https://www.kaggle.com/ relacionado con oil
& gas.

# Arquitectura del proyecto

- Version python: Python 3.10
- Entorno virtual: virtualenv 20.16.3
- Nombre del Proyecto: ingeodata-test-moreno
  - Version Django: Django 4.1.6
  - Archivo requirements.txt: Contenido de las librerias utilizadas
- Folder estadistica: Es la carpeta que contiene las librerias desarrolladas para la el proyecto, se uso esta libreria en el entorno virtual
  - ruta ingeodata-test-moreno\env\Lib\site-packages

Nota: Se realiza el adjunto del archivo de manera local para esta prueba, en caso de realizarse de alto nivel es recomendable utilizar base de datos para la manupulación de la información y el procesamiento de datos.

# Dataset cargado

Info: Se descarga el dataset desde la pg https://www.kaggle.com/datasets/thedevastator/gb-electrical-grid-half-hourly-data-2008-present

Archivos dataset de prueba nombre

- espeni.xls
- espeni.csv

# Test

En la carpeta testunitario se aloja imagenes de las diferentes pruebas realizdas de la libreria creada
