.. _introduccion_tecnologia:

**********************************************************
Introducción. ¿Cómo son las aplicaciones SIG?
**********************************************************


Las aplicaciones informáticas que forman parte del ámbito SIG son muy diversas, y su evolución es constante. En este capítulo presentaremos los tipos principales de aplicaciones y la forma en que estas van desarrollándose dentro de dicho ámbito SIG, y el papel que juegan en este. 

Todos estos tipos de aplicaciones no son elementos aislados, sino que se relacionan entre sí y dependen en muchos casos los unos de los otros para cobrar sentido como herramientas útiles. El objetivo del capítulo es presentar una visión global de esa realidad, mostrando los distintos elementos tecnológicos que pueden encontrarse en un entorno SIG actual.


Introducción
=====================================================

Las aplicaciones SIG son el elemento de trabajo básico dentro de todos aquellos que componen el concepto global de un SIG. Una aplicación SIG materializa todas las ideas vistas hasta el momento dentro de este libro, y es la herramienta fundamental para el trabajo con datos espaciales, lo cual constituye la tarea primordial de un SIG.

Dentro de la lógica evolución de toda tecnología informática, los SIG se han desarrollado de forma muy rápida y variada, adaptándose a una realidad, la de la propia información geográfica, también en constante evolución en todas sus vertientes. Por ello, la idea de aplicación SIG que podía encontrarse en un libro equivalente a este hace 10 o 20 años es bien distinta de la que hoy tenemos. De hecho, la concepción única de aquel entonces ya no es tal, y actualmente son muchas las formas en las que las aplicaciones SIG pueden presentarse.

Junto con la concepción *clásica* del SIG, todavía presente, existen una serie de otras tecnologías que han ido surgiendo paulatinamente, y que incorporan ideas y conceptos como los que ya conocemos de capítulos anteriores. En esta parte del libro se mostrarán todas ellas en detalle, definiendo así el panorama global de las aplicaciones SIG y los usos y funciones principales de cada una de dichas tecnologías.

Para comprender el papel que juegan las distintas formas de aplicaciones SIG que encontramos hoy en día y que trataremos en los sucesivos capítulos, es necesario analizar la forma en que han ido conformándose dentro del entorno SIG, lo cual haremos en este capítulo.

La convergencia de las aplicaciones en el ámbito SIG
=====================================================

Una de las tendencias principales a lo largo de la evolución de los SIG es a la unión de otra serie de aplicaciones o elementos de estas, enriqueciéndose con conceptos y funcionalidades que, o bien encuentran en un SIG su aplicación a la información geográfica, o bien ya la tenían pero dentro de un marco aislado. El SIG actúa como elemento de unión de todas estas tecnologías, y engloba con carácter general a aquellas herramientas que de un modo u otro puedan emplearse para el análisis y tratamiento de datos espaciales.

Con esta filosofía, el concepto de SIG ha crecido desde sus orígenes, incorporando elementos propios de otras herramientas. Su crecimiento ha sido mayor que el de otro tipo de aplicaciones, ya que ha jugado un papel central y articulador, y en lugar de únicamente aportar conceptos a estas otras aplicaciones, en su mayoría ha tomado prestado de ellas. Dentro de las aplicaciones SIG actuales encontramos elementos que provienen, entre otros, de los siguiente ámbitos.


* Análisis de imágenes
* Diseño asistido por ordenador (CAD)
* Bases de datos
* Herramientas de diseño gráfico	


Muchos de estos elementos ya se han comentado de uno u otro modo en secciones anteriores de este libro, ya que su importancia es más que notable.

Incluso dentro del propio ámbito SIG, las distintas aplicaciones han ido convergiendo paulatinamente. Las dos formas principales de almacenar la información geográfica, ráster y vectorial, conformaban originalmente también la base para las distintas aplicaciones, con escaso solape entre estas. Es decir, aquellas aplicaciones que podían manejar datos ráster y realizar operaciones con ellos, apenas tenían capacidades vectoriales o estas estaban por completo ausentes. Del mismo modo, las aplicaciones de corte vectorial no eran capaces de trabajar con datos ráster o, en todo caso, con algunas imágenes que podían representarse pero apenas analizarse.

