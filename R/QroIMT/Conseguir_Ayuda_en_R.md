##Encontrar respuestas:

###Buscar en la web:
* "Googlea" el mensaje de error
* Buscar en los Foros (stackoverflow, stackexchange, etc...)
* Leyendo un FAQ

### Leer un libro, manuales, documentos.
### Leer los archivos de ayuda pre-incluidos en nuestra version de R.
* Accesamos a esta ayuda anteponiendo el signo "?" a nuestro comando, por ejemplo para el comando "rnorm"
  `?rnorm `
* Buscar archivos de ayuda: (No es necesario tener el nombre EXACTO entre comillas)
    `help.search("rnorm")`
* Conocer los argumetos del commando:
  `args("rnorm")`
* Para ver el código fuente:  (tecleamos el nombre del comando omitiendo los paréntesis "()" al final)
  `rnorm`
* Conocer un poco más acerta de "miobjeto" en R:
  1. Cual es su "mode":
  `mode(miobjeto)`  
  2. cual es su clase "class"
  `class(miobjeto)` 
  3. `str(miobjeto)`
  4. `summary(miobjeto)`
  [Funciones útiles](http://cran.r-project.org/doc/contrib/Short-refcard.pdf)  


###"Postear" a la lista de correos de R (R-help NO R-devel) o Stackoverflow
###Por inspección / experimentación
  Por ejemplo: cambiando las entradas si se trata de una función.
###Leyendo el código fuente.
###Pregutarle a un amigo con más experiencia:
  * ¿Cómo preguntar?  / ¿cómo NO preguntar?
  * ¿Qué pasos reproducen el problema?
  *  ¿Cuál es el resultado esperado y que es lo que obtienes en cambio?
  *  Versión del paquete y versión de R 
  *  ¿Qué Sistema operativo?
  *  Comentar las cosas que has intentado previamente.
  *  Ejemplos:


  1. "Ayuda!!, tengo un error y no puedo cargar mi base de datos en el lenguaje R y son para mi trabajo de mañana".
  2. R 3.1.1, error al cargar mis datos con lumi() , mi sistema operativo es  Debian 3.2.65 x86_64 GNU/Linux
  3. R 3.1.1, función lumi() en Debian 3.2.65 x86_64 GNU/Linux,  $Error: there is no package called ‘lumi’

#### Recomendaciones:
  * Describe el objetivo último (Así podrán explicarte distintas soluciones).
  * Se explicito.
  * Se conciso
  * Se cortés (Nunca duele)
  * Sigue el post (sus respuestas y soluciones) 
  * Usa los foros en lugar del correo

#### Advertencias:
  * Gritar que has encontrado un "error" en el software (99% de las veces no lo es).
  * No Pedir en los foros que (literalmente) resuelvan tu tarea de la escuela.
  * Cuando busques respuestas es importante comentar lo que has intentado.

# Este documento esta basado en:
* Posting guide de R: http://www.r-project.org/posting-guide.html
* Eric Raymond ("How to  ask questions the smart way")

### Sitios recomendados para aprender mas sobre R:
* https://es.coursera.org/course/rprog
* https://cran.r-project.org/
* http://swcarpentry.github.io/r-novice-inflammation/
* http://stackoverflow.com/questions/6853204/plotting-multiple-curves-same-graph-and-same-scale


