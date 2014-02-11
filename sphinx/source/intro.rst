##########
Preámbulo
##########


**************
Introducción
**************

Acerca de este libro
=====================

A principio de marzo de 2006, tuvieron lugar en Girona las I Jornadas sobre Sistemas de Información Geográfica (SIG) libres, organizadas por la Universitat de Girona y el Servei de Sistemes d'Informació Geogràfica i Teledetecció (SIGTE). Al amparo de ese encuentro, algunos (no muchos) decidimos aprovechar el momento para, entre otras cosas, reunirnos y fundar el capítulo hispano--hablante de `OSGeo <http://www.osgeo.org}>`_, una organización internacional cuya actividad se centra en torno a los Sistemas de Información Geográfica libres. El objetivo era intentar formar un grupo de trabajo para afrontar aquellas cuestiones de interés general para la comunidad SIG de habla hispana, y fueron muchas las tareas que en aquel momento se recopilaron como necesarias dentro del ámbito de los SIG en lengua española. Entre ellas, la creación de un libro libre sobre Sistemas de Información Geográfica.

Este libro es mi intento particular de tratar de dar solución a esa necesidad en ese momento apuntada, y recopila un trabajo realizado pacientemente desde entonces, siendo un testigo de todo el esfuerzo y desarrollo que tiene lugar en nuestros días en materia de SIG. Con él, espero que dicho desarrollo no solo continúe, sino que crezca, poniendo a disposición de la comunidad los conocimientos con los que establecer una base conceptual más sólida, así como una herramienta de máxima utilidad para la formación y transmisión de los aspectos teóricos relacionados con los Sistemas de Información Geográfica.

¿Por qué escribir este libro?
================================

Como ya quedó claro en aquella reunión fundacional del capítulo hispano--hablante de OSGeo, un libro como este era algo necesario dentro del mundo de los SIG, y lo sigue siendo hoy a pesar del tiempo que ha pasado desde entonces. Veamos con más detalle por qué.

Es difícil encontrar hoy en día una disciplina científica que no pueda sacar partido de los Sistemas de Información Geográfica y no contemple a estos como herramientas de primera línea. Incluso fuera del ámbito científico, los SIG son parte de nuestra vida diaria, y la mayoría de la gente ha usado en algún momento un callejero en Internet o un navegador GPS, elementos que forman parte del conjunto de tecnologías directamente relacionadas con los SIG y su entorno.

En una situación así, cabe esperar que el sector editorial se encuentre en un estado de similar desarrollo, y el número de obras disponibles sea no solo abundante, sino diverso, y que cubra con detalle tanto los fundamentos básicos de la disciplina como los desarrollos más recientes (que no son pocos). Esto, sin embargo, no sucede realmente así. Si hablamos del mercado editorial en español, las referencias de que disponemos no están en absoluto acordes con el buen estado del ámbito de los SIG, tanto en su desarrollo e implementación como en el volumen de negocio que generan en los países de habla hispana. 

Los principales textos de SIG en nuestro idioma fueron escritos en los años 90, cuando comenzó a asentarse el sector de los Sistemas de Información Geográfica, especialmente en España, ocupando un nicho entonces desierto dentro del mercado editorial. Lamentablemente, ninguno de estos trabajos ha sido actualizado recientemente, a pesar de que los cambios que se han producido en el sector han sido tan notables que dicha actualización resulta completamente imprescindible.
%Textos clásicos como  :cite:p:`Bosque1997Rialp` o  :cite:p:`Gutierrez1994Sintesis` son excelentes referencias al respecto, sirviendo perfectamente como obras introductorias a la disciplina de los SIG. 

A partir del año 2000, el ritmo editorial en el ámbito del SIG no decae, pero las referencias nuevas que hacen su aparición en el mercado son casi en su totalidad de corte práctico, bien sea referidas a un software en concreto, o bien a un campo de aplicación particular. Los fundamentos básicos, necesarios para cualquier operación con un SIG, quedan en estos casos explicados en base a un programa concreto, o bien se supone su conocimiento a través de otros textos.

