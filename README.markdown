Traducción del libro "Scala by Example" al español
==================================================

**Scala by Example** (_Scala a través de Ejemplos_), hace parte de la 
documentación oficial sobre el lenguaje de programación Scala. 
Esta es la traducción al idioma español de este interesante libro.


Acerca de Scala y el libro
--------------------------

Scala es un lenguaje de programación **funcional**/**orientado a objetos**, que
trabaja sobre la Máquina Virtual de Java (**JVM**). Nació como parte del trabajo
de _Martin Odersky_, profesor de la _École polytechnique fédérale de Lausanne_ 
(EPFL) en Suiza.

Se creó a raíz de la frustración que es programar en Java. Esto hizo que Scala
se diseñara con la facilidad de programación en mente, por lo que su sintaxis 
es muy sencilla, también, al ser Orientado a Objetos, es muy sencillo para un 
programador experto en Java hacer el salto hacia el lenguaje, 
pero ya que también está orientado hacia la programación funcional, 
muchas veces usar dichas capacidades puede ser 
"traumático" para el programador inexperto en este paradigma.

Por eso, _Scala by Example_ es uno de los libros de referencia cuando se está
aprendiendo este maravilloso lenguaje de programación, ya que lo introduce 
a partir de ejemplos, de forma completa, y fiel al lenguaje (de forma pragmática), 
con ejemplos muy conocidos, y con otros no tanto, pero que serán útiles 
y hasta cruciales a la hora de enfrentar verdaderos retos a futuro.



Sobre la programación funcional
-------------------------------

¿Estás interesado en Scala, pero no entiendes/te da pereza/te vuelve loco(a) 
la programación funcional (Conocido también como _paradigma declarativo_)?

No sufras más, y lee: 
**https://ademirar.wordpress.com/2010/08/28/programacion-funcional-para-el-resto-de-nosotros/**


FAQ:
----

* **¿Dónde puedo descargar el PDF?**: El libro aun está en traducción, por lo 
  que si quieres leerlo en PDF, deberás descargar el repositorio y hacerlo tú, 
  usando **Sphinx**, y el comando ``make latexpdf``. El PDF se generará 
  dentro de carpeta llamada _build_, y luego dentro de _latex_.
  En la sección de descargas de GitHub también hay un PDF, pero ten la certeza 
  de que estará desactualizado.

* **Si el original está en LaTeX, ¿Por qué se está escribiendo en .rst?:** 
  El libro lo estamos escribiendo usando la sintaxis _reStructuredText_, para 
  luego generar el PDF usando **Sphinx**, o **rst2pdf**.
  Usar el latex original nos ha traído muchas complicaciones a la hora de 
  compilarlo por cuestiones con los _fonts_ que se usan, etc.
  El que usemos _reStructuredText_ nos permite poder exportar el documento a 
  muchos otros medios, como el PDF ya mencionado, a páginas web, e incluso, 
  también a LaTeX.
  También, está el "plus" de poder colorear la sintaxis del código de los
  ejemplos del libro.
   
   
* **¿Cómo puedo colaborar?:** ¡¡Haz un folk de este repositorio!!, por favor,
  cuando empieces o te detengas de traducir un capítulo, avísanos desde un 
  issue, y haz una **solicitud de Pull** una vez lo tengas terminado (o si 
  definitivamente no lo vas a terminar, pero has adelantado algo).


* **¿Qué necesito para editar el texto?:** Cualquier editor de texto está bien,
  siempre y cuando tengas buena ortografía... en otro caso, es preferible 
  uno con corrección ortográfica para asegurar la calidad del documento.
  También deberías conocer la sintaxis de _reStructuredText_: 
  http://docutils.sourceforge.net/docs/user/rst/quickref.html
  O también:
  http://openalea.gforge.inria.fr/doc/openalea/doc/_build/html/source/sphinx/rest_syntax.html

* **¿Cuándo podré generar un LaTeX con estos archivos?:** ¡Puedes hacerlo ya 
  mismo!. Si tienes el programa **Sphinx** instalado y bien configurado, 
  con un sencillo ``make latex`` podrás general el LaTeX del libro.

* **¿Alguna pregunta?:** Con toda confianza, puedes preguntar desde un issue.



--------------------------

_Ultima modificación: vie 10 ago 2012 13:28:42 COT_