Esta situación ha ido cambiando y, aunque en diferente forma, un SIG actual es capaz de trabajar con ambos tipos de datos con un nivel suficiente de funcionalidades. Poco a poco, todo el conjunto de tecnologías que han ido apareciendo dentro del entorno SIG se han ido extendiendo a las distintas aplicaciones, y aunque existen tipos bien definidos, estos no constituyen bloques estancos.

Así, por ejemplo, capacidades como el acceso a servicios remotos han evolucionado de forma similar a la gestión de datos ráster y vectoriales, en cuanto que han dejado de ser tecnologías exclusivas de una serie de aplicaciones para pasar a formar parte esencial del conjunto de estas. En el caso particular de estos servicios remotos, implicaron el desarrollo de servidores que eran mayoritariamente empleados desde aplicaciones Web. Con posterioridad, las aplicaciones de escritorio, más cercanas al concepto tradicional del SIG, han ido incorporando estas capacidades para ofrecer una funcionalidad similar a la de esas aplicaciones Web. En la actualidad, la integración de estos elementos va más allá, adaptando todas las restantes funcionalidades de esas aplicaciones de escritorio, muchas de las cuales no aparecen (todavía) en las aplicaciones Web, al trabajo con datos remotos.

De este modo, el trabajo actual con datos remotos se va integrando en los SIG como un elemento más, del mismo modo que ha sucedido con los distintos modelos de datos hasta alcanzar la situación actual en la que se conciben como realidades distintas pero fundamentales y complementarias dentro de un SIG.

Veremos todo lo relativo al uso de datos remotos dentro del capítulo :ref:`Servidores_y_clientes_remotos`, también dentro de esta parte del libro.


La especialización de las aplicaciones SIG
=====================================================

Al mismo tiempo que las aplicaciones SIG iban incorporando funcionalidades e ideas de distintos ámbitos, surgían tecnologías y productos paralelos enfocados a un uso más concreto dentro de un determinado campo de aplicación. El crecimiento de los SIG que se produce como consecuencia de ese afán integrador da lugar a aplicaciones sólidas y completas, que resultan sumamente versátiles al tiempo que complejas. Siendo ya una tecnología base bien desarrollada, pueden comenzar a derivarse nuevas aplicaciones SIG que se asienten sobre esa base pero que no tengan tal carácter genérico, sino que concreten su campo de actuación y las tareas para las que están diseñados principalmente.

Por una parte, encontramos aplicaciones destinadas al uso en una determinada disciplina, en las que la aplicación conserva solo aquellas capacidades que resulten de mayor interés para el objeto de esta. Las aplicaciones de este grupo pierden el carácter genérico y versátil del SIG, y normalmente integran tecnologías SIG dentro del marco de trabajo concreto de la disciplina correspondiente, aprovechando que en esta existe información geográfica susceptible de ser aprovechada mediante esas tecnologías SIG.

Por otra parte, encontramos modificaciones guiadas por los propios componentes de la herramienta, asignando más peso a elementos particulares del sistema SIG. De este modo surgen aplicaciones SIG dedicadas fundamentalmente a la gestión de datos, otras que se centran especialmente en el análisis, o bien aquellas en las que la visualización juega el papel fundamental. Sin olvidar que un SIG es ante todo un sistema, aparecen aplicaciones que concentran sus capacidades en un elemento de ese sistema. En lugar de entenderse la tecnología SIG como una aplicación que engloba a todo el sistema, se entiende ese sistema como un conjunto de aplicaciones más especializadas, cada una de las cuales compone una pieza del mismo.

