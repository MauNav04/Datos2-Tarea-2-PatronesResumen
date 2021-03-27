Impacto de los Patrones de Diseño Orientado a Objetos en el Desarrollo de Software

Resumen- Los patrones de diseño de software tienen una serie de beneficios para el desarrollo de
software y los desarrolladores, en términos como la velocidad y el aprendizaje, pero también para crear
sistemas de software orientados a objetos (OO); sin embargo los patrones de diseño de software son
muy abstractos todavía hay mucho que hacer y mejorar. Revisemos los pros y los contras.
Los patrones de diseño orientados a objetos se introdujeron a mediados de la década de 1990 para
proporcionar soluciones a problemas de diseño comunes. Su reutilización se ha mejorado utilizando
conceptos como la herencia y el polimorfismo. La noción de patrones fue introducida por Christopher
Alexander, quien identificó y trató de resolver problemas arquitectónicos comunes, ya que se dio cuenta
de que había algunas características, problemas y soluciones comunes que se pueden utilizar, resolver y
mejorar mediante la implementación de patrones de diseño.
En general, los patrones de diseño ofrecen una forma de reutilizar mucha experiencia, pero no significa
necesariamente que la reutilización se limite a repetir la misma experiencia, ya que proporcionan
respuesta a cómo, cuándo, por qué o dónde se pueden utilizar, por lo que se pueden utilizar en muchas
situaciones diferentes y la solución se confecciona para cada contexto particular.

2. Trabajos relacionados

Ackerman L y González C introducen a los desarrolladores y arquitectos en la idea de que el uso de
patrones de diseño como un artefacto que permite la codificación de una especificación de patrón para
un entorno específico y puede ser creado y utilizado para diferentes fases. Rising. L analiza un ejemplo
en el que un patrón nuevo llamado Mediador se adapta perfectamente a los retos de un diseño que
estaba llevando horas de trabajo.
En un análisis realizado para comprobar la reutilización y la extensibilidad, para comparar los pros y los
contras entre los patrones de diseño y los diseños alternativos, se demostró que los patrones
proporcionan una solución que es más extensible, pero la conclusión no se puede generalizar para todos
los patrones. Appostollos 2006 evaluó los patrones de diseño en el desarrollo de juegos, demostrando
su mantenibilidad, pero sólo para los juegos.
Yacoub, S.A., Ammar, H. H., &amp; Mili A., enseña a los desarrolladores los beneficios de la abstracción de los
patrones de diseño explicando las dependencias y la colaboración entre patrones mientras se ocultan
los detalles de la implementación. Douglas c. Schmidt y Paul Stephenson, presentan un caso de estudio
sobre la implementación de patrones (Reactor y Acceptor) en telecomunicaciones OO, para plataformas
UNIX y Windows NT OS, también muestra la limitación de su uso en sistemas comerciales de
telecomunicaciones.
Fowler, M. (2003), explica que los patrones escritos ayudan a educar a otros miembros del equipo para
construir y revisar el software. T Cline, M.P. (1996), ventajas y desventajas de los patrones de diseño,
ayuda a los profesionales de TI que quieren aprender más o desean promover el uso de patrones de
diseño.

3. Catálogo de patrones de diseño