En resumen, es un buen momento para escribir un libro sobre SIG en español, y es así porque resulta necesario recoger los conocimientos actuales en este campo, de la misma forma que se recogieron en una etapa anterior en algunos de esos textos comentados.

Pero la razón para escribir este libro no es únicamente que este sea un buen momento para escribir un libro de SIG. Porque este no es solo un libro de SIG, sino un libro *libre* sobre SIG. Y si este resulta un momento ideal para escribir un libro sobre SIG en nuestro idioma, lo es más aún si este libro es libre, tal y como el que ahora mismo estás leyendo.

El software libre ha experimentado en los últimos años un crecimiento impensable tiempo atrás. En la mayoría de áreas existen ya alternativas libres al software privativo, suficientemente maduras como para dar respuesta a todas las necesidades de los usuarios. Lejos de aquella imagen de aplicaciones muy alejadas de las necesidades y conocimientos del usuario medio, las aplicaciones libres están cada día más presentes en todos los ámbitos y a cualquier nivel de utilización, siendo su penetración muy elevada y, más importante aún, creciente. Los SIG, por supuesto, no son ajenos al movimiento del software libre, y disponemos a día de hoy de excelentes alternativas en nuestro campo.

Todas estas aplicaciones SIG libres suelen venir acompañadas de sus correspondientes textos de ayuda, habitualmente también libres, los cuales constituyen además muy buenas referencias sobre el campo de los SIG en general. Existen incluso obras no libres de gran relevancia (por ejemplo, Neteler, M. & Mitasova, H. *Open Source GIS: A GRASS GIS Approach*, Springer, New York, 2007.), con gran cantidad de información y actualizadas periódicamente en nuevas ediciones. Se puede, en resumen, leer mucho sobre SIG libres.

Sin embargo, todos estos textos libres se hallan siempre supeditados a algún software (libre casi siempre), y no existe ningún tratado completo sobre SIG que no se base en una aplicación concreta para desarrollar sus contenidos. En el mundo libre, el esfuerzo editorial va siempre de la mano del software. Y esto es así no solo en nuestro idioma, sino en todos los demás. Sorprendentemente, no hay ninguna obra libre que trate los SIG de forma genérica y pretenda dar una formación conceptual al respecto. Todos los textos libres sobre SIG son, en la actualidad, de tipo práctico en mayor o menor medida.

Así pues, es un buen momento para escribir un libro en español sobre SIG, y es un excelente momento para hacer un libro libre sobre SIG, con independencia del idioma, pues ambos son elementos necesarios. Es seguro que hay muchos lectores potenciales que quieren aprender sobre SIG, y este libro es la forma de poner a su alcance los conocimientos actuales de los que disponemos, con una obra actual y accesible. Esa es la razón por la que se ha escrito el libro que ahora tienes en tus manos (o en la pantalla de tu ordenador o en cualquier otro soporte en el que, gracias a la libertad con la que se distribuye, puede haber llegado hasta ti).

A quién va dirigido este libro
===============================

Si estás leyendo estas páginas, es probable que te interese su contenido, así que es probable también que tú seas una de las personas hacia las que va dirigido este libro. No obstante, veamos con más detalle quiénes son los lectores que se esperan para esta obra (aunque no seas uno de ellos, por supuesto puedes seguir leyendo, y me agradaría que este libro te fuera útil).

Es importante reseñar que este es un libro principalmente teórico. Está enfocado a todos aquellos que deseen aprender los fundamentos teóricos de la disciplina de los SIG, abarcando la practica totalidad de ramas de esta. Estas ramas toman elementos de muchas otras disciplinas distintas (la informática, la geografía, la matemática...), y todas ellas se han tratado a su vez con un suficiente nivel de detalle. Un lector que asimile la mayor parte de los conocimientos de este libro estará en una situación excepcional para comprender en conjunto todo lo que representan los SIG, qué tareas pueden hacerse con ellos, y entender por qué, cómo y cuándo se han de llevar a cabo dichas tareas. El objetivo es formar a alguien en materia de SIG, de tal modo que pueda posteriormente afrontar tareas relacionadas, tales como la realización de proyectos con Sistemas de Información Geográfica, o la aplicación de los SIG a un área concreta de trabajo, cualesquiera que sean las características de esta.