Esta especialización es de mayor interés para exponer en esta parte del libro las distintas tecnologías que actualmente coexisten en el amplio mundo del SIG, y su estructura parcialmente se basa en ese criterio. Las aplicaciones particulares enfocadas a una determinada disciplina se mencionarán no aquí sino en la última parte del libro, en la que se exponen usos prácticos del SIG en determinados campos. Siempre que en estos campos existan aplicaciones específicas con componente SIG, estas serán detalladas en el capítulo correspondiente.

Tipos de aplicaciones
=====================================================

Con todo lo anterior, el panorama ante el que se encuentra hoy en día un usuario de SIG es sumamente complejo. Existen muchas aplicaciones distintas, y la dificultad de abordar su uso no es debida a su elevado número, sino a la gran cantidad de enfoques diferentes y conceptos distintos sobre los cuales estas se han desarrollado. En términos de tecnología, el mundo SIG es rico y variado, y resulta imposible tener un conocimiento profundo de todos sus representantes. En función de la actividad desarrollada, unas u otras herramientas se demostrarán de más utilidad, pero no debe olvidarse que todas ellas pueden resultar útiles en cierto modo, pues guardan el denominador común del trabajo con datos geográficos e información georreferenciada.

Podemos distinguir tres grupos principales: herramientas de escritorio, repositorios de datos, y clientes y servidores que permiten en conjunto el trabajo remoto con todo tipo de datos SIG. Las herramientas de escritorio son la tecnología informática fundamental en el campo SIG. Los repositorios de datos y los clientes y servidores han ido cobrando día a día más importancia hasta convertirse en elementos fundamentales y muy representativos del mundo SIG actual. Ya conocemos bastante acerca de las bases de datos, porque debido a su relevancia las hemos desarrollado en capítulos anteriores del libro. Los clientes, por su parte, pueden presentarse de diversas formas, tanto como aplicaciones Web como integrados dentro de las herramientas de escritorio, aunque los estudiaremos junto a los servidores, agrupando así las tecnologías Web en un único bloque.

En los siguientes capítulos veremos las características de estos grupos, así como la relación existente entre ellos. Los repositorios de datos no tienen un capítulo propio dentro de esta parte, ya que hemos hablado de ellos en partes anteriores al tratar las bases de datos, pues así parecía más conveniente dada la importancia de estas y la necesidad de conocer algo más acerca de ellas antes de abordar otros temas como, por ejemplo, las consultas.

Juntos a estos tipos de *software*, encontramos otros de tipo SIG derivados de ellos, cuyos principal representante son las aplicaciones adaptadas a dispositivos móviles. Por la importancia que están cobrando en la actualidad estas últimas, detallaremos también sus características en un capítulo adicional.

Todas estos elementos conforman el panorama global de la tecnología SIG, con un conjunto de interrelaciones similar al definido esquemáticamente en la figura :num:`#figesquematecnologiasig`. Tanto clientes Web como herramientas de escritorio (en caso de que estas últimas tengan capacidades de cliente), acceden a los servidores para obtener datos y servicios. Los servidores, a su vez, toman datos de los repositorios de datos, al igual que pueden hacer las herramientas de escritorio para el trabajo con datos locales, algo que los clientes Web no están pensados para hacer.

.. _figesquematecnologiasig:

.. figure:: Esquema_tecnologia_SIG.*
	:width: 650px
	:align: center

	Clases principales de software SIG y relaciones entre ellas


 


La adaptación de las aplicaciones SIG. El SIG como base genérica
===============================================================================
	
Los SIG han crecido mucho desde su origen y, además de ampliar horizontes y mejorar el trabajo con ellos, han añadido numerosas funcionalidades adicionales. Como cabe esperar, un SIG actual no solo permite hacer las cosas mejor, sino que también permite hacer más cosas. Como herramienta rica en capacidades, un SIG puede entenderse como una aplicación preparada para responder a todas las posibles necesidades dentro del campo del análisis geográfico.