Los patrones de diseño ayudan a acelerar el proceso de desarrollo al proporcionar paradigmas ya
probados. Su reutilización mejora la legibilidad del código para los usuarios familiarizados con los
patrones. Un inconveniente es el uso de los mismos nombres para diferentes patrones.
Existen 3 clases básicas de patrones de diseño:
Patrones de diseño estructural: Estos patrones tienen que ver con la composición de clases y objetos.
Los patrones estructurales de creación de clases utilizan la herencia para componer interfaces, mientras
que los patrones estructurales de objetos definen formas de componer objetos para obtener nuevas
funcionalidades. (Por ejemplo: .adapter, decorator, bridge, composite, flyweight, façade y proxy).
Patrones de diseño de creación: Se refieren a la instanciación de clases. Dos ideas dominantes:
1. Encapsular el conocimiento sobre las clases concretas que utiliza el sistema.
2. Ocultar cómo se crean y combinan las instancias de estas clases concretas.
También se clasifican en patrones Object-creational (creación de objetos) y patrones Class-creational
(creación de clases). Los patrones objeto-creación difieren parte de su creación de objetos a otro objeto,
los patrones clase-creación difieren su creación de objetos a subclases Gang of Four. (Por ejemplo:
abstract factory, builder, factory method, singleton y prototype).
Patrones de diseño de comportamiento: identifican patrones de comunicación comunes entre objetos y
realizan la asignación de responsabilidades entre objetos. (Por ejemplo: observer, chain of responsibility,
interpreter, iterator, memento, template method, command, visitor, strategy y mediator).

4. Cómo seleccionar un patrón de diseño

¿Cuáles son los patrones y cuál seleccionar?
Según el libro de GoF hay 5 enfoques principales:
1. Repositorios de patrones y catálogos de patrones (disponibles en línea)
2. Sistemas de recomendación (según una recomendación específica)
3. Lenguajes formales (algunos utilizan lenguajes formales)
4. Motores de búsqueda (Utilizan motores de búsqueda)
5. Otros enfoques (no clasificables)
Algunas cosas buenas a considerar cuando se selecciona un patrón son:
-Considerar cómo los patrones de diseño resuelven los problemas de diseño.
-Estudiar las secciones de intención de todos los patrones del catálogo
-Estudiar cómo se interrelacionan los patrones
-Estudiar los patrones de propósito similar
-Examinar las causas del rediseño
-Considerar qué debe ser variable en el diseño

5. Cómo utilizar los patrones de diseño

Hay que leer el patrón de diseño completo, prestando especial atención a las secciones de aplicabilidad
y consecuencias. Revisar la estructura de las secciones de participantes y colaboraciones, entender
cómo se relacionan las clases y los objetos. Estudiar el código. Elegir nombres significativos para los
participantes. Defina las clases definiendo la interfaz, la herencia, las relaciones y las variables de
instancia que representan los datos y las referencias a los objetos. La definición de nombres específicos
para las operaciones depende de la aplicación.
La sección de implementación ofrece orientación en la implementación. La sección de código de
ejemplo también debe ser de ayuda.

Ventajas:

- Reducen el tiempo de desarrollo, ya que se implementan soluciones conocidas en de “reinventar la rueda”.
- Proveen flexibilidad y extensibilidad
- Facilitan la comunicación entre equipos de desarrollo de software
- Carecen de especificación
- Capturan conocimiento entendido implícitamente
- Promueven medios estructurales para documentar arquitecturas de software.
- Son una solución conocida para construir sistemas de software y proveer soluciones a problemas recurrentes.
- Modifican el diseño inicial para mejorar la adaptabilidad y facilitar futuros cambios al software.
- Facilita la reutilización de diseños exitosos y evita alternativas que disminuyen su capacidad para reutilizarlo.
- Mejora la comunicación y el proceso de TI.

Desventajas:
- Sigue siendo un arte que solo puede ser dominado después de usarlo por muchos años.
- Provoca falta de ingeniería y exceso de ingeniería.
- De vez en cuando tienen como objetivo solucionar el problema equivocado.
- Su uso no necesariamente mejora la calidad del programa.
- Los desarrolladores y gerentes deben tener en mente que aprender un conjunto de patrones no implica tener buenas habilidades de implementación y diseño.
- Pueden incrementar la complejidad del programa
- Varios patrones convencionales tienden a ser muy abstractos.
- Uso del patrón de diseño inapropiado.
- Sobrecarga de patrones.
- No funcionan como una varita mágica que simplifica diseños complicados y problemas de implementación.