Aunque se trate de un libro teórico, este libro puede (y debe) convertirte en un buen usuario de SIG y ayudarte en el terreno práctico de su utilización. Tanto si eres ya usuario de SIG como si no lo eres, es probable que la lectura de estas páginas te aporte gran cantidad de información que mejorará la forma en que utilizas (o utilizarás) un Sistema de Información Geográfica, pues te ayudará a entenderlo mejor. No obstante, si lo que pretendes es aprender a utilizar un SIG y buscas un manual para ello, este no es, en principio, el libro que andabas buscando, pues no se dan indicaciones sobre cómo usar un SIG en concreto o cómo realizar procesos y operaciones con él. Podrías leer completo este libro y después no saber qué hacer ante una aplicación SIG, porque no vas a encontrar aquí cómo utilizar ninguna de ellas.

Aun así, es posible que, incluso en ese caso, este libro sí sea para ti. Si todavía no sabes utilizar un SIG y quieres aprender a ello, lo más probable es que tampoco sepas mucho sobre SIG. En tal caso, te recomiendo que empieces por aquí antes de lanzarte a aprender el manejo de una aplicación SIG. No tienes que leer necesariamente todo el libro al completo. Puedes complementar el contenido de estas páginas con el manual de usuario del SIG que elijas, e ir aprendiendo a utilizar este a medida que construyes una base sólida de conocimientos sobre la que apoyar dicho aprendizaje. 

En resumen, este es un libro orientado a quienes desean aprender con mayor o menor profundidad qué es y para que sirve un SIG, aportándoles la base necesaria para que posteriormente puedan afrontar su trabajo con un SIG, tanto si ya tienen nociones al respecto como si todavía no han utilizado uno antes.

Si al leer este libro echas en falta algo que consideras importante, házmelo saber. Estaré encantado de considerar tus propuestas para así abarcar un abanico más amplio de lectores potenciales.

Estructura
===========

En un libro de tan amplio alcance, es probable que distintos lectores tengan un interés mayor por distintos temas tratados. Por esta razón, el libro se divide en siete bloques bien definidos, de forma que, tanto conceptual como funcionalmente, presenta una estructura más adecuada para su uso.

En primer lugar, un bloque dedicado a la definición de los elementos fundamentales, que son la base para todo el desarrollo posterior. Los elementos definidos en esta parte se desglosan en las siguientes, que tratan por separado los datos espaciales, y las formulaciones que permiten el análisis de estos.

Todos los elementos anteriores requieren de una tecnología y de unas aplicaciones SIG, que son las que nos permiten manejar los datos, procesarlos o generar cartografía. Estas aplicaciones con las que se produce el trabajo en un proyecto SIG se tratan en todas sus variantes dentro de una parte específica de este libro.

La visualización de los datos espaciales y la creación de cartografía son ambos elementos básicos de los SIG, y una materia donde existe abundante desarrollo. Esto, junto con el uso inevitable que se realiza de las funcionalidades de generación cartográfica de un SIG en el empleo diario de este, hace interesante dedicar una parte independiente a este tema.

El factor organizativo, vital para entender los SIG hoy en día, se detalla en una parte independiente, una vez que ya se conocen todos los fundamentos e ideas básicas.

Por último, una parte dedicada al uso práctico y real de los SIG muestra cómo estos pueden dar soluciones a problemas muy variados, y cómo todo lo visto anteriormente en las partes previas se materializa en la práctica. 


****************
Agradecimientos
****************

Este libro no sería posible sin la ayuda de quienes contribuyeron directa o indirectamente a él, apoyándolo de una u otra manera. Quiero expresar mi agradecimiento a todos ellos por su relevante colaboración para que este libro saliera adelante.

