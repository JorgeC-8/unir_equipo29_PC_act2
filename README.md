# Conteo de palabras en páginas de libros

Un algoritmo que cuenta las palabras en una página de un libro utilizando filtros espaciales y morfológicos.

## Objetivos 

El objetivo de este trabajo es buscar y analizar los filtros espaciales y morfológicos más habitualmente usados en la literatura. Esto permitirá consolidar los conceptos y operaciones sobre imágenes aprendidas en teoría.

## Descripción

Las operaciones espaciales tienen en cuenta las relaciones de vecindad entre los píxeles para aplicar diferentes tipos de mejoras a la imagen. Las operaciones morfológicas simplifican imágenes y conservan las principales características de los objetos. Los estudiantes deben analizar los filtros estudiados en clase y compararlos con otros que se estén usando actualmente para resolución de problemas reales. Pueden buscar e investigar en paquetes de imagen de Python como Skimage, OpenCV, Mahotas, PIL, etc. La solución se implementará en un notebook Python que describirá y mostrará en pantalla los resultados de los principales pasos. En caso de que se utilice partes de un software existente, deberá referenciarse la fuente.  

La solución aportada no debe ser básica: repetición de una solución bien conocida o existente en una librería. Se pueden utilizar funcionalidades proporcionadas por las librerías, pero la implementación de la operación principal debe ser propia. No se permite copiar código de Internet. En caso de que se reutilicen ideas deberá referenciarse la fuente.


## Forma de entrega

Han de entregarse dos documentos. Primero, un notebook de Jupyter con la solución propuesta y los ficheros adicionales que se necesiten para ejecutarlo. Segundo, un informe donde se explique el problema o contexto donde se han implementado los diferentes filtros, cuáles de estos filtros (LP, HP, detección de bordes, morfológicos, diferentes combinaciones de los anteriores, etc.) han sido empleados y por qué, los resultados obtenidos y unas conclusiones. Se puede incluir bibliografía. 

Extensión máxima del informe: 6/8 páginas. 

NOTA: la elección de las imágenes es decisión del alumno. Se recomienda que busque y utilice imágenes de su ámbito profesional (médicas, industriales, etc.) o de su interés personal. También puede usar imágenes tomadas con su cámara o celular.

## Iniciando

### Dependencias

* Jupyter
* Matplotlib
* OpenCV 2
* Numpy
* LaTeX con XeLaTeX+MakeIndex+BibTeX

### Instalación

* Descargar estas imágenes:

[book1.bmp](https://drive.google.com/open?id=16TUDtcGv03bB8xZgsyRn7zvy7MHO2JAM&authuser=rodoart%40ciencias.unam.mx&usp=drive_fs)
[logo.png](https://drive.google.com/open?id=1OOxaBDZCA2rtHLkpDIcnaULH_j_jmXX-&authuser=rodoart%40ciencias.unam.mx&usp=drive_fs)

* Instalar _book1.bmp_ en _notebook/pictures_.
* Instalar _logo.png_ en _tex/figures_


### Ejecutando el programa.
* Jupyter para abir notebook/act2.ipynb
* Latex para compilar tex/act2.tex
