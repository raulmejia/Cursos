
'https://github.com/jtleek/genstats'  
'https://simplystatistics.org'

* Confiabilidad de paquetes para R:  
  1. Pagina del Autor
  2. Github
  3. mejor R-cran
  4. Bioconductor (No solo "corren", si no peer-review, informacion sobre el porcentaje de descargas y respuestas de los autores )  
  
* Foros
  1. Biostars
  2. Bioconductor soport-page (supponrt.bioconductor.org)
  3. Stackoverflow  
  4. 
  
#Hacer Preguntas sobre R
* Que pasos reproducen el problema? (Ej. medico "Yo/Mi primo esta enfermo pero no se ni que siento/ ni que me molesta")
* Cual es el "resultado" esperado?
* Que obtuviste en cambio?
* Que version del producto estas usando R, paquete?
* Sistema operativo?

#Preguntas sobre analisis de datos
* Cual es la pregunta que tratas de resolver?
* Que herramientas/pasos usaste para responderla?
* Que es lo que esperas ver?
* Que obtienes en cambio?
* Que otras soluciones haz pensado al respecto
* 'En general habla del fin ultimo de lo que quieres hacer'

#Ejemplo:
1. Ayuda! no puedo hacer ni entender modelos lineales en R y los necesito para  mi trabajo de ma;ana.
2. R version 3.1.2, limma() me produce un error cuando intento cargar mi base de datos la cual fue creada en excel.
3. Debian GNU/Linux 7.8 (wheezy), R version 3.1.2, limma(),  Error: no se pudo encontrar la función "limma"

#Datos crudos vs procesados
* Datos crudos (no hay computo de por medio)
* conjunto de datos "en orden".

# Reproducibilidad
Cuando la reproducibilidad es una cuestion etica?  
'http://www.birs.ca/events/2013/5-day-workshops/13w5083/videos/watch/201308141121-Baggerly.mp4'
* Que necesito para la reproducibilidad
1. Los DATOS, Como compartir los datos? 'https://github.com/jtleek/datasharing'
  1. Datos crudos, "tal como tu los recibes".
  2. Los datos ya organizados, listos para ser usados y compartidos.
  3. El "code book" que explique las variables utilizadas, su nomenclatura, como se obtuvieron, unidades y cualquier peculiaridad del dise;o del estudio.
  4. El "recipe" (receta) es un pipeline al cual le das los "datos crudos" y te devuelve tus "datos procesados". incluso si no tienes el script como tal, puedes hacer un texto que describa el algoritmo. (No puedes decir use el software "X" por que el software "X" cambia).
2. Compartir el Software:
  1.  Codigo "crudo" de R. (bien comentado por favor).
  2.  "Literate programming" (in R markdown document http://rmarkdown.rstudio.com) in python (iphyton notebook)