Por encima de todo, a mis padres. Hay muchas razones por las que un día decidí escribir este libro, pero, como en todo lo que hago, saber que ellos se sentirán orgullosos de mí por hacerlo es, sin duda, la principal de todas ellas. Además, y aun no siendo expertos en SIG, me han enseñado la lección más importante acerca de cómo entender correctamente estos: que la mejor forma de conocer el mundo no es a través de un mapa o un SIG, sino viviéndolo uno mismo. Las dos citas que he añadido al inicio del libro creo que ilustran muy bien esa filosofía que tanto ellos como yo compartimos, al tiempo que describen acertadamente mi visión sobre la forma en la que debe entenderse un SIG.

A Juan Carlos Giménez, por haberme acompañado durante toda mi carrera profesional, haciendo que todo mi trabajo, incluyendo la redacción de este libro, haya sido y siga siendo una experiencia inmejorable. Personal y profesionalmente, le debo mucho más que un agradecimiento en un libro, pero supongo que esta es una buena forma de empezar a pagar esa deuda.

A los coautores de capítulos que cedieron su trabajo para que pudiera ser incorporado a este libro: Landon Blake, Miguel Luaces, Miguel Montesinos, Ian Turton y Jorge Sanz. Asimismo, Oscar Fonts ha colaborado en la corrección y ampliación de algunos capítulos con tal dedicación que he considerado justo incluirle como coautor en ellos.

A todos los que colaboran desinteresada y voluntariamente en proyectos como la Wikipedia o el proyecto Open ClipArt, los cuales han servido de gran ayuda a la hora de elaborar contenidos de esta obra, en especial los de tipo gráfico. Este libro contiene asimismo elementos gráficos tomados de publicaciones libres de diversos tipos (artículos, libros, blogs, etc.), a cuyos autores agradezco el haberlos publicado de ese modo, permitiendo que su
esfuerzo sea aprovechado por otros libremente.

A Tomislav Hengl, por ceder las plantillas \LaTeX a partir de las cuales fueron adaptadas las empleadas en este libro. Y porque en esas plantillas no iba solo un formato para este texto, sino parte de su buen hacer a la hora de escribir libros.

A la Conselleria de Infraestructuras y Transportes de la Generalitat Valenciana y el Servei de Sistemes d'Informació Geogràfica i Teledetecció (SIGTE) de la Universitat de Girona, quienes en uno u otro momento cedieron infraestructuras para la realización de reuniones de autores dentro de eventos de cuya organización eran responsables. Entre sus miembros, muy especialmente a Lluis Vicens, que apoyó este libro de forma incondicional en todo momento.

Como proyecto libre que es, este libro ha sido corregido de forma abierta y pública por cuantos han deseado contribuir de ese modo. A todos ellos quiero expresar desde aquí mi más sincero agradecimiento: Javier Carrasco, Toni Hernández, Santiago Higuera, José Manuel Llorente, Ester López, Jordi Marturià, Miguel Montesinos, Rosa Olivella, Ferrán Orduña, Joana Palahí, Nuria Pérez, Carol Puig, Jorge Sanz, Josep Sitjar, David Tabernero, Nacho Varela, Ana Velasco, Laura Vergoñós y Lluis Vicens.

He usado medios e infraestructura de la Universidad de Extremadura para escribir este libro (y alguna que otra hora de trabajo en la que debería haber estado haciendo otras cosas), por lo que agradezco la ayuda prestada, la comprensión y el buen ambiente de trabajo que siempre he tenido, imprescindible para concluir con éxito una labor así.

El control de versiones del libro lo he llevado durante la mayor parte de su redacción mediante un repositorio SVN alojado por el proyecto OSOR, el mismo que utilizo para almacenar el código fuente de SEXTANTE. Mi agradecimiento para este proyecto de la Comisión Europea por proveer un servicio gratuito de gran calidad que me ha facilitado notablemente el trabajo.

Actualmente, el texto fuente de este libro se encuentra alojado en el repositorio SVN de OSGeo, organización a la que agradezco su colaboración y la contribución realizada a este trabajo. La portada del libro utiliza el diseño corporativo de OSGeo, cedido generosamente para ello. Los miembros del capítulo hispano--hablante de OSGeo merecen un agradecimiento especial por su contribución y apoyo al proyecto.


