# Instrucciones generales para hacer la memoria del TFG

Este documento contiene guías e ideas generales (no reglas) para
estructurar el Trabajo de Fin de Grado. Estas guías han sido creadas
tomando como partida las [instrucciones para TFGs de Carlos
León](https://github.com/cleongh/instruccionestfg)

Es fundamental tener en cuenta que la memoria va a ser la primera
impresión (y, junto con la presentación, la más relevante), y que el
tribunal se la mirará con detalle.

**La calidad de la memoria es esencial para aprobar el TFG.**

<!-- MarkdownTOC -->

- [Normativa TFG](#normativa-tfg)
- [Plantillas](#plantillas)
  - [Editores y plataformas](#editores-y-plataformas)
  - [LaTeX vs. Word](#latex-vs-word)
- [Portada y aspecto](#portada-y-aspecto)
- [Capítulos](#cap%C3%ADtulos)
  - [Resumen \(abstract\)](#resumen-abstract)
  - [Introducción](#introducci%C3%B3n)
  - [Capítulo del estudio del trabajo previo \(o "estado del arte"\)](#cap%C3%ADtulo-del-estudio-del-trabajo-previo-o-estado-del-arte)
  - [Capítulos de contribución](#cap%C3%ADtulos-de-contribuci%C3%B3n)
  - [Evaluación y discusión](#evaluaci%C3%B3n-y-discusi%C3%B3n)
  - [Conclusiones y trabajo futuro](#conclusiones-y-trabajo-futuro)
  - [Bibliografía](#bibliograf%C3%ADa)
- [Recomendaciones sobre la escritura del documento](#recomendaciones-sobre-la-escritura-del-documento)
- [Para revisar otros TFGs ya escritos](#para-revisar-otros-tfgs-ya-escritos)
- [Comunicación y revisiones](#comunicaci%C3%B3n-y-revisiones)
- [Fechas](#fechas)
- [Plagio](#plagio)

<!-- /MarkdownTOC -->




# Normativa TFG

Lo primero es leerse la [normativa del TFG del año que nos
toca](https://informatica.ucm.es/trabajo-de-fin-de-grado-y-sistemas-informaticos).
La normativa y el calendario suelen aparecer en los enlaces a la derecha
de la lista de trabajos del año en cuestión. Siempre hay información
relevante, entre la que destaca:

* Los plazos de entrega. De estos, el llamado "Entrega de la memoria
  final y de la autorización de difusión" es la fecha final en la que
  ya no se pueden hacer más cambios.
* Qué partes de la memoria hay que escribir en inglés.
* Hay que declarar la contribución de cada uno de los miembros,
  explicitando qué ha hecho cada uno. Se puede poner notas distintas a
  los miembros del grupo (aunque no es raro que se ponga la misma a
  todos).

# Plantillas

Para realizar la memoria es conveniente usar alguna de las plantillas
que hay disponibles. Actualmente un buen punto de partida son [las
plantillas para memorias de
TFM](https://informatica.ucm.es/trabajos-de-fin-de-master-ing-inf) que
aparecen en la página de los másteres (nuevamente, en el lado derecho):

* [Plantilla para
  Word](https://informatica.ucm.es/file/plantilla_tfg_word?ver)
* [Plantilla para
  LaTeX](https://informatica.ucm.es/file/plantilla_tfg_latex?ver)

Si vais a utilizar otras plantillas como [TeFloN](https://www.ucm.es/oficina-de-software-libre/file/teflon-x-c) revisad que el formato se aproxima a lo pedido en la normativa.

También podéis probar [otras alternativas](https://github.com/wikiti/pandoc-book-template) para escribir [la memoria en Markdown](https://github.com/tompollard/phd_thesis_markdown), pero de esto no hay aún plantillas. 

## Editores y plataformas

Podéis usar cualquier editor o plataforma. Google Docs o Word en Office365 tienen la ventaja de que la colaboración es trivial. En particular, Word permite de una manera muy cómoda y sin pérdida de formatos/estilos cambiar entre la versión de navegador y la de escritorio por lo que si vais a usarlo para escribir la memoria es mejor opción que Google Docs.

Para LaTeX se suelen usar editores genéricos (como [Visual Code](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) o [Sublime Text](https://latextools.readthedocs.io/en/latest/)) o propios (como [TexMaker](https://www.xm1math.net/texmaker/) o [TexStudio](http://texstudio.sourceforge.net/)). Otra alternativa es [Overleaf](https://www.overleaf.com/), para poder escribir de manera colaborativa. El inconveniente de este último es que se "pierde" el control de versiones (como se verá en la próxima sección).


## LaTeX vs. Word

Podéis usar la que queráis pero solemos recomendar que lo hagáis en
LaTeX porque:

* En LaTeX no hay que preocuparse de la maquetación del texto sino
  solo de escribirlo teniendo en cuenta unas marcas simples de
  sintaxis. Una vez compilado, el PDF quedará con un acabado
  profesional con muy poco esfuerzo.
* Los archivos .tex son código que se compila a PDF, por lo que se
  pueden meter dentro de un sistema de control de versiones (y ya
  conocéis la utilidad de los mismos para trabajo colaborativo)
* No sabéis tanto Word como creéis por lo que en muchas ocasiones no
  se usa correctamente la plantilla de Word y resulta muy engorroso
  hacer que todo quede con un acabado profesional.

La sintaxis de LaTeX es sencilla para lo que se necesita generalmente en
un TFG por lo que no es impedimento para empezar a trabajar con ello.

Si usáis la plantilla de Word utilizad correctamente los estilos, los
títulos y las referencias cruzadas, y el gestor bibliográfico. Si no lo
sabéis usar, entonces os recomendamos que hagáis el pequeño esfuerzo de
aprender LaTeX.

En la UCM también hay [cursos de Word y LaTeX a distintos
niveles](https://cursosinformatica.ucm.es/) con los que aprender lo que
necesitáis para hacer los TFGs (y, además, conseguir créditos
optativos).

# Portada y aspecto

Es necesario adaptar las portadas de las plantillas a la descripción de los
contenidos que aparece en la normativa.

# Capítulos

La memoria se estructura en varios capítulos. Generalmente, todos los capítulos (salvo el de "Introducción" y el de "Conclusiones y Trabajo Futuro") tienen uno o varios párrafos de introducción (que ayudan al lector a saber de dónde viene y qué es lo que se va a explicar en este capítulo) y una sección final, llamada Conclusiones, en la que se hace un breve resumen de lo visto en el capítulo y de las conclusiones más destacadas de lo que se ha contado en el capítulo. Cualquier lector debería poder entender (sin entrar a detalles técnicos)qué se ha hecho en el TFG solo leyendo las introducciones y las conclusiones de los capítulos.


Generalmente, hay 5 partes importantes que todo trabajo académico (no
sólo la memoria del TFG) tiene que contemplar. Lo normal es estructurar
el documento de forma que estas partes se correspondan con los siguientes
capítulos:

- Resumen
- Introducción
- Estado del arte o Estudio del Trabajo Previo
- Capítulo(s) de contribución
- Conclusiones y Trabajo Futuro

## Resumen (abstract)

Unos pocos párrafos que sirvan para que alguien no tenga ni idea de lo
que se está leyendo sepa: *cuál es el problema que se quiere resolver*,
*cómo se ha resuelto* y *cuáles han sido los resultados más
importantes*. Algo siguiendo estas ideas, pero más largo y detallado:

1.  El estado actual de la tecnología es \(X\).
2.  Sin embargo, la tecnología aún no hace \(Y\).
3.  Usando \(Z\), hemos hecho un sistema que hace \(Y\).
4.  Lo hemos montado y evaluado, con resultados \(R\).

### Palabras clave

Poned las *keywords*. Intentad ordenarlas por relevancia, y que sean
palabras clave que la gente suela buscar.

## Introducción

El capítulo de introducción Es útil empezar a escribir contando de forma general el
estado de la ciencia o la técnica en un punto dado, e introduciendo el
problema general por el que se trabaja. Es decir, antes de ir a las
subsecciones, escribir unos párrafos describiendo un poco con detalle el
estado actual del problema o la tecnología. Con seriedad, pero no con un
detalle total de cada cosa, ya que eso va en el siguiente capítulo.

### Motivación

La motivación es la razón **técnica** por la que se lleva a cabo un
desarrollo. La motivación describe por qué se hace el trabajo (por
ejemplo, se quiere mejorar la identificación automática de personas por
la imagen de su cara) y por qué se intenta, en particular, la solución
que se propone.

Es decir, hacéis el trabajo **por un motivo**, **porque vale para
algo**, y porque **la tecnología lo permite**.

### Objetivos

Una lista *concreta* de cosas que se quieren conseguir. Muchas veces
ayudará hacerlo como una lista con topos:

* Descubrir los números primos que acaben en 7
* Implementar un algoritmo que descubra las caras que se parecen a 7
* Hacer un experimento con caras reales

### Metodología y Plan de trabajo

Generalmente consiste en indicar la forma en la que se va a trabajar  indicando, entre otros:

- La metodología empleada (por ejemplo, sprints semanales usando scrum)
- Si hay reuniones periódicas
- La comunicación dentro del equipo
- Uso de repositorios para trabajo colaborativo
- ...

El plan de trabajo pretende definir cuál es la fecha aproximada en la que se van a cubrir los objetivos/tareas definidas. Este plan de cómo se van a repartir los recursos y el tiempo queda **también** muy bien con un [diagrama de Gantt](https://es.wikipedia.org/wiki/Diagrama_de_Gantt), aunque no tiene que ser tan técnico.

### Estructura del resto del documento

Esto es más una costumbre, pero ayuda. Algo del estilo de: "En el
capítulo 2 se estudiará el estado del arte. En el capítulo 3 se describe la..."

## Capítulo del estudio del trabajo previo (o "estado del arte")

Una parte lenta de hacer, pero muy importante. En esta parte se describe
todo el trabajo sobre el que se construye nuestra propuesta. Tiene que
tener muchas citas, y esas citas son *idealmente* artículos y libros
técnicos y científicos. Sólo en el caso de citar algo que no esté como
publicación clásica (un videojuego) se permite no ser tan riguroso.

Para acceder a este tipo de documentos os recomendamos que uséis [el buscador de la biblioteca](https://biblioteca.ucm.es/) y que hagáis búsquedas con términos en inglés. 

Esta parte se suele hacer muy al principio por lo que es recomendable que se vaya escribiendo a medida que se hace (si no, habrá que volver a hacer el trabajo al final del curso). Siempre que encontréis algo interesante haced un resumen con vuestras propias palabras y guardadlo junto con la referencia del documento del que ha salido. De esta forma será más fácil componer la memoria más adelante.

### Trabajos parecidos o relacionados

Aquí hay que hacer una revisión general de todo lo que se parezca a
nuestro trabajo.

### Tecnologías usadas en el trabajo

Aquí se describen los puntos importante de las tecnologías que usamos,
si es que hay algo interesante: librerías, algoritmos, plataformas... No
hay que poner imágenes con los logos ni contar cosas triviales (no hay
que explicar qué navegador de Internet usamos, a no ser que el proyecto
vaya de eso). No hay que describir `git` ni `scrum`.

## Capítulos de contribución

Esta parte puede ser un solo capítulo, aunque pueden (y suelen) ser más,
dependiendo de lo que se cuente. Es donde se explica lo que se ha hecho: la funcionalidad, la arquitectura, pruebas, experimentos, resultados... Idealmente, primero lo general y finalmente los resultados.

Una cosa muy normal es tener varios capítulos aquí. Por ejemplo:

- **Diseño funcional**: Qué es lo que hace lo que vamos a desarrollar. Nos podemos apoyar en bocetos y prototipos para explicar la funcionalidad o, incluso, en la versión final de la interfaz (si tiene) de nuestra aplicación.
- **Implementación**: Diseño arquitectónico de la aplicación, módulos que la componen, comunicación entre módulos, tecnología usadas... En este capítulo **no se ponen capturas de código** (a no ser que fuese algo fundamental sin lo cual no se entiende el desarrollo del proyecto) **ni capturas del árbol de directorios de nuestro proyecto** para definir la arquitectura. Usamos los diagramas UML adecuados que conocemos de otras asignaturas. 

## Evaluación y discusión

Un capítulo en el que contéis cómo habéis evaluado el sistema que habéis desarrollado. Empezad el capítulo esbozando la idea, y luego, posiblemente por secciones, detalláis lo que aparece a continuación. Si hay varios tipos de evaluación entonces se repiten estas secciones varias veces, definiendo cada una de las evaluaciones realizadas.

### Objetivo

Cuál es el objetivo de la evaluación, para qué lo queréis hacer. Se explica el qué se va a evaluar, no el cómo se va a evaluar, que se cuenta a continuación:


### Proceso de evaluación

Cuál es el método de evaluación, que vais a hacer para evaluar, cómo son los cuestionarios, qué pruebas se harán....

Qué experimentos se han hecho, cuántos usuarios, dónde, etc.

El contenido de este apartado depende de si se han hecho evaluaciones con usuarios y/o evaluaciones experimentales. 

### Resultados

Poner tablas, gráficas y números. Sin opinar de momento, sólo decir lo
que sale.

### Análisis de los resultados

Basándoos en la sección anterior, explicar qué significa que hayan
salido esos datos (sobre todo en función de los objetivos de la evaluación), y si los validan o la rechazan. Es muy normal que ni una cosa ni la otra, pero los datos deberían *dar indicios* en uno u otro sentido, cosa que se dice claramente.

### Discusión

Es una sección (o puede que sea un capítulo) en donde se *discute*, desde el punto de vista técnico, las ventajas y limitaciones de nuestro trabajo. No hay inconveniente por admitir explícitamente las limitaciones, sobre todo si esas limitaciones no las ha superado nadie. No hay que dejarse nada, todo lo que no se discuta será discutido con el tribunal durante la presentación, y eso suele ser algo más complicado que haberlo reflexionado durante el desarrollo del TFG.

## Conclusiones y trabajo futuro

El capítulo final es bastante esquemático. Se empieza con algo parecido
al *abstract*, pero centrándose más en los resultados. Se suele escribir de modo que se alinea con los objetivos de la introducción pero cambiando el modo en el que se describen e indicando las tareas realizadas y los resultados concretos. Por ejemplo, el Objetivo "Analizar diferentes técnicas para reconocer texto de manera automática" pasa a ser "Se ha hecho un estudio de diferentes librerías y algoritmos para el reconocimiento automático de texto" en las conclusiones. Puede parecer redundante, porque lo es, pero se espera que se cuente aquí.

Después se habla del Trabajo futuro, de lo que se podría hacer a partir de aquí, basándose en los resultados o en el producto de la implementación. Suele ser recomendable llevar una lista de cosas que pueden ser interesantes para incluir en el proyecto y que, si no se llegan a desarrollar, se incluyen en el trabajo futuro.

## Bibliografía

La bibliografía es **fundamental**. Hay que procurar no citar páginas
web, sino artículos científicos y libros (las páginas desaparecen, lo
otro está catalogado). Gestionar una bibliografía es un poco aburrido
pero con un gestor bibliográfico como [Zotero](https://www.zotero.org/) es más fácil. Google Docs y Word tienen plug-ins para integrar fácilmente Zotero. Word también incluye su propio gestor bibliográfico.

Si se citan páginas web (porque no se ha encontrado una referencia mejor) incluid siempre la fecha del último acceso. 

Generalmente, si se citan librerías o software específico, en lugar de una cita bibliográfica se suele poner una nota al pie de la página en la que se referencia.

Si tienes dudas, la biblioteca de la UCM tiene material sobre [como citar la bibliografía](https://biblioguias.ucm.es/elaborar-trabajos-academicos/citar-bibliografia) y también tenéis [guías de gestores bibliográficos](https://biblioguias.ucm.es/ingenieria-informatica/gestionar-bibliografia).

# Recomendaciones sobre la escritura del documento

- No se escribe en "personal". No se ponen nada  como "hemos aprendido mucho" o "he hecho...", es un documento técnico. Para  referirse a uno mismo, las fórmulas clásicas son usar la primera persona del plural ("hemos llevado a cabo"), o el impersonal ("se ha implementado...").
- En general, hay que tener cuidado con el tiempo verbal con el que se escribe. Generalmente en la intro se escribe "sobre lo que se va a hacer" y en las conclusiones "sobre lo que se ha hecho", por lo que el resto del texto puede estar en presente.
- Todas las imágenes y figuras tienen que ser útiles (nada de logos)
- Todas las imágenes, figuras, tablas y demás tienen que estar numeradas y referenciadas desde el texto, y tener un pie que describa perfectamente lo que se ve.
- Los títulos de capítulos y secciones tienen que ser descriptivos. No pongáis "contribución" o "prototipo". Poned "Desarrollo del sistema inteligente para hacer palomitas" o "Detalle de modelo computacional  del primer prototipo".
- Dentro de lo razonable, repetir cosas en varios sitios no es necesariamente malo. Es muy raro que alguien se lea un  documento técnico como se lee una novela, se va por secciones, se cambia de capítulo... Aunque no hay que exagerar esto, hay que asumir  que mucha gente se leerá las conclusiones casi lo primero.



# Para revisar otros TFGs ya escritos

Se han escrito ya muchos TFGs, y es muy útil que leáis TFGs ya escritos
para ver cómo se hacen. La [UCM publica todos los
TFGs de la Facultad de Informática](https://docta.ucm.es/browse/subjectucm?scope=c7e23ccb-08c5-430a-b40e-6b7b823b84e9&value=Inform%C3%A1tica%20(Inform%C3%A1tica)&bbm.return=14) y son de libre acceso. Principalmente de
la Facultad de Informática (porque siguen la normativa, sobre todo los
del año anterior), pero cualquier lectura es buena. Aunque no sea lo más
divertido del mundo leer trabajos de otros, intentad echar un vistazo a
ejemplos (por ejemplo, de compañeros vuestros que ya hayan terminado). Algunos trabajos de TFG destacables son los siguientes:

- [MMOTFG: Massively Multiplayer Online Telegram Fantasy Game](https://docta.ucm.es/entities/publication/b903e837-9ddc-4bb5-89b2-589e542d3f10)
- [Recomendador inteligente de vestimenta ](https://docta.ucm.es/entities/publication/fb8dee97-d5b5-44a5-aa51-ac26bdcef556)
- [Realidad aumentada para el Museo de América](https://docta.ucm.es/entities/publication/53f32842-9e84-48bc-9bff-d142a12d3293)
- [Sistema de matchmaking para un videojuego multijugador ](https://docta.ucm.es/entities/publication/6e3d0790-6261-4e6c-b37e-98228388f522)


# Comunicación y revisiones

En última instancia, una memoria técnica es un ejercicio de
comunicación. Se escribe para que alguien, en 1 hora, sepa todo lo
relevante que ha ocurrido durante todo un año de trabajo. Filtrar,
condensar, explicar bien las causas y las decisiones, y estructurar de
forma que el lector tenga que emplear poco esfuerzo para entender, es
fundamental.

Para que la memoria sea lo más correcta posible, es necesario revisarla en varias ocasiones una vez escrita. Pero estas revisiones empiezan por vosotros mismos, como escritores de la memoria. Cualquier revisión parcial de la memoria implica que lo que está escrito ya lo habéis revisado vosotros, por lo que no se espera que haya faltas de ortografía, erratas, comentarios al margen de la memoria o frases sin terminar (o, al menos, se intenta que no las haya). Además, es fundamental que, una vez completada, **se lea de principio a fin y como si fuese la primera vez que sea ha leído** ya que es la forma en la que la leerá el tribunal. Es un ejercicio que puede resultar algo complicado pero fundamental para ver que la memoria no presupone ningún conocimiento y que la información está en el orden correcto. 

# Fechas

Empezad a escribir cuanto antes. Cuesta mucho esfuerzo, y en general se
tiene poca práctica. Lo ideal es ir mandando versiones de la memoria para que, muy pronto, la estructura coja forma y se corrijan, cuanto
antes, los defectos básicos. 

Suele ser recomendable tener una primera versión en enero, otra versión extendida en marzo, y una versión casi final a primeros de mayo, de modo que la entrega que en el calendario aparece como borrador final sea prácticamente una versión definitiva de la memoria. 

# Plagio

Tal y como se indica en la normativa, todas las memorias de TFG pasan por un sistema antiplagio que revisa si hay partes de la memoria que han sido copiadas (de libros, de webs, de otros TFGs...). Para evitarlo es muy sencillo: **No copieis y peguéis texto de ningún sitio** y escribid con vuestras propias palabras todo lo que leais en otros documentos y que os parezca interesante.