Sin embargo, la filosofía actual de las aplicaciones SIG es distinta a la existente en los primeros desarrollos, y el objetivo principal de un SIG hoy en día no es el de constituir una herramienta que contenga todas las funcionalidades que puedan necesitarse, sino una base sobre la que estas puedan construirse. Junto a las funciones básicas de edición, manejo de datos y análisis, un SIG permite la adaptación de estas a las necesidades concretas de cada trabajo, siendo así una herramienta versátil que puede tomar una u otra forma en función de las circunstancias particulares de cada uso.

La adaptabilidad de SIG es una de sus principales virtudes, y es la que permite que puedan desarrollarse útiles válidos para cada caso. Un SIG no es, por tanto, una herramienta cerrada con un conjunto de elementos suficiente para dar respuesta a todas las necesidades, y la obtención de una herramienta SIG final para un determinado trabajo no es un proceso único sino un desarrollo en dos etapas. 

La primera de estas etapas implica el desarrollo del propio SIG como tal, y la segunda concierne al desarrollo de elementos adicionales que completan la herramienta según las necesidades propuestas, apoyándose sobre los componentes fundamentales. Aunque muchos usuarios tendrán suficiente con un SIG en su forma original, muchos otros necesitarán desarrollos adicionales, o bien se beneficiarán de ellos al poder lograr sustanciales mejoras en comparación con el empleo del SIG básico.

Debido a este esquema de trabajo, el usuario SIG ha de ser en ocasiones un usuario técnico y cualificado, o bien ha de necesitar el concurso de alguien capaz de desarrollar sobre un SIG herramientas adicionales. La figura del programador SIG es importante dentro de un proyecto SIG, y hace que la gestión de la tecnología tenga la misma relevancia que la gestión de los datos o de cualquier otro de los restantes componentes globales de un SIG.

La idea de un SIG como herramienta base es especialmente patente en el caso de las aplicaciones de escritorio, las cuales concentran una gran mayoría del trabajo desarrollado dentro de un proyecto SIG, lo cual las hace especialmente aptas a constituirse como herramientas básicas sobre las que se desarrollan modificaciones destinadas a responder a las necesidades del proyecto. No obstante, también otras aplicaciones SIG son susceptibles de jugar ese mismo papel.

En el caso de las aplicaciones Web, estas se adaptan para crear accesos particulares a unos datos concretos, de forma que pueden emplearse para dar acceso a la información geográfica a través de Internet, y hacerlo de una forma particular en cuanto a la apariencia y las funcionalidades ofrecidas. Los servidores se prestan de igual modo a ser adaptados en la medida de lo necesario.

Aunque la presencia de elementos para facilitar esa adaptabilidad (lenguajes de programación integrados, arquitecturas escalables, etc.) es general, la aparición de alternativas libres competitivas dentro del mercado del SIG ha potenciado más aún el desarrollo de herramientas adaptadas, al permitirlo en mayor grado. Puedes encontrar más sobre las diferencias entre software libre y software privativo en el apartado :ref:`Software_libre_vs_privativo`, con especial atención a las aplicaciones SIG.


Resumen
=====================================================

A partir de la concepción inicial de los SIG como aplicaciones bien definidas en las cuales se reunían las funcionalidades principales de estos, se ha desarrollado en la actualidad un amplio panorama de aplicaciones bien diferenciadas, las cuales podemos dividir en tres grupos principales: herramientas de escritorio, repositorios de datos y clientes y servidores. 

Estos tipos de aplicaciones se encuentran interrelacionados y se apoyan unos en otros para ofrecer todo el conjunto de capacidades actuales de los SIG.

Para llegar hasta este punto, los SIG han tomado elementos de otras aplicaciones, congregándolos en un único software. Al mismo tiempo, se han ido especializando en distintos ámbitos, dividiendo así el total de áreas de posible trabajo de este tipo de tecnologías.

En la actualidad los SIG forman una base genérica sobre la cual se construyen herramientas de análisis geográfico adaptadas a distintos fines.
